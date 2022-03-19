# terraform-action

```yaml
name: Terraform LocalStack

on: [push]

jobs:
  terraform-localstack:
    runs-on: ubuntu-latest
    steps:

    - name: Terraform LocalStack
      uses: ShubhamTatvamasi/terraform-action@master
```
