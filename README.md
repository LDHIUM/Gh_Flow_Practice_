# gh-flow-practice

## Process

```shell
# 1. Local works
$ git branch feature/{featurename}
$ git switch feature/{featurename}

# do work

$ git status
$ git add {filename}
$ git commit
$ git push -u origin feature/{featurename}
```

2. Open pull request on github.com
3. Confirm and Merge
4. Delete branches both local and remote
5. `$ git pull origin main` on branch main to update local main branch
