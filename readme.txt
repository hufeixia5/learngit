Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git track changes of files.
My stupid boss still prefers SVN.
##############################################################################
git config --global user.name "username"         #����git���û���

git config --global user.email "email"           #����Git��Ӧ������

#git����������һ��add�����ݴ�����׼���ύ���ڶ���Ϊ��ʹ��commit

git add readme.txt             #����һ���汾

git commit -m "append GPL"           #���°汾��-m��Ϊ�޸ĵ�����

git reflog      # �鿴�޸ļ�¼

git log --pretty=oneline            #--pretty=onelineΪ����鿴�޸���Ŀ

git reset --hard d9afa              #���˵�ָ����λ��

git reset --hard HEAD^              #HEAD^���˵���һ�汾HEAD^^���˵��������汾��HEAD~100���˵���100���汾

git status                          #�鿴��ǰ״̬

git checkout -- readme.txt          #���ļ��ڹ��������޸�ȫ��������

git reset HEAD <file>               #���ݴ������ļ��ᵽ������

git rm test.txt                     #����git rm����ɾ��һ���ļ������һ���ļ��Ѿ����ύ���汾�⣬��ô����Զ���õ�����ɾ������ҪС�ģ���ֻ�ָܻ��ļ������°汾����ᶪʧ���һ���ύ�����޸ĵ����ݡ�

test.txt��2�����֣� ����add����commit����rm����checkout��������ɾ���������test.txt��2�����֣�

test.txt ��2�����֣�����add����commit�����޸�����test.txt�����ݣ�3�����֣�����rm����checkout��������ɾ���������test.txt��2�����֣�

git push -u origin master           #����Զ�̿��ǿյģ����ǵ�һ������master��֧ʱ��������-u������Git������ѱ��ص�master��֧�������͵�Զ���µ�master��֧������ѱ��ص�master��֧��Զ�̵�master��֧�������������Ժ�����ͻ�����ȡʱ�Ϳ��Լ����

git remote add origin git@server-name:path/repo-name.git             #����һ��Զ�̿� 
git remote add origin git@github.com:hufeixia5/learngit.git    
##############################################################################










