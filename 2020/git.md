# How to download, intialize and use git

## Download git using different methods

### Windows

- Windows 10 can use [WSL](https://docs.microsoft.com/en-us/windows/wsl/about)(windows subsystem for linux) to run a Linux system as tool, it includes git can be used as in linux directly. 

- Install Git from web as a windows application

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