# 本项目用于git的练习

## 配置账号信息

```
git config --global user.name 胡思俊 # 设置全局签名

git config --global user.eamil 2655758030@qq.com # 设置全局邮箱

git config --list # 查看配置信息
```

## 新建仓库

```
git init # 在本地文件夹中初始化一个git仓库

git status # 查看仓库状态

git add [file1] [file2] ... # 将指定文件添加到暂存区，.或*代表全部添加

git commit -m 'message' # 提交到本地仓库，message为提交信息

git remote add origin [origin] # 添加源，可以理解为远程仓库的位置

git push -u origin master # 将本地仓库推送到远程仓库， -u代表设置默认跟踪分支
```

## 克隆

```
git clone https://github.com/HuTuTu666/gitPractice.git # 克隆

git clone https://github.com/HuTuTu666/gitPractice.git myPro # 克隆仓库到指定文件夹
```

## 分支

```
git branch # 列出本地分支

git branch -r # 列出远端分支

git branch -a# 列出所有分支

git branch [branch] # 新建branch分支

git --set-upstream [branch] origin [branch] # 将本地branch分支与远端branch分支建立连接

git branch -m [old] [new] # 将old分支重命名为new分支

git branch -d [branch] # 删除branch分支

git branch -D [branch] # 强制删除branch分支

git checkout [branch] # 切换到branch分支

git checkout -b [branch] # 新建branch分支并切换到branch分支

git checkout -b test dev # 基于dev分支新建test分支，并切换
```

## 分支合并

```
当在不同分支对同一个文件的同一位置进行不同修改时，合并会出现冲突
git merge [branch] # 将所在分支与branch分支合并，当前分支落后于branch分支才能合并
```
