# terraform-localstack-action

```yaml
name: Terraform LocalStack

on: [push]

jobs:
  terraform-localstack:
    runs-on: ubuntu-latest
    steps:

    - name: Checkout
      uses: actions/checkout@v3

    - name: Terraform LocalStack
      uses: ShubhamTatvamasi/terraform-localstack-action@master
```
