Answer 1) git version 2.26.2.windows.1
Answer 2) diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager
user.name=Paola
user.email=pg748418@ohio.edu

Answer 3) When I type git --help, I get a small guide with some Git commands for different situations

Answer 4)$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5) $ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 6) $ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7) $ git commit -m "Initial commit"
$ git status
On branch master
nothing to commit, working tree clean


Answer 8) $ git log
commit 02170747d9352e3a72b1620d8f78841b48e0c73e (HEAD -> master)
Author: Paola <pg748418@ohio.edu>
Date:   Fri May 15 23:08:36 2020 -0400

    Initial commit

Answer 9) $ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean


Answer 10) No changes I made online were reflected in my local copy. 

Answer 11) My push command gets rejected

Answer 12) The changes online were reflected in my local copy when I used git pull

Answer 13) 
.  ..

