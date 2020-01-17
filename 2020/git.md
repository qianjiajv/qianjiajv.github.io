# How to download, intialize and use git

## Download git using different methods

### Windows

- Windows 10 can use [WSL](https://docs.microsoft.com/en-us/windows/wsl/about)(windows subsystem for linux) to run a Linux system as tool, it includes git can be used as in linux directly. 

- Install [git](https://gitforwindows.org/) from web as a windows application

### Linux

Such as Ubuntu, input `$ git` to test git has download in the system or not. And if you don't have the git in linux, input `$ sudo apt-get install git`.

### Mac OS

I'm sorry to tell you i've never used it. （；´д｀）ゞ

## Intialization

- After installed, we must tell the computer who are your. So,  Use the follow command.
```
$ git config --global user.name "Your Name" # change Your Name in "" as your own name
$ git config --global user.email "email@example.com" # change email@example.com in "" as your email 
```
### Use

- `git init` create a new folder, and use this command to have a workstation
- `git add -A` add all change
- `git diff <file>` have the change of your file with last
- `git log` have the change detailed history
- `git log --pretty=oneline` have the change history as one line
- `git reset --hard HEAD^` reset as last version
- `git commit -m 'details'` commit change to git, and add details to explain what change you do.
- `git remote add origin git@github.com:user/repo.git` connect to your repository from github. The `origin` is name of the default remote machine 
- `git clone git@github.com:user/repo.git` clone repository from github to your computer
- `git status` have your workstation's status
- `git push -u origin master` push the workstation's change to remote machine. The `master` is the branch your want to push
- `git pull origin master` pull the status from remote
- `git remote` have the remote status
- `git checkout -- <file>...` to discard changes in working directory
- `git checkout -b example` create a new branch an checkout it
- `git branch` have the branch status
 