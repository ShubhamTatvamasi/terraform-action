# Terraform LocalStack

We will use LocalStack `providers.tf` file. \
Add your terraform variables in environment as per your need.

```yaml
name: Terraform LocalStack

on: [push, pull_request]

jobs:
  terraform-localstack:
    runs-on: ubuntu-latest
    env:
      TF_VAR_ec2_instance_count: 1
    steps:

    - name: Checkout
      uses: actions/checkout@v3

    - name: Terraform LocalStack
      uses: ShubhamTatvamasi/terraform-localstack-action@master
```
