# Pre-commit hooks

Custom pre-commit hooks for [pre-commit.com](https://pre-commit.com/).

## poetry-tag-checker

Enforce pyproject.toml version to be synchronized with latest git tag through [Poetry](https://python-poetry.org/). 

```
repos:
- repo: https://github.com/zifeo/pre-commit
  rev: 0.1.0
  hooks:
  - id: poetry-tag-checker
```



