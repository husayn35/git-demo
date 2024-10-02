
NEXT NOUT@Husayn MINGW32 ~
$ ^[[200~echo "# git-demo" >> README.md
git branch -M main
git remote add origin https://github.com/husayn35/git-demo.git
git push -u origin mainbash: $'\E[200~echo': command not found

NEXT NOUT@Husayn MINGW32 ~
$ git init
Initialized empty Git repository in C:/Users/NEXT NOUT/.git/

NEXT NOUT@Husayn MINGW32 ~ (master)
$ git add README.md

NEXT NOUT@Husayn MINGW32 ~ (master)
$ git commit -m "first commit"
[master (root-commit) 6df5006] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

NEXT NOUT@Husayn MINGW32 ~ (master)
$ git branch -M main

NEXT NOUT@Husayn MINGW32 ~ (main)
$ git remote add origin https://github.com/husayn35/git-demo.git

NEXT NOUT@Husayn MINGW32 ~ (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 214 bytes | 214.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/husayn35/git-demo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

NEXT NOUT@Husayn MINGW32 ~ (main)
$
