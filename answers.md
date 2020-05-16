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
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 8) $ git log
commit ef7d9aa60cfd23954410f7415a462b7509399fd0 (HEAD -> master)
Author: Paola <pg748418@ohio.edu>
Date:   Fri May 15 15:36:13 2020 -0400

    Initial commit

Answer 9) $ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 10) No changes I made online were reflected in my local copy. 

Answer 11) My push command gets rejected

Answer 12) The changes online were reflected in my local copy when I used git pull

Answer 13) 
$ ls
answers.md  git-lab-2  README.md
