# learn git commands
    git commit -m "frist commit"


忘记添加文件index.js,你可以执行下面的命令

    git add index.js
    git commit --amend // 修改最后一条commit信息

获取master分支最新的commit和本地的仓库进行合并

    git pull origin master 

设置新的远程仓库url

    git remote set-url origin <url>

指定分支上传拉取 不用每次指定操作的分支
    
    git branch --set-upstream-to=origin/test test


# git tree
![git tree](https://github.com/xiaokyo/git-study/blob/master/git_tree.jpg)
