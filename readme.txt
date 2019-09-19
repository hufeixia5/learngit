Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git track changes.

git config --global user.name "username"         #输入git的用户名

git config --global user.email "email"           #输入Git对应的邮箱

git add readme.txt             #增加一个版本

git commit -m "append GPL"           #更新版本，-m后为修改的描述

git reflog      # 查看修改记录

git log --pretty=oneline            #--pretty=oneline为精简查看修改条目

git reset --hard d9afa              #回退到指定的位置

git reset --hard HEAD^              #HEAD^回退到上一版本HEAD^^回退到上两个版本，HEAD~100回退到上100个版本

git status                          #查看当前状态
