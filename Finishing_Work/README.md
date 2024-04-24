# DataMining

This repository mainly records notes related to data mining .

[JCCGGKS/DataMining (github.com)](https://github.com/JCCGGKS/DataMining)

## 将本地文件上传到github的步骤：

### (第一步)在GitHub上创建仓库（远程仓库）
具体操作步骤如下：

​	在 GitHub 上创建一个新的代码仓库。
​	打开 GitHub 网站，登录账号。
​	点击页面右上角的加号图标，选择 “New repository” 创建新的仓库。
​	输入仓库名称、描述等信息，选择公开或私有，然后点击 “Create repository” 完成创建。
### (第二步)安装Git
​	安装 Git 可以按照以下步骤进行：

​	在 Git 官网（https://git-scm.com/downloads）下载适用于你的操作系统的 Git 安装包，例如 Windows 或 macOS 系统。该软件包包含了 Git Bash、Git GUI 等常用工具。

​	安装 Git。在 Windows 操作系统中，双击下载的 Git 安装包，按照提示进行安装即可。在 macOS 操作系统中，双击下载的 dmg 文件，将 Git 拖动到“应用程序”文件夹中即可完成安装。

配置 Git。安装完成后，打开终端或 Git Bash（Windows 系统），输入以下命令来配置 Git：

```git
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

这里的 "Your Name" 和 "your_email@example.com" 分别为你的用户名和邮箱地址，将它们替换为你自己的即可。这些信息将用于标识你提交的代码的作者。

在安装配置完Git,任意右击你电脑的文件夹都能看到Git Gui Here和Git Bush Here

Git Bash：Git Bash 是 Git 在 Windows 操作系统上的命令行工具，它提供了一种与 Linux 和 macOS 终端类似的界面，可以通过命令行执行 Git 的各种操作。使用 Git Bash 可以快速、方便地操作 Git，而不需要在 Windows 上安装类 Unix 的命令行工具。
Git GUI：Git GUI 是 Git 提供的图形界面工具，它提供了一个可视化的界面，可以用来执行 Git 的大多数操作。Git GUI 支持各种 Git 操作，包括提交、分支管理、版本控制等。相对于 Git Bash，Git GUI 更加直观易用，可以方便地执行一些常见的 Git 操作。
检查 Git 是否已经安装：

git --version
如果 Git 已经安装，则会显示 Git 的版本号，例如：git version 2.33.0.

检查 Git 是否已经配置用户名和邮箱：

```git
git config --global user.name
git config --global user.email
```

如果输出了你的用户名和邮箱地址，则说明 Git 已经配置完成。如果没有输出，则说明你还需要配置用户名和邮箱。则需要执行上面配置Git步骤。

### (第三步)上传文件到Github（本地仓库–>远程仓库）

```git
 create a new repository on the command line
```

```git
echo "# DataMining" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:JCCGGKS/DataMining.git
git push -u origin main
```

```git
push an existing repository from the command line
```

```git
git remote add origin git@github.com:JCCGGKS/DataMining.git
git branch -M main
git push -u origin main
```

------------------------

#### 之后的学习规划

在理解理论知识的基础之上，能够复现代码并跑起来。了解并掌握pytorch。