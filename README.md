# Simple-Git-Tutorial
**Steps to be followed**

* fork repository (No need if you can clone main repo)
* git clone `<link>`
* git branch `<branch name>`
* git checkout `<branch name>` 
* move into directory
* make neccessary changes and add necessary files
* git add .
* git commit -m `<message about changes>`
* git push origin master
* make a pull request !



**How to squash commits**
* git rebase -i HEAD~4 ( to squash 4 commits )
* change pick to squash in the text editor
* exit the editor
* git push origin branch-name --force ( Use when already pushed commits )



