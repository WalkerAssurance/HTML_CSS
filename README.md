# HTML_CSS
html-l4-ex1

Mike@ASUS-VivoBook-X515EP MINGW64 ~ (main)
$ cd /d/intita/html_css

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css
$ git init
Initialized empty Git repository in D:/INTITA/HTML_CSS/.git/

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (master)
$ git add .

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css


Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (master)
$ git commit -m "added index.html, style.css"
[master (root-commit) 098093a] added index.html, style.css
 2 files changed, 111 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (master)
$ git status
On branch master
nothing to commit, working tree clean

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (master)
$ git branch
* master

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (master)
$ git remote add origin https://github.com/WalkerAssurance/HTML_CSS.git

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (master)
$ git branch -M main

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.97 KiB | 1.97 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/WalkerAssurance/HTML_CSS.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Mike@ASUS-VivoBook-X515EP MINGW64 /d/intita/html_css (main)
$ git log --all
commit 098093a721fd0866c3e29c926dec5e41e8c84d02 (HEAD -> main, origin/main)
Author: WalkerAssurance <mihailg.post@gmail.com>
Date:   Tue Nov 14 14:52:57 2023 +0200

    added index.html, style.css
