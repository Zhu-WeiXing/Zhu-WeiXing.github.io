---
title: Git的配置与使用
cover: https://api.ixiaowai.cn/gqapi/gqapi.php
---

## git的配置

### 用户信息
配置个人的用户名和电子邮件地址
```
$ git config --global user.name "用户名"
$ git config --global user.email "电子邮件地址"
```

### 文本编辑器
设置Git默认使用的文本编辑器，一般可能会是Vi或者Vim。如果你有其他偏好，可以重新设置
```
$ git config --global core.editor 编辑器名
```

### 查看配置
要检查已有的配置信息，可以使用git config --list命令
```
$ git config --list 
```

## git的使用

### 在命令行上创建新的存储库
```
$ git init        #git初始化
$ git clone <repo>   # git克隆仓库   repo:远程仓库
$ git add .   #添加当前项目的所有文件
$ git status   #查看上次提交之后是否有修改 
$ git commit -m '提交信息'   #提交说明
$ git push    #本地仓库提交到远端仓库
```

### 从命令行上推送现有存储库
```
$ git remote add origin 仓库地址
$ git push -u origin master
```

