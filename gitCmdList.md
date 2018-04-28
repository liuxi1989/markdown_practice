## 常用git 命令备份

1. 删除远程库dev分支
<pre>
git push origin ：dev 	//注意冒号前的空格
</pre>

2. 拉取远程库dev分支，并在本地创建dev分支，使其关联
<pre>
git checkout -b dev origin/dev		//如果失败，需要先执行git fetch
</pre>

3. 拉取远程分支dev,到本地分支dev1
<pre>
git fetch origin dev;dev1
</pre>