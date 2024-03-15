### Latex

1. 微分算子d可通过`\rm{d}`或`\text{d}`将斜体变为正体。
2. 向量的模长符号是`\left \|   \right \|`.

### A Virtual Environment

1. Linux: virtual box | kvm
2. Windows: VMware player | windows virtual PC
3. MacOS: QEMU | parallels

### Related Websites

[Git官方教程](https://git-scm.com/book/en/v2)

[Git分布式管理](https://www.educoder.net/paths/cgknh4of)

[联邦学习](https://zhuanlan.zhihu.com/p/79284686)

[神奇网站](https://www.zhihu.com/question/343655023/answer/3122803497)

[adityatelange.in](https://adityatelange.in/)



I add how to [activate WebStorm2023.3.2](https://jihuo.live/2024/01/10/webstorm-2023-3-2-%E6%BF%80%E6%B4%BB%E7%A0%B4%E8%A7%A3%E6%95%99%E7%A8%8B/)

### Edit Workspace in VScode

### Google update

[【Chrome自动更新修复】检查更新时出错：无法启动更新检查（错误代码为 4: 0x80070005 -- system level）](https://blog.csdn.net/qq_16763983/article/details/126216331)

### Git

用Git上传项目到github

（一）主要部分：

`cd d:`

`cd Git/projects/<repo name>/` (进入本地仓库目录)

`ls -a` (确认当前仓库是否为github仓库)

或者进入本地仓库，右键`open git bash here`.

`git add .`

`git commit -m "描述你的更改"`

`git push origin main`

（二）常见问题：

`git pull origin <branch_name>` 将远处仓库与本地同步

`git push -u origin <branch_name>` 如果是第一次推送需要添加-u

`git pull origin main --allow-unrelated-histories` 强制合并不相关的历史记录

问题已经解决，换了个网...

When I use `git push origin main`

ssh: connect to host github.com port 22: Connection timed out
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.

[ssh git clone](https://gist.github.com/Tamal/1cc77f88ef3e900aeae65f0e5e504794)

### Wolfram

`Plot[x^2+y^2, {x, -3, 3}, {y, -3, 3}]`

我无法连接至pinterest.jp

### Manim

已经成功安装manimgl和ffmpeg，无法运行。待解决。

### hexo

fatal: unable to access 'https://github.com/username/username.github.io.git/': Failed to connect to github.com port 443 after 21089 ms: Couldn't connect to server
FATAL Something's wrong. Maybe you can find the solution here: https://hexo.io/docs/troubleshooting.html

Win+r 运行
%temp%
每日清缓存
cleanmgr
磁盘清理
mrt
恶意软件清理
