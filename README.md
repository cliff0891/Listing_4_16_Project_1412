# Listing_4_16_Project_1412: Generating a random uppercase letter 

## Introduction

## Outline

## References/Literature

## Code

## Console output: Testing results

## Command Prompt: Git commands

Before we started using the command prompt, first we set up a new Java 
project and class. Next we tied our local work to github.com

*dir* to show what is in the directory.
```
E:\COMSC_1033_Workspace>dir
 Volume in drive E has no label.
 Volume Serial Number is CF21-6DC3

 Directory of E:\COMSC_1033_Workspace


11/02/2015  10:27 AM    <DIR>          Listing_4_16_Project_1412
               1 File(s)            188 bytes
              17 Dir(s)   8,057,962,496 bytes free
```
Next we use *cd* to change directories into our project folder.
```
E:\COMSC_1033_Workspace>cd Listing_4_16_Project_1412
```
Use *dir* to verify that we can see the bin and src folders
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>dir
 Volume in drive E has no label.
 Volume Serial Number is CF21-6DC3

 Directory of E:\COMSC_1033_Workspace\Listing_4_16_Project_1412

11/02/2015  10:27 AM    <DIR>          .
11/02/2015  10:27 AM    <DIR>          ..
11/02/2015  10:27 AM               401 .project
11/02/2015  10:27 AM    <DIR>          src
11/02/2015  10:27 AM    <DIR>          bin
11/02/2015  10:27 AM               232 .classpath
               2 File(s)            633 bytes
               4 Dir(s)   8,057,962,496 bytes free
```

Now we start to follow through the instructions from 
Github.com to set up the new repository.

1. Echo a read me file.
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>echo # Listing_4_16_Project_14
12 >> README.md
```
2. Initilize the repository.
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git init
Initialized empty Git repository in E:/COMSC_1033_Workspace/Listing_4_16_Project
_1412/.git/
```
add our files
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git add .
```
Configure our user name and email.
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git config user.name "Jeremy E
vert"

E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git config user.email "jeremy.
evert@swosu.edu"
```
Make our first commit.
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git commit -m "first commit"
[master (root-commit) dbbb394] first commit
 5 files changed, 36 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .project
 create mode 100644 README.md
 create mode 100644 bin/Listing_4_16.class
 create mode 100644 src/Listing_4_16.java
```
Make connections to github.
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git remote add origin https://
github.com/jeremy-evert/Listing_4_16_Project_1412.git

E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git push -u origin master
Username for 'https://github.com': jeremy.evert@swosu.edu
Password for 'https://jeremy.evert@swosu.edu@github.com':
Counting objects: 9, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 1.20 KiB | 0 bytes/s, done.
Total 9 (delta 0), reused 0 (delta 0)
To https://github.com/jeremy-evert/Listing_4_16_Project_1412.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
```
Make a new branch dev using *git checkout -b*
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git checkout -b dev
Switched to a new branch 'dev'
```
Connect this branch to the remote.
```
E:\COMSC_1033_Workspace\Listing_4_16_Project_1412>git push -u origin dev
Username for 'https://github.com': jeremy.evert@swosu.edu
Password for 'https://jeremy.evert@swosu.edu@github.com':
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/jeremy-evert/Listing_4_16_Project_1412.git
 * [new branch]      dev -> dev
Branch dev set up to track remote branch dev from origin.
```
and life is good.




## Summary

