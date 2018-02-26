# SSH

## 1.创建ssh key

```bash
$ ssh-keygen -t rsa -C "your_email@youremail.com"
```

> ex：$ ssh-keygen -t rsa -C "123456@qq.com"

## 2.验证SSH是否成功

```bash
$ ssh -T git@github.com
```

## 3.设置username和email

```jsx
$ git config --global user.name "your name"
$ git config --global user.email "your_email@youremail.com"
```

> - your name：GitHub用户名
> - your_email：GitHub注册邮箱

# 本地文件上传到GitHub

## 1.建立git仓库

```bash
git init
```

## 2.将项目的所有文件添加到仓库中

```bash
git add .
```

## 3.将add的文件commit到仓库，并添加注释

```bash
git commit -m "注释语句"
```

## 4.去github上创建自己的Repository

## 5.将本地的仓库关联到github上

```bash
git remote add origin https://github.com/SangFall5/test.git
```

## 6.上传github之前，要先pull一下

```bash
git pull origin master
```

## 7.上传代码到github远程仓库

```bash
git push -u origin master
```

# 完



