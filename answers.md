1.) git version 2.43.0.windows.1

2.)  PS C:\Users\tenno\git-lab\git-lab> git config --list
pack.packsizelimit=2g
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files (x86)/Git/mingw32/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Tennon77
user.email=ts083822@ohio.edu

3.) It shows all the subcommands of git --help

4.)PS C:\Users\tenno\git-lab\git-lab> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\tenno\git-lab\git-lab>

5.) PS C:\Users\tenno\git-lab\git-lab> git status
On branch main
Your branch is up to date with 'origin/main'.

6.) It was red before now it is green

nothing to commit, working tree clean
PS C:\Users\tenno\git-lab\git-lab>

7.)On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\tenno\git-lab\git-lab>

8.)PS C:\Users\tenno\git-lab\git-lab> git log
commit b5d1d002eb6613c0f429dacffa5e8baac078f58c (HEAD -> main, origin/main)
Author: Tennon77 <ts083822@ohio.edu>
Date:   Tue Jan 23 11:15:36 2024 -0500

    gotta love it

9.)I completed questions seven after following step 8 in the preview file. 9 and 7 have the same repository status.; 

10.) Not without git pull

11.) Everything up-to-date

12.) remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 923 bytes | 71.00 KiB/s, done.
From https://github.com/Tennon77/git-lab2
   98e19fe..1c648b1  main       -> origin/main
Updating 98e19fe..1c648b1
Fast-forward
 README.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)
PS C:\Users\tenno\git-lab\git-lab2\git-lab2>

13.)  Directory: C:\Users\tenno\git-lab\git-lab2\git-lab2\git-lab2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         1/23/2024   4:42 PM          44622 a.exe
-a----         1/23/2024   4:31 PM            327 git-lab-program.cc
-a----         1/23/2024  12:32 PM             36 README.md