fallow mirror
================

Mirror of fallow package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For fallow: see https://github.com/fallow-rs/fallow


### Using fallow with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/s-weigand/pre-commit-mirrors-fallow
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: fallow
