# latihan3

IHSAN@DESKTOP-64KN2SL MINGW64 ~ (master)
$ pwd
/c/Users/IHSAN

IHSAN@DESKTOP-64KN2SL MINGW64 ~ (master)
$ mkdir lab_pemrograman

IHSAN@DESKTOP-64KN2SL MINGW64 ~ (master)
$ cd lab_pemrograman/

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman (master)
$ mkdir latihan1

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman (master)
$ cd latihan1/

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git init
Initialized empty Git repository in C:/Users/IHSAN/lab_pemrograman/latihan1/.git/

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ echo "#latihan1" >> README.md

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ ls -l
total 1
-rw-r--r-- 1 IHSAN 197121 10 Oct 14 15:38 README.md

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git commit -m "ihsan hadimulya"
[master (root-commit) 59064ec] ihsan hadimulya
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git config --global user.name "SANEXP04"

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git config --global user.email "rendermn753@gmail.com"

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git remote add origin https://github.com/SANEXP04/latihan3.git

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 230 bytes | 230.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/SANEXP04/latihan3/pull/new/master
remote:
To https://github.com/SANEXP04/latihan3.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git clone https://github.com/SANEXP04/latihan3.git
Cloning into 'latihan3'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

IHSAN@DESKTOP-64KN2SL MINGW64 ~/lab_pemrograman/latihan1 (master)
$
![Screenshot (1)](https://user-images.githubusercontent.com/115678077/195808213-000d5364-e48d-496d-9598-9bf0e6b9aba9.png)
![Screenshot (2)](https://user-images.githubusercontent.com/115678077/195808224-ab08660d-e566-4873-b1fd-c62aadce1c1f.png)
