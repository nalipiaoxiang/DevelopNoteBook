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
ssh-keygen -t rsa -C "www.chenpengchong@gmail.com"
查看秘钥
cat ~/.ssh/id_rsa.pub
在git上添加秘钥
```

```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC5Ab7xLr8Q+FTpzHcoOKYQRAT/qNLy40EyY4kWc5WUSSNw050rxhVK5rMGd6BSY6P8xGFAVlUMHpa8fm3mSxs0d4kKKaiQSLcJcUSkDLi8+mU3kXhS2xfI06TFtwOPNrHu1A8T20Get9pKlDXOkii2ZUn+jh4bZ9kxlD6E3t8alsY1keStoeArnxcIr8gqG3czIQaTQXCEPb+im74MfVaP38/4iT12jKTXuV8YUQEB/EdMoPQpqjPYO5Jju8t6qEnc22769Gh4RyQhJFhLyODM2VT9Bjp4lYN7SVj8ohTKlqpOsnFaOqb7nA+rDOnMMT+ysHF/Iky26NUZaGolBj3/bVW/Scrb9Az9myQgHS2cf4uuC+jt9Cw6FQ7yeteOIzF2Kta2u7w/mWFBJgNKUbB857vbUSk8MtwzSYj9NBVnN5LUZe0xFaf0XN/6uGofL8oGqPVAtfv0ddq4x9aRC5wH+Xmp9VnKFByMbXeq/uEC3ZPwQ6kWzyrKcTAamy7m230= www.chenpengchong@gmail.com

```

```
删除 远程地址
git remote rm origin
```

