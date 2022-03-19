# Terraform LocalStack

Place your **provider** code block config inside `provider.tf` file, which will be replaced by LocalStack provider.


```yaml
name: Terraform LocalStack

on: [push, pull_request]

jobs:
  terraform-localstack:
    runs-on: ubuntu-latest
    steps:

    - name: Checkout
      uses: actions/checkout@v3

    - name: Terraform LocalStack
      uses: ShubhamTatvamasi/terraform-localstack-action@master
```
