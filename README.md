# shellcheck pre-commit hook

pre-commit hook of shellcheck with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For shellcheck: see [here](https://github.com/koalaman/shellcheck)

## Using shellcheck with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-shellcheck
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: shellcheck-conda
```
