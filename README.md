# clang-format pre-commit hook

pre-commit hook of clang-format with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For clang-format: see [here](https://clang.llvm.org/docs/ClangFormat.html)

## Using clang-format with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-clang-format
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: clang-format-conda
```
