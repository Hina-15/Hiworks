# Hina15

Hiworks是一个受长期支持的私人仓库

仓库中的内容大多是一些仓库所有人在平时学习时的成果与描述

~~仓库中的文件可能随时修改，不过仍具有参考意义~~

#### 2023/11/24

修改了连不上github的bug
~~其实是找错了文件夹~~

23:22
找对了文件夹也没连上

#### 2023/11/25

新增了 ~/.ssh 内一个config文件、内容如下：

```
Host github.com
User git
Hostname ssh.github.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa
Port 443

Host gitlab.com
Hostname altssh.gitlab.com
User git
Port 443
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa

```

运行    `ssh -T git@github.com`

#### 0:36
修剪远程分支 `git remote prune origin`