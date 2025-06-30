
git config –global user.email “邮箱地址”  配置git全局信息用于记录每次提交的来源
git config –global user.name “用户名”


git init 初始化本地库


git rm --cached <file>       从暂存区删除文件

提交上传：
git add <file>   添加文件到暂存区
git commit -m “版本说明”   提交文件到本地库
git commit --amend -m “版本说明”   修改最近一次的提交说明


git log 查看详细版本信息
git reflog 查看版本信息部分信息


git status 查看状态
git diff      查看文件改动的内容


git reset --hard <版本号>版本代码穿梭


git branch -v 查看分支
git branch <分支名> 创建分支
git checkout <分支名> 切换分支
git merge <要合并的分支名>  合并分支


git remove -v 查看别名
git remove add <别名>  <URL> 创建别名

git fetch                             拉取最新版本至本地库不自动合并
git pull <别名> <分支名> 拉取最新版本至本地库并自动合并
git push <远程主机名> <本地分支名> 推送至远程库

git reset --hard HEAD^    回退至上一版本
git reset --soft HEAD^     取消commit操作，但是不丢弃修改

git reset HEAD <文件名> 将文件从暂存区放回到工作区
git checkout --<文件名>  撤销文件在工作区的修改






