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
