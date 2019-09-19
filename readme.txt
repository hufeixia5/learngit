Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git track changes of files.
My stupid boss still prefers SVN.
##############################################################################
git config --global user.name "username"         #输入git的用户名

git config --global user.email "email"           #输入Git对应的邮箱

#git分两步，第一步add放入暂存区，准备提交，第二步为提使用commit

git add readme.txt             #增加一个版本

git commit -m "append GPL"           #更新版本，-m后为修改的描述

git reflog      # 查看修改记录

git log --pretty=oneline            #--pretty=oneline为精简查看修改条目

git reset --hard d9afa              #回退到指定的位置

git reset --hard HEAD^              #HEAD^回退到上一版本HEAD^^回退到上两个版本，HEAD~100回退到上100个版本

git status                          #查看当前状态

git checkout -- readme.txt          #将文件在工作区的修改全部撤销，

git reset HEAD <file>               #将暂存区的文件会到工作区

git rm test.txt                     #命令git rm用于删除一个文件。如果一个文件已经被提交到版本库，那么你永远不用担心误删，但是要小心，你只能恢复文件到最新版本，你会丢失最近一次提交后你修改的内容。

test.txt（2行文字） ——add——commit——rm——checkout——这样删除了你会获得test.txt（2行文字）

test.txt （2行文字）——add——commit——修改增加test.txt的内容（3行文字）——rm——checkout——这样删除了你会获得test.txt（2行文字）

git push -u origin master           #由于远程库是空的，我们第一次推送master分支时，加上了-u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。

git remote add origin git@server-name:path/repo-name.git             #关联一个远程库 
git remote add origin git@github.com:hufeixia5/learngit.git    
##############################################################################










