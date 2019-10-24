## git test
+ create branch-lhb

### 常用命令
+ `git status` 查看当前仓库状态, 拿不准的时候多用这个
+ 本地信息
  + 查看用户配置 `git config --global --list`
  + 查看当前仓库配置信息 `git config --local --list`
  + 查看用户名 `git config user.name` 修改 `git config --global user.name 'xxx'`
  + 查看邮箱地址 `git config user.email` 修改 `git config --global user.email 'xxx'`
+ 本地分支管理
  + 查看远程分支 `git branch -r`
  + 创建新的分支, 但不会切换过去 `git branch xxx`
  + 创建新的分支并切换过去 `git checkout -b xxx`
  + 查看各个分支最后提交信息 `git branch -v`
  + 切换到某个分支 `git checkout xxx`
  + 删除某个分支 `git br -d xxx`
  + 将某个分支合并到当前分支上 `git merge xxx`
+ 远程分支管理
  + 抓取远程所有分支更新并合并到本地 `git pull`
  + push 分支 `git push`
+ 远程仓库管理
  + 查看远程服务器地址和仓库名称 `git remote -v`
  + 查看远程服务器状态 `git remote show origin`
  + 设置远程仓库地址 `git remote set-url origin xxxurl`
+ 其他
  + 命令简写
    + `git config --global alias.co checkout` 命令缩写
    + `git config --global alias.cm commit` 命令缩写
    + `git config --global alias.br branch` 命令缩写
    + test
