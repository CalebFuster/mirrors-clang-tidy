clang-tidy mirror
===================

Mirror of `clang-tidy` package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For clang-tidy: see https://github.com/ssciwr/clang-tidy-wheel


### Using clang-tidy with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/CalebFuster/mirrors-clang-tidy
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: clang-tidy
```
