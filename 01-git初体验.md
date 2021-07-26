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
git reset --hard 版本代码
