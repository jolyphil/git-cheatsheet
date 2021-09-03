# git-cheatsheet
Frequently used series of commands in Git

## Start a new branch and push it to GitHub

1. Create and switch to a new branch

```gitconfig
git checkout -b newbranch
```

2. Stage and commit your changes

    git add <myfile>
    git commit -m "<my commit message>"
    
3. Push the new branch to GitHub

    git push origin newbranch
    
4. Start tracking the remote branch

    git branch -u origin/newbranch
    
5. Create a pull request on GitHub

6. Continue committing on the branch and pushing while discussing development with collaborators on GitHub

