> This repository is made to learn how git commands are used in while working on version control system along with the fellow peers.

> Below is the list of commands used and learned while demonstrating the git commands from local machine

# Important git commands

## Setup gitbash
>Configure local user email id
```bash
    git config --global user.email "you@email.com"
```

>Configure local user name
```bash
    git config --global user.name "Your Name"
```

### Beginner level commands

- `git init` -> it initializes a new git repository. Repository is a folder managed by git where we can track all the changes we are making in the project.

- `git add <filename>` -> starts tracking your new change for next commit

- `git commit -m "<message>"` -> this creates a new version based on your prev changes

- `git rm --cached <filename>` -> to bring back the whole file all together to the working area/unstage area/untracked area (to undo the file)

- `git restore --staged <filename>` -> The new modified changes that we pushed in the staging area only those changes are back (to undo the changes of already added file)

- `git branch` -> To see all the branches

- `git checkout -b "branch name"` -> To checkout and enter in new branch

- `git checkout "branch name"` -> to checkout to already existing branch

- `git merge "branch name"` -> to merge branches

- `git pull origin master` -> on the master branch whatever are the latest changes bring them and add them to the commits

- `git clone "repository url"` -> to clone the repository in our localhost

- `git commit --amend` -> to add the commit to the previous added one

>Feel free to fork and add more commands if you wish too!!
