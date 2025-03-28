<h1>Command 01</h1>

winget install --id Git.Git -e --source winget

________________________________________________________________________
Found Git [Git.Git] Version 2.49.0
This application is licensed to you by its owner.
Microsoft is not responsible for, nor does it grant any licenses to, third-party packages.
Downloading https://github.com/git-for-windows/git/releases/download/v2.49.0.windows.1/Git-2.49.0-64-bit.exe
  ██████████████████████████████  67.0 MB / 67.0 MB
Successfully verified installer hash
The installer will request to run as administrator, expect a prompt.
Successfully installed

<h1>Command 02</h1>

git init

________________________________________________________________________
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try  
again.
At line:1 char:1
+ git init
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

<h1>Command 03</h1>

git push

________________________________________________________________________
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try 
again.
At line:1 char:1
+ git push
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS H:\cinescope-dashboard>
 *  History restored 

<h1>Command 04</h1>

git push

________________________________________________________________________
fatal: No configured push destination.


and then push using the remote name

    git push <name>


<h1>Commands</h1>
git remote add origin https://github.com/leavingnadir/Cinescope-Dashboard.git
git status
git remote -v
git branch -M main
git push -u origin main

________________________________________________________________________
info: please complete authentication in your browser...
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 8 threads
Compressing objects: 100% (22/22), done.
Writing objects: 100% (24/24), 56.83 KiB | 4.74 MiB/s, done.
Total 24 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/leavingnadir/Cinescope-Dashboard.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
