Git is a version control systerm.
Git is a free software.
Git is a distributed version control sysytem.
Git is a free software under the GPL.

Git has a mutable index called stage.
Git tracks changes of files.

…or create a new repository on the command line

echo "# first" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/wzijing/first.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/wzijing/first.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


