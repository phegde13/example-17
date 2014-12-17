Welcome to Git (version 1.9.4-preview20140929)


Run 'git help git' to display the help index.
Run 'git help <command>' to display help for specific commands.

A555364@CLB6CS1 ~
$ ssh-keygen -t rsa -C "prasanna.hegde2@target.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/h/.ssh/id_rsa):
/h/.ssh/id_rsa already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /h/.ssh/id_rsa.
Your public key has been saved in /h/.ssh/id_rsa.pub.
The key fingerprint is:
e6:a4:30:4d:7e:73:75:55:87:ce:04:cc:a5:6d:f6:82 prasanna.hegde2@target.com
The key's randomart image is:
+--[ RSA 2048]----+
|           o.o..=|
|            ooo..|
|      .     o+=  |
|     +     . =o. |
|    o o S . E . .|
|     o * o     . |
|      . .        |
|                 |
|                 |
+-----------------+

A555364@CLB6CS1 ~
$ clip < ~/.ssh/id_rsa.pub

A555364@CLB6CS1 ~
$ git config user.name
A555365

A555364@CLB6CS1 ~
$ pwd
/h

A555364@CLB6CS1 ~
$ cd /c

A555364@CLB6CS1 /c
$ pwd
/c

A555364@CLB6CS1 /c
$ git init example-17
Initialized empty Git repository in c:/example-17/.git/

A555364@CLB6CS1 /c
$ cd example-17

A555364@CLB6CS1 /c/example-17 (master)
$ pwd
/c/example-17

A555364@CLB6CS1 /c/example-17 (master)
$ git config --local user.name

A555364@CLB6CS1 /c/example-17 (master)
$ git config --local user.name "GitHub Student"

A555364@CLB6CS1 /c/example-17 (master)
$ git config --local user.email "prasanna.hegde2@target.com"

A555364@CLB6CS1 /c/example-17 (master)
$ git config --local --list
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
core.hidedotfiles=dotGitOnly
user.name=GitHub Student
user.email=prasanna.hegde2@target.com

A555364@CLB6CS1 /c/example-17 (master)
$ git config --global color.ui auto

A555364@CLB6CS1 /c/example-17 (master)
$ git config --global core.autocrlf true

A555364@CLB6CS1 /c/example-17 (master)
$
version 2.1.2 for intermediate training diff from staged
intermediate training diff from staged