# Git使用

代码提交git

```
http
git init
git add .
git add README.md
git commit -m "first commit"
git remote add origin https://xxx.git
git push -u origin master

ssh
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:xxx.git
git push -u origin master
```



```
项目下面生产秘钥
ssh-keygen -t rsa -C "xxx@gmail.com"
查看秘钥
cat ~/.ssh/id_rsa.pub
在git上添加秘钥
```

```
ssh-rsa 

```

```
删除 远程地址
git remote rm origin
```

