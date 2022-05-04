# Git
## Checkout remote branch
```sh
git branch -r
git fetch origin {BRANCH}
git checkout {BRANCH}
```

## Revert Change
```sh
git log
git revert {Commit ID}
git push -u origin HEAD
```

## Add tag to the specified commit
```sh
git tag -a "v1.x" -m {Comment} {Commit ID}
git push origin "v1.x"
```
