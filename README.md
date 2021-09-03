# git-cheatsheet
Frequently used series of commands in Git

## Start a new branch and push it to GitHub

1. Create and switch to a new branch

```
git checkout -b newbranch
```
2. Examine your branches

```
git branch -vv
```

3. Stage and commit your changes

```
git add myfile
git commit -m "My commit message"
```

4. Push the new branch to GitHub

```
git push origin newbranch
```
    
5. Start tracking the remote branch

```
git branch -u origin/newbranch
```
    
6. Create a pull request on GitHub

7. Continue committing on the branch and pushing while discussing development with collaborators on GitHub

