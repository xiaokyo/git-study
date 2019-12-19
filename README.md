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

回退版本强制提交

    git reset --hard e377f60e28c8b84158
    git push -f origin dev

获取单次提交的commit修改

    git log --online -3
    git cherry-pick 2555c6e
    // 有冲突解决后
    git cherry-pick --continue
    // or
    git cherry-pick 2555c6e -n
    // 不自动提交

使用rebase来达到每次提交你的提交都在最上面

    git pull origin dev --rebase

合并commit,<commitId>想合并后紧跟的commit

    git rebase -i <commitId>

# git tree
![git tree](https://github.com/xiaokyo/git-study/blob/master/git_tree.jpg)
