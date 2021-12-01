# minihooks
git hooks which is not hidden

```
./
  .git/
  pre-commit
  pre-push
```

Just write vanilla shell in the hook files.

`minihooks` also provides `npm prepare` style project initialization which `core.hooksPath` does not have.

## Utilities

`minihooks` provides some utilities to avoid template hook scripts.

```
mh-avoid-master
mh-commit-message-rule
mh-branch-name-rule
mh-avoid-secret-key
```

## FAQ

###  Why not `husky`?

###  Why not just use `core.hooksPath`?

