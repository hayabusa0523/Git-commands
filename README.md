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

$ git status 查看是否有修改而未提交文件
$ git diff README.md 查看修改了什么
$ git log 查看历史 （按q退出） 或者$ git log --pretty=oneline
$ cat README.md 查看文本内容
$ git reset --hard HEAD~回退版本数
$ git reset --hard 版本号
$ git reflog 获取版本号

shift+insert =复制粘贴
shift+enter =全屏
ctrl+ +/-/0 =放大，缩小或回复
111111111111111111111111
222222222222222222222222
333333333333333333333333
444444444444444444444444