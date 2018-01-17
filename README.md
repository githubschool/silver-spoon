# silver-spoon
GitHub Repository for Class


# git visualization tool

http://git-school.github.io/visualizing-git/
```
git checkout -b sprint-dev
git checkout master
git commit
git checkout sprint-dev
git commit
git checkout -b new-feat
git commit
git checkout sprint-dev
git commit
git checkout new-feat
git commit
git commit
git commit
git commit
git checkout sprint-dev
git merge new-feat
git checkout master
git merge sprint-dev
```

### Git Ignore Alias

```
alias.ignores=!(curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/master/VisualStudio.gitignore) && git add . && git commit -m “gitignore” && :
```
