"# upload-tutorial" 

https:
https://github.com/spyspy/upload-tutorial.git

SSH:
git@github.com:spyspy/upload-tutorial.git

=======================================================

…or create a new repository on the command line

echo "# upload-tutorial" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/spyspy/upload-tutorial.git

git push -u origin master

=======================================================

…or push an existing repository from the command line

git remote add origin https://github.com/spyspy/upload-tutorial.git

git push -u origin master

=======================================================

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

=======================================================

Dowoload:

git remote add origin https://github.com/spyspy/upload-tutorial.git

git pull

=======================================================

Synchronized Remote to Local:

git fetch origin 來同步遠端伺服器上的資料到本地 (還需要 git merge orgin 然後就等於 git pull orgin) 

git remote  查詢remote是誰

git remote -v 查詢有哪些remote?

git pull (等於 fetch + merge)

=======================================================
