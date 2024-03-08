# belajarGIT

Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT

SAVIO@Savio-PC MINGW64 ~
$ git config --global user.email "saviopalendeng506@gamil.com"

SAVIO@Savio-PC MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/HP/.git/

SAVIO@Savio-PC MINGW64 ~ (master)
$ git config --global user.email "saviopalendeng506@gmail.com"

SAVIO@Savio-PC MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/HP/.git/

SAVIO@Savio-PC MINGW64 ~ (master)
$ cd GiT
bash: cd: GiT: No such file or directory

SAVIO@Savio-PC MINGW64 ~ (master)
$ cd GiT
bash: cd: GiT: No such file or directory

SAVIO@Savio-PC MINGW64 ~ (master)
$ cd Users
bash: cd: Users: No such file or directory

SAVIO@Savio-PC MINGW64 ~ (master)
$ pwd
/c/Users/HP

SAVIO@Savio-PC MINGW64 ~ (master)
$ cd GiT
bash: cd: GiT: No such file or directory

SAVIO@Savio-PC MINGW64 ~ (master)
$ git clone <https://github.com/AbangSakata/belajarGIT.git>
bash: syntax error near unexpected token `newline'

SAVIO@Savio-PC MINGW64 ~ (master)
$ git clone https://github.com/AbangSakata/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

SAVIO@Savio-PC MINGW64 ~ (master)
$ ls
 AppData/             Favorites/               NTUSER.DAT                                                                                     Pictures/      'Start Menu'@      ntuser.ini
'Application Data'@   IntelGraphicsProfiles/   NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TM.blf                                        PrintHood@      Templates@
 Contacts/            Links/                   NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000001.regtrans-ms   Recent@         Videos/
 Cookies@            'Local Settings'@         NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000002.regtrans-ms  'Saved Games'/   belajarGIT/
 Documents/           Music/                   NetHood@                                                                                       Searches/       ntuser.dat.LOG1
 Downloads/          'My Documents'@           OneDrive/                                                                                      SendTo@         ntuser.dat.LOG2

SAVIO@Savio-PC MINGW64 ~ (master)
$ cd belajarGIT

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch
* main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch Tugas-git

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch
  Tugas-git
* main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch Tugas-html

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch Tugas-css

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch Tugas-js

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch Tugas-midProject

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch Tugas-php

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch Tugas-finalProject

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-git
fatal: a branch named 'Tugas-git' already exists

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt
fatal: pathspec 'Tugas-Git.txt' did not match any files

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ touch Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ rm -r Tugas-html
rm: cannot remove 'Tugas-html': No such file or directory

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git ab15266] Menambahkan file Tugas-git.txt
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt
 create mode 100644 Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git merge Tugas-git
Updating 7d47892..ab15266
Fast-forward
 Tugas-git.txt  | 0
 Tugas-html.txt | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt
 create mode 100644 Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-html
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-git.txt
Please commit your changes or stash them before you switch branches.
Aborting

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Menulis pada file Tugas-git.txt"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-git.txt
        deleted:    Tugas-html.txt

no changes added to commit (use "git add" and/or "git commit -a")

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-html
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-git.txt
Please commit your changes or stash them before you switch branches.
Aborting

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git rm Tugas-html.txt
rm 'Tugas-html.txt'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit "Menghapus file Tugas-html.txt"
error: pathspec 'Menghapus file Tugas-html.txt' did not match any file(s) known to git

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Menghapus file Tugas-html.txt"
[main 04e0637] Menghapus file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-git.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Memodifikasi file Tugas-git.txt"
[main 5655185] Memodifikasi file Tugas-git.txt
 1 file changed, 1 insertion(+)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html ff34fa5] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git merge Tugas-html
error: Empty commit message.
Not committing merge; use 'git commit' to complete the merge.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main|MERGING)
$ git commit -m "Menggabungkan Branch Tugas-html"
[main bace765] Menggabungkan Branch Tugas-html

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas.html
fatal: pathspec 'Tugas.html' did not match any files

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 5 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-html.txt

no changes added to commit (use "git add" and/or "git commit -a")

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-html.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Memodifikasi file Tugas-html.txt"
[main 58d60da] Memodifikasi file Tugas-html.txt
 1 file changed, 1 insertion(+)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 2 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (15/15), 1.29 KiB | 120.00 KiB/s, done.
Total 15 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (6/6), done.
To https://github.com/AbangSakata/belajarGIT.git
   7d47892..58d60da  main -> main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 1b433f2] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-css)
$ git merge Tugas-css
Already up to date.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git merge Tugas-css
Merge made by the 'ort' strategy.
 Tugas-css.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-css.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Memodifikasi file Tugas-css.txt"
[main c67e0e6] Memodifikasi file Tugas-css.txt
 1 file changed, 1 insertion(+)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 826 bytes | 413.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/AbangSakata/belajarGIT.git
   58d60da..c67e0e6  main -> main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js c02a14c] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git merge Tugas-js
Merge made by the 'ort' strategy.
 Tugas-js.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-js.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Memodifikasi file Tugas-js.txt"
[main a5b5c72] Memodifikasi file Tugas-js.txt
 1 file changed, 1 insertion(+)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 761 bytes | 380.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/AbangSakata/belajarGIT.git
   c67e0e6..a5b5c72  main -> main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 6d7e706] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git merge Tugas-midProject
Merge made by the 'ort' strategy.
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-midProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Memodifikasi file Tugas-midProject.txt"
[main 51b5d67] Memodifikasi file Tugas-midProject.txt
 1 file changed, 1 insertion(+)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 796 bytes | 796.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/AbangSakata/belajarGIT.git
   a5b5c72..51b5d67  main -> main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php beb8767] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git merge Tugas-php
Merge made by the 'ort' strategy.
 Tugas-php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-php.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Memodifikasi file Tugas-php.txt"
[main fe29692] Memodifikasi file Tugas-php.txt
 1 file changed, 1 insertion(+)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 767 bytes | 383.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/AbangSakata/belajarGIT.git
   51b5d67..fe29692  main -> main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 7b26633] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git merge Tugas-finalProject
Merge made by the 'ort' strategy.
 Tugas-finalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-finalProject
fatal: pathspec 'Tugas-finalProject' did not match any files

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git add Tugas-finalProject.txt

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git commit -m "Memodifikasi file Tugas-finalProject,txt"
[main f7c8c95] Memodifikasi file Tugas-finalProject,txt
 1 file changed, 1 insertion(+)

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 799 bytes | 399.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/AbangSakata/belajarGIT.git
   fe29692..f7c8c95  main -> main

SAVIO@Savio-PC MINGW64 ~/belajarGIT (main)
$

