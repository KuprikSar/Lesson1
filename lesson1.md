# _Git and GitHub instruction_

## 1. Git Setup
For setup Git follow [this site](http://git-scm.com/) and download .exe file. After setup check a git in a terminal with command `git --version`.
You can see something that:
```
git version 2.15.0
```
If you see that - setup is correct

## 2. Git Settings
After setup you need a introduce. 

* `git config --global user.email "you@example.com"`
* `git config --global user.name "your Name"`

## 3. Git commands
* `git --version` - check a version of git
* `git init` - create a local repository
* `git add` - add file/directory to repository
* `git commit -m "comment"` - create a save point
* `git log` - show a save points history
* `git log --oneline` - show a short history save points
* `git chekout <branchname>` - move to branch <branchname> actual version
* `git checkout xxxxxx` - step to xxxxxxx save point
* `git branch` - look a branch name
* `git branch <branchname>` - create a new branch branchname
* `git merge <branch_name>` - merge branch from branchname
* `git branch -d <branchname>` - delete branch branchname

## 4. Git Initialization
Open a project folder. Open a Terminal and type `git init`. For add file to repository type `git add filename.xxx`. For create a first save point type `git commit -am "init commit"`. Git is initializated.

## 5. Write a changes to repository
After changes in file, you need a save it (command+s) before create save point. For write changes in repository type a command `git commit -am "comment"`. For check a save pont type a `git status`. You can see something that:
```
On branch draft
nothing to commit, working tree clean
```

## 6. Look a commit history
For look a history type a `git log` or a short type a `git log --oneline`.

## 7. Move to save point
For move to save point in branch type `git checkout save_pont_code`. For move to actual version in selected branch `git checkout branchname`. 

## 7. Image paste

![image_paste](baba.jpg)

## 8. Ignore file
Dirst of all, you need add a ignore file with name `.gitignore`. Open this file and type name/directory of what do you want to ignore. For ignore a full class jpg file, type a `*.jpg`.

## 9. Create a branches
