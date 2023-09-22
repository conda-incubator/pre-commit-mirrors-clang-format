clang-format(-conda) mirror
===================

Mirror of clang-format for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For clang-format: see https://clang.llvm.org/docs/ClangFormat.html

### Using clang-format with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-clang-format
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: clang-format-conda
```

