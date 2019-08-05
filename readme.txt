Git is a distributed version control system.
Git is free software.

=======================
git学习

设置账号
git config --global user.email "zjm122796@163.com"
git config --global user.name "zhaojiamin"

初始化一个Git仓库，使用git init命令。

添加文件到Git仓库，分两步：

使用命令git add <file>，注意，可反复多次使用，添加多个文件；
使用命令git commit -m <message>，完成。