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

class@LAPTOP-AU6JMOMH MINGW64 ~ (master)
$ cd Documents

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents (master)
$ git clone https://github.com/clssty/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents (master)
$ cd belajarGIT

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git 225f659] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 277fede..225f659
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 149.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/clssty/belajarGIT.git
   277fede..225f659  main -> main

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 1e6b22a] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating 225f659..1e6b22a
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 332 bytes | 110.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/clssty/belajarGIT.git
   225f659..1e6b22a  main -> main

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-git.css

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css e74c057] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 1e6b22a..e74c057
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 357 bytes | 178.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-git.js

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt"
[Tugas-js afd00b0] Menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating e74c057..afd00b0
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 291 bytes | 145.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clssty/belajarGIT.git
   e74c057..afd00b0  main -> main
class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject be6da8b] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating afd00b0..be6da8b
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes | 156.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clssty/belajarGIT.git
   afd00b0..be6da8b  main -> main

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-git.php

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 9f2ae86] Menambahkan Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating be6da8b..9f2ae86
Fast-forward
 Tugas-php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 287 bytes | 287.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clssty/belajarGIT.git
   be6da8b..9f2ae86  main -> main

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject 2476fac] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 9f2ae86..2476fac
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

class@LAPTOP-AU6JMOMH MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clssty/belajarGIT.git
   9f2ae86..2476fac  main -> main
