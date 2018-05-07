…or create a new repository on the command line

echo "# p1803" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/wyz522588/p1803.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/wyz522588/p1803.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.



```
git add .
git commit -m 'ffff'
git push -u origin master

```
