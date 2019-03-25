# learn git commands
    git commit -m "frist commit"


忘记添加文件index.js,你可以执行下面的命令


    git add index.js
    git commit --amend


这样就只有一个提交信息了

    git pull origin master

获取master分支最新的commit和本地的仓库进行合并

<<<<<<< HEAD
![git tree](www)
=======
![git tree](https://github.com/xiaokyo/git-study/blob/master/git_tree.jpg)
>>>>>>> 104fdf06e7a461609ada4855cbe9a955c48953f5
