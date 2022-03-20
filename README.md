# Terraform LocalStack

We will use LocalStack `providers.tf` file.

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
