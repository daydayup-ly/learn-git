# git 基本命令

## 在本地创建一个repository
mkdir aproject
cd aproject/
git init  

## 进入本地repository
cd 对应文件名

## 新建branch
git branch newbranch
git checkout -b new-branch existing-branch #This creates a new branch new-branch, based on existing-branch.

## 切换到新建branch 中
git checkout newbranch
git checkout -b newbranch   创建branch 并切换

## 查看状态
git status 

## 查看branch
git branch  会显示所有branch 名 带*的表示所在branch



## 将修改 stage 
git add 修改了的文件名
git add --all / (git add -a)  将所有修改stage

## 提交修改
git commit -m '添加 a.html' #提交描述(git commit -am 表示先add 再commit)

## 查看 以往提交
git log (git log --oneline)

## 把本地branch push 到github上
git push origin newbransh 

## merge
git merge newbranch #把newbranch 合并到主分支 (在主分支下操作)

## 基本流程
git clone ->  git branch -> make changes -> git add -> git commit -> git push ->pull requst -> git merge

