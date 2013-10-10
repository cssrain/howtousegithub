如何使用GitHub
==============

##Git,Github,SVN简介
Git，SVN：版本控制工具

Github：代码托管网站

用户可以通过Git来把代码提交到Github中。

Git 是 Linus 在开发 Linux 内核时用于替换 Bitkeeper 版本控制工具（该工具不是免费的）而写的一个开源的分布式版本控制软件。而 Github 是一个代码托管网站。而代码托管的意思是允许人们把代码放到 Github ，并为团队开发提供一种比较简单的代码同步方法。Git 是一个分布式的版本控制工具。分布式主要是针对已有的 SVN 、CVS 受中央控制的版本控制工具而言的。在git里，每个代码库在相互独立的同时，又可以相互交换代码（通过push/pull）进行代码的交换。这里主要介绍Github在 Windows 上的使用。


##安装Github
在http://windows.github.com/ 上下载 Github for Windows ，按提示安装即可。在安装过程中，git 的命令行版本也会一并安装。虽然在 Windows 下大多数应用都是基于图形界面的，但是使用 git 还是很有必要用命令行。

Github for Windows 实际上是 Github 网站的客户端版本，有网站上的一切功能，并且，为上传、更新位于 github.com 的代码库进行了良好的支持。使用 Github 帐号登陆以后，在图形界面里可以轻易地创建代码库。


##Git常用命令

* `git clone <address>`：复制代码库到本地。
* `git add <file> ...`：添加文件到代码库中。
* `git rm <file> ...`：删除代码库的文件。
* `git commit -m <message>`：提交更改，在修改了文件以后，使用这个命令提交修改。
* `git pull`：从远程同步代码库到本地。
* `git push`：推送代码到远程代码库。
* `git branch`：查看当前分支。带*是当前分支。
  * `git branch <branch-name>`：新建一个分支。
  * `git branch -d <branch-name>`：删除一个分支。
* `git checkout <branch-name>`：切换到指定分支。
* `git log`：查看提交记录（即历史的 commit 记录）。
* `git status`：当前修改的状态，是否修改了还没提交，或者那些文件未使用。
* `git reset <log>`：恢复到历史版本。
 

##一般的开发流程
一般使用 git 的流程：

1. 编辑文件，更新代码。
2. 添加代码到当前待提交的更改列表中：git add <修改的文件>。 
3. 提交当前修改作为一个记录：git commit -m '修改了<修改的文件>，原因是：……'。
4. 更新代码：git push。


*  [原文链接](https://github.com/yfwz100/neuola/wiki/github使用指南)
 

##相关内容
Markdown : 是一种轻量级标记语言

编辑软件：http://markdownpad.com/    在线编辑：http://mahua.jser.me/

Goagent：翻墙

如何安装：https://code.google.com/p/goagent/

