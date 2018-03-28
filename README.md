# Git-commands
some commands for Git Bash

$ cd C:/Android/git-repositories
$ mkdir new_repository_1           创建新的目录
$ cd new_repository_1              进入到创建的目录
$ git clone http://github.com/hayabusa0523/Git-commands.git 导入共享端repo

你可以提出更改（把它们添加到暂存区），使用如下命令：
git add <filename>
git add *
这是 git 基本工作流程的第一步；使用如下命令以实际提交改动：
git commit -m "代码提交信息"
现在，你的改动已经提交到了 HEAD，但是还没到你的远端仓库
$ git add README.md
$ git commit -m "first commit"
$ git push origin master
111111111111111111111111
222222222222222222222222
