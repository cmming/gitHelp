## 第一次提交
### 设置远端地址
https://github.com/cmming/gitHelp.git

添加远程仓库
git remote add origin https://github.com/cmming/gitHelp.git

git ->setting ->远端


### 添加文件 
    git add .  //添加所有文件

### 提交 
    git commit -m "提交测试"

### 推送
    git push --all(推送所有分支)
    git push -u origin master (本地的master分支推送到origin主机的master分支)


### 版本功能

    git log  //看所有版本
    git reset --hard 7ebbee1fa4a2a681fd336b34b01170f2490b732f  //切换版本  (切换版本之前千万要先提交)

### 分支学习

    git branch  //查看所有版本

    git branch newBranch    //创建分支
    git checkout newBranch  //切换分支