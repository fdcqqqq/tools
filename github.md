# git工具与github使用

### git仓库的配置

git config --global user.name xxx

git congig --global user.email xxx

cat .gitconfig 查看配置文件

gitconfig --list 查看配置

### git 操作

git init 初始化git仓库

git status 查看git仓库状态

git add *将工作内容记录到暂存区

git rm --cached xxx 取消暂存区添加

git commit -m "init add"将工作区所有文件提交到仓库

touch .gitignore (将需要隐藏的文件写入)将不想提交的文件隐藏提交

git add .gitignore xxx

git log 查看日志

git rm xxx 删除文件

git mv xxx path 移动文件

### branch分支操作

git branch xxx 创建分支

git checkout 分支名字    切换分支

git checkout -b xxx 创建并切换分支

git merge xxx 合并分支

git branch -d 删除分支

### github使用

git pull / git fetch把远程github文件拉下来

git remote rm xxx 删除远程名字

git push 将文件上传

生成公钥:

ssh-keygen

cd .ssh

cat id_ras.pub 获取公钥







