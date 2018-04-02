Git is a version control system.
Git is a free software.
git init 将当前目录变成仓库
git 分为工作区和暂存区
	工作区为当前目录
	暂存区在隐藏文件夹.git里
git add filename :见文件提交到暂存区
git commit -m "这里写注释" : 提交到当前分支
git status : 查看当前状态
git diff filename : 查看文件修改了哪里
git log 显示日志
git log --pretty=oneline ：以一行显示日志
git reset --hard HEAD^ :版本回滚 回到上一个版本
git reset --hard HEAD^^ :版本回滚 回到上两个版本
git reset --hard HEAD~100 :版本回滚 回到上100个版本
git reflog : 获取版本号
git reset --hard 版本号 ：回到版本号的版本