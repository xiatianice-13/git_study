基本操作

提交与修改

|**命令**|**说明**|
|------|------|
|[git add](https://www.runoob.com/git/git-add.html)|添加文件到暂存区|
|[git status](https://www.runoob.com/git/git-status.html)|查看仓库当前的状态，显示有变更的文件。|
|[git diff](https://www.runoob.com/git/git-diff.html)|比较文件的不同，即暂存区和工作区的差异。|
|[git commit](https://www.runoob.com/git/git-commit.html)|提交暂存区到本地仓库。|
|[git reset](https://www.runoob.com/git/git-reset.html)|回退版本。|
|[git rm](https://www.runoob.com/git/git-rm.html)|将文件从暂存区和工作区中删除。|
|[git mv](https://www.runoob.com/git/git-mv.html)|移动或重命名工作区文件。|
|git reset|回溯版本|

**提交日志**

|**命令**|**说明**|
|------|------|
|[git log](https://www.runoob.com/git/git-commit-history.html#git-log)|查看历史提交记录|
|[git blame <file>](https://www.runoob.com/git/git-commit-history.html#git-blame)|以列表形式查看指定文件的历史修改记录|

远程操作

git remote add origin url 连接远程仓库

如果输入错误 git remote rm origin

或者 git clone url 克隆远程仓库

|**命令**|**说明**|
|------|------|
|[git remote](https://www.runoob.com/git/git-remote.html)|远程仓库操作|
|[git fetch](https://www.runoob.com/git/git-fetch.html)|从远程获取代码库|
|[git pull](https://www.runoob.com/git/git-pull.html)|下载远程代码并合并|
|<a href="https://www.runoob.com/git/git-push.html">git push</a>|上传远程代码并合并|


-----
分支管理

创建分支

```
git branch name
```

查看所有远程分支

```
git branch -a 
git branch -d name //删除分支
```



切换分支

```
git checkout name 
```

查看当前分支

```
切换分支
git checkout name 
查看当前分支
git status 
```

合并分支

```
git merge name
```

git log --graph --pretty=oneline --abbrev-commit

![](image_1.c12ebd0f.png)

- ==建立本地分支和远程分支的关联，使用git branch --set-upstream branch-name origin/branch-name；==

-----
创建仓库

在文件夹右键选着git bash here

初始化

```
git init 
```

克隆仓库

```
git clone url 
```

编辑git配置

```
git config --list //查看配置
git config -e --global (所有仓库) //编辑git配置文件
```

