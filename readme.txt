this is a git.

F2 可以退出编辑状态,进入命令行.然后我们按照一步步操作可以走出来.

git add
git log
git reflog
git reset --hard 

git tracks changes

remember 3 status:
工作区,暂存区,仓库


git branch dev
git checkout dev

create a new branch is quick and simple

qucik and simple

use git merge --no-ff -m "xx" dev

<<<<<<< HEAD

git stash is useful
=======
use git stash

git branch -D dev/feature

origin 是远程仓库的名称

>>>>>>> dev


多人协作:
创建与远程库对应的分支:
git checkout -b dev origin/dev

建立与远程库分支的关联:
git branch --set-upstream-to=origin/dev dev

git log

git reflog















