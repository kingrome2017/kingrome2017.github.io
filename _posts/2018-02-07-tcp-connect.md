---
layout: post
title: git常用命令指南
categories: Blog
description: git常用命令指南
keywords: Blog, Emulator, TCP
---

## 〉生成SSH

* 使用git已两三月了，最常用的几个命令倒是很熟悉，用的比较少的命令很是记不清，要多多探索这些命令，首先要有个帐号为所欲为，接下来开始正题

```javascript
    $ ssh-keygen -t ras -C "email@xxx"
```
## 〉设置用户名
  
```javascript
    $ git config --global user.name "cc"
    $ git config --global user.email "cc@xx"
```

## 〉分支操作
```javascript
    /*查看分支*/
    git branch     //所有本地分支
    git branch -r  //所有远程分支
    git branch -a  //所有远程分支和本地分支

    /*创建分支*/ git branch branchName //留在当前分支
    git checkout -b branchName //创建并切换分支
    git branch --set-upstream-to=<remote>/branchName //建立本地分支与远程分支的追踪关系
    git branch --track branchName [remote branch] //新建一个分支，并与远程建立追踪关系 git checkout branchName //切到指定分支 /*分支合并*/ git pull origin branch //取回远程更新并与本地分支合并 git fetch origin branch //取回远程更新 git merge branch //合并指定分支到当前分支(产生提交记录) git rebase branch //合并指定分支到当前分支(不产生提交记录，比较适合有强迫症的) git cherry-pick commitId //将与commitId对应的提交合进当前分支
```


## 〉放弃暂存区修改
感谢以下的项目,排名不分先后
 ` 
    git checkout -- filename  //放弃暂存区修改（修改不在）
    git rm --cached filename  //放弃add（修改还在，但产生一条delete记录）
    git reset HEAD filename   //同上（没有delete记录）

    git stash     //暂时放弃未提交的修改
    git stash pop  //恢复
`


