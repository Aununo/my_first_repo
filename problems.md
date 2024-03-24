# 遇到的问题

## Google update

[【Chrome自动更新修复】检查更新时出错：无法启动更新检查（错误代码为 4: 0x80070005 -- system level）](https://blog.csdn.net/qq_16763983/article/details/126216331)

## Manim (Solved)

[安装指南 -ManimGL 文档](https://docs.manim.org.cn/getting_started/installation.html)，在桌面 clone 存储库，`git clone git@github.com:3b1b/manim.git`，命令行`cd manim`，注意使用 pip 安装 manimgl 时，应使用 `pip install -e C:\User\Username\manim`，且文档提供的两种方法不要同时使用。

example_scenes.py 文件里好像有旧版本冲突的问题。

## hexo (Solved)

```
fatal: unable to access 'https://github.com/username/username.github.io.git/': Failed to connect to github.com port 443 after 21089 ms: Couldn't connect to server FATAL Something's wrong. Maybe you can find the solution here: https://hexo.io/docs/troubleshooting.html
```

> git 用 http 协议连接不上的话，可以尝试改为 ssh 协议：`git@github.com:username/repo.git`或许问题就会得到解决。

## 在 WSL 2 上运行 ubuntu (Solved)

```
Installing, this may take a few minutes...

WslRegisterDistribution failed with error: 0x80370114

Error: 0x80370114 ??????????????????

Press any key to continue...
```

> wsl 2 和 vmware 不兼容捏~ 好像是因为 hyper-v。。`wsl --set-default-version 1`