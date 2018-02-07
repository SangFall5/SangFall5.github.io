# SSH

## 1.创建ssh key

`$ ssh-keygen -t rsa -C "your_email@youremail.com"`

> ex:$ ssh-keygen -t rsa -C "123456@qq.com"

## 2.验证SSH是否成功

`$ ssh -T git@github.com`

## 3.设置username和email

`$ git config --global user.name "your name"
$ git config --global user.email "your_email@youremail.com"`

> your name：GitHub用户名
> your_email：GitHub注册邮箱

# 本地文件上传到GitHub

## 1.建立git仓库

`git init`

## 2.将项目的所有文件添加到仓库中

`git add .`

## 3.将add的文件commit到仓库，并添加注释

`git commit -m "注释语句"`

## 4.去github上创建自己的Repository

## 5.将本地的仓库关联到github上

`git remote add origin https://github.com/SangFall5/test.git`

## 6.上传github之前，要先pull一下

`git pull origin master`

## 7.上传代码到github远程仓库

`git push -u origin master`

# 完



