# ultra-reusable-workflow

## Inputs

<!-- AUTO-DOC-INPUT:START - Do not remove or modify this section -->

|   INPUT    |  TYPE  | REQUIRED | DEFAULT |           DESCRIPTION            |
|------------|--------|----------|---------|----------------------------------|
| aws_region | string |   true   |         | The full name of the <br>region  |

<!-- AUTO-DOC-INPUT:END -->

## Secrets

<!-- AUTO-DOC-SECRETS:START - Do not remove or modify this section -->

|        SECRET         | REQUIRED |      DESCRIPTION      |
|-----------------------|----------|-----------------------|
| aws_secret_access_key |   true   | AWS Secret Access Key |

<!-- AUTO-DOC-SECRETS:END -->

## Outputs

<!-- AUTO-DOC-OUTPUT:START - Do not remove or modify this section -->
No outputs.
<!-- AUTO-DOC-OUTPUT:END -->











## Example Usage

```yml
name: Run Example

jobs:
  aws:
    uses: vincentclee/ultra-reusable-workflow/.github/workflows/workflow.yml@master
    with:
      aws_region: us-east-1
```
