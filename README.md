# a-new-hello-world
(do this again and again, review often, and you will remeber better)

# workflow of git on GitHub （5 steps）
## 1. create a new repository
## 2. create a new branch
## 3. make a commit （change）
## 4. open a pull request & maybe then maybe makeing more other commits
## 5. merge pull rerquest


# workflow of git with new branch （For Comapany）on command-line (7 steps)
## git branch newBranch2  （建立一个新分支）
## git checkout newBranch2   （转到新的分支）
## git status                   （make chanegs）
## 1. git add -A                  （add change 到 staging area）
## git diff           （检查一下change是否对）
## git reset                       （如果发现change不对，撤回修改，不然就要再次push或者merge一次了）
## 2. git commit -m 'a new change'  （commit changes）
## 3. git push -u origin newBranch2  （push new branch ）
## git branch -a                 
## 4. git checkout master             （转到master,准备进行merge）
## 5. git pull origin master           （准备往master进行一切任何的commit之前，都要先进行pull操作）
## 6. git merge newBranch                （merge到master）
## 7. git push origin master              （push到master）
## git branch -d newBranch2             （删除local branch）
## git push origin --delete newBranch2    （删除remote branch）


# workflow of git without new branch（For Individual） on command-line (4 steps)
## 1. git add -A
## 2. git commit -m ""
## 3. git pull origin master
## 4. git push origin master
