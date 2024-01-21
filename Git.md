### Git

用Git上传项目到github

（一）主要部分：

`cd d:`

`cd Git/projects/<repo name>/` (进入本地仓库目录)

`ls -a` (确认当前仓库是否为github仓库)

`git add .`

`git commit -m "描述你的更改"`

`git push origin main`

（二）常见问题：

`git pull origin <branch_name>` 将远处仓库与本地同步

`git push -u origin <branch_name>` 如果是第一次推送需要添加-u

`git pull origin main --allow-unrelated-histories` 强制合并不相关的历史记录

When I use `git push origin main`

ssh: connect to host github.com port 22: Connection timed out
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.

[ssh git clone](https://gist.github.com/Tamal/1cc77f88ef3e900aeae65f0e5e504794)
