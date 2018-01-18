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

- **For BASH**

 for d in {1..6};
 do touch file$d.md;
 git add file$d.md;
 git commit -m "adding file $d";
 done
 
 
 - **PowerShell:**

 for ($d=1; $d -le 6;$d++) {
   touch file$d.md;
   git add file$d.md;
   git commit -m "adding file$d.md";
 }
