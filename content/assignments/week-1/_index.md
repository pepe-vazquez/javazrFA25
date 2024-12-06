---
title: Week 1
type: docs
prev: assignments/finalproject
next: assignments/week-2
---

This is my first week at FabAcademy.

## Principles and practices. Project Management

## GIT

$ git config --global user.name "myname"  
$ git config --global user.email "myname@mail.org"  
Check SHH KEY  
$ cat ~/.shh/id_rsa.pub  
cat: /c/Users/myname/.shh/id_rsa.pub: No such file or directory  
Generate SSH KEY  
 ssh-keygen -t rsa -C myname@mail.org  
Generating public/private rsa key pair.  
Enter file in which to save the key (/c/Users/myname/.ssh/id_rsa):  
Created directory '/c/Users/myname/.ssh'.  
Enter passphrase for "/c/Users/myname/.ssh/id_rsa" (empty for no passphrase):  
Enter same passphrase again:  
Your identification has been saved in /c/Users/myname/.ssh/id_rsa  
Your public key has been saved in /c/Users/myname/.ssh/id_rsa.pub  
The key fingerprint is:  
*********  
The key's randomart image is:   
+---[xxx 1234]----+  
+----[xxx123]-----+

Visualise shh key  
$ cat ~/.ssh/id_rsa.pub

ssh-rsa
ABCDEFGHIJKLMNÑOPQRSTUVWXYZ*****

Visualize git configuration
$ cat .gitconfig
[user]
        name = myname
        email = myname@mail.org

        [color]
        ui = true

Setup local git project
$ mkdir myfolder
$ cd myfolder

Initializing git
$ git init
Initialized empty Git repository in C:/Users/myname/myfolder/.git/

Crear archivo readme.md
git add 
git commit -m "my first file"
git push 

Stablish a secure connection with GITHUB
Copy shh key to clipboard
$ clip <~/.ssh/id_rsa.pub
and Add new key
![](images-01/gitlabsshkeys.jpg)


Copy link name from CODE
git clone https://github.com/user/project.git
git clone https://gitlab.com/user/project.git

Copy link name from CODE