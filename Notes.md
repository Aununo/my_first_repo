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

### Latex

1. 微分算子d可通过`\rm{d}`或`\text{d}`将斜体变为正体。
2. 向量的模长符号是`\left \|   \right \|`.

### Sagemath

sage中的矩阵运算

打开SageMath 9.3 Console

1. 声明一个矩阵变量

`sage: a = matrix( [ [1,2,3,4], [2,5,9,14], [4,13,29,54], [8,35,99,224] ] )`

注意：坐标的中括号外面还有一层中括号。

2. 输出矩阵

`sage: a`

>
>[    1    2    3    4]
>[    2    5    9   14]
>[    4   13   29   54]
>[    8   35   99  224]

3. 计算行列式

`sage: a.det()`

>> 12

### A Virtual Environment

1. Linux: virtual box | kvm
2. Windows: VMware player | windows virtual PC
3. MacOS: QEMU | parallels

### kali linux

#### install kali linux in the virtual box (Windows)

1. download and install [virtual box](https://www.virtualbox.org/wiki/Downloads).
2. head over to the [kali linux](https://www.kali.org/get-kali/#kali-virtual-machines)
3. path`D:/ISO/Linux/kali-linux-2023.4-virtualbox-amd64`

#### run

1. default admin and password: kali & kali.
2. You can customize the size of window and fonts in terminal by
`File - Preference - Appearance - Font change - 20pt`
3. update the package index.
`sudo apt-get update`
4. ensure all installed packages are brought up to their latest versions.
`sudo apt-get upgrade`
5. tidy up and clear some space.
`sudo apt-get autoremove`
6. remove any downloaded packages that are no long needed.
`sudo apt-get clean`
7. clear the terminal.
`clear`

### Related Websites

[爆肝一天，国内外所有GPT完全注册教程-保姆级教程（附带GPT和Plus以及本地部署教程)](https://zhuanlan.zhihu.com/p/648732646)

[Git官方教程](https://git-scm.com/book/en/v2)

[Git分布式管理](https://www.educoder.net/paths/cgknh4of)

[联邦学习](https://zhuanlan.zhihu.com/p/79284686)

[神奇网站](https://www.zhihu.com/question/343655023/answer/3122803497)

[adityatelange.in](https://adityatelange.in/)

### Local Website

Here we have an awesome tutorial [快速搭建个人博客——保姆级教程](https://pdpeng.github.io/2022/01/19/setup-personal-blog/)
I add how to [activate WebStorm2023.3.2](https://jihuo.live/2024/01/10/webstorm-2023-3-2-%E6%BF%80%E6%B4%BB%E7%A0%B4%E8%A7%A3%E6%95%99%E7%A8%8B/)

### Edit Workspace in VScode

### Google update

[【Chrome自动更新修复】检查更新时出错：无法启动更新检查（错误代码为 4: 0x80070005 -- system level）](https://blog.csdn.net/qq_16763983/article/details/126216331)


