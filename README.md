# git-cheatsheet
Frequently used series of commands in Git

## Start a new branch and push it to GitHub

1. Create and switch to a new branch (here: featurebranch)

```
git checkout -b featurebranch
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
git push origin featurebranch
```
    
5. Start tracking the remote branch

```
git branch -u origin/featurebranch
```
    
6. Create a pull request on GitHub

7. Continue committing on the branch and pushing while discussing development with collaborators on GitHub


## Merge a local branch, delete a local branch, push changes, delete a remote branch

1. Switch to receiving branch (here main)

```
git checkout main
```

2. Merge feature branch (here: featurebranch)

```
git merge featurebranch
```

3. (Eventually manage merge conflict)

4. Delete local feature branch

```
git branch -d featurebranch
```

5. Push changes to main

```
git push
```

6. Delete remote branch 

```
git push origin --delete featurebranch
```
