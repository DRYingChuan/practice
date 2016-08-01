# practice
git学习练习库

cd 跳转位置
用法
例如 我当前位置在c盘
如果想跳转到 e盘的 test 文件夹下
命令如下 cd e:test

pwd 显示当前所在位置

ls -ah 显示当前位置所有文件

git init  创建当前位置为版本库

git add <file> 添加文件到版本库暂存区

git commit 提交文件到版本库

git commit -m "<提交说明>"

git status 显示版本库是否有已修改但是未提交的文件（告诉我们版本库是否有文件修改）

git diff <file> 显示文件具体修改情况（告诉我们文件修改情况）

git log 显示文件的修改历史(查看提交历史，以便确定要回退到哪个版本)

git log --pretty=oneline 简化历史记录显示

git reset 回退文件版本

首先，Git必须知道当前版本是哪个版本，在Git中，用HEAD表示当前版本，上一个版本就是HEAD^，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100。
HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id。

git reflog 显示版本id,以便于确认版本需要回到那个版本

git checkout -- file 撤销工作区的修改

git reset HEAD <file> 回退提交到暂停区的文件

git diff HEAD -- <file> 命令可以查看工作区和版本库里面最新版本的区别：

rm <filt>  删除工作区的文件

git rm <file>  删除暂停区的文件（删除版本库的文件只需要提交就行 git commit）

创建SSH Key
$ ssh-keygen -t rsa -C "email"

远程提交代码

git pull 




