一、下载安装
二、
设置用户签名
git config user.name xxx
git config user.email xxx
初始化本地库
git init

让本地库配置文件可见,并关闭访达
defaults write com.apple.finder AppleShowAllFiles TRUE
killall Finder  

----------版本-----------

查看本地状态
git status

添加到暂存区
git add 

从暂存区删除
git rm --crash 

提交代码
git commit -m'版本信息' 文件名

查看提交日志
git reflog
git log

版本穿梭
git reset --hard commit_id

版本的删除
git rebase -i commit_id_n-1  此处要删除前一个版本的id。(有问题？这到底是啥)

----------分支------------
查看当前分支的版本
git branch -v 

创建新的分支
git branch branchname
（疑问：创建的新分支，怎么搞过来原分支的代码？）
