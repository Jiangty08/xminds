# Linux

------

Linux基础知识学习有助于对计算机系统的理解，同时其中包含的各类工具（grep、awk、vim等）极大提升工作效率，是不可或缺的技能。学习分为如下几个方面：

* 基础知识
* Shell编程
* GNU工具使用
* Vim使用

## Linux基础知识

### 环境搭建

搭建Linux开发环境是学习的第一步，可以根据喜好选择如下任意一种方法：

1. 直接安装Linux系统

    * Linux发行版有很多：Debian、Ubuntu、CentOS、Red Hat等等，初学者通常使用Ubuntu作为入门系统：https://www.ubuntu.com/download

2. 使用虚拟机安装Linux

    * 常用虚拟机：

        * [Vmware](http://www.vmware.com/)——功能更强大
        * [VirtualBox](https://www.virtualbox.org/)——轻量级虚拟机
        
    * 虚拟机可以通过方式1中的镜像直接安装，也可以从网上下载现有系统：https://virtualboxes.org/images/

3. 在线学习Linux

	* 常用在线环境：

		* [实验楼](https://www.shiyanlou.com/courses/)
		* [jslinux](http://bellard.org/jslinux/)
		* [cb.vu](http://cb.vu/)

	* 实验楼除了包含Linux开发环境，还包括一些在线课程可供学习

### 学习资料

* [鸟哥的Linux私房菜](http://linux.vbird.org/)
* [Linux公社](http://www.linuxidc.com/)
* [Linux思维导图整理](http://www.jianshu.com/p/59f759207862)


## GNU学习

### shell编程

* 《shell脚本学习指南》非常实用的文档，网上可以下载
* 命令解释[ExplainShell.com](ExplainShell.com)
	* 对于Linux用户来说每天都会写各种命令和脚本，那么你可以使用这个网站工具来查看命令式如何工作的,这样可以避免不必要的错误出现；也是一个很好的学习命令的方式
* [在线查看命令帮助](Linuxmanpages.com)
* oh-my-zsh：https://github.com/robbyrussell/oh-my-zsh
* github上找一些小项目实战：https://www.zhihu.com/question/28182203

熟练使用man查看帮助，参照《Shell脚本学习指南》，多做练习，很快你就可以掌握基本的Shell编程技能。

### GNU开发环境

Toolchain、Compiler、Library、Binutils、Debug、**Makefile**

## Vim使用

程序员用的编辑器有很多——notepad++、sublime、atom、集成开发环境等等，其中vim是Linux下一款非常强大的编辑器，学习资料：

* [给想学习VIM的超级小白的文章](https://zhuanlan.zhihu.com/p/22530297)，其中整理了vim学习的资料非常全。

* 常规学习步骤：

	* 在shell下执行vimtutor，按照教程熟悉基本使用
	* 使用[Bundle](https://github.com/VundleVim/Vundle.vim)进行插件管理
	* 定制化Vim，配置合适自己使用的vim，github上有很多
		* http://amix.dk/vim/vimrc.html
		* https://github.com/spf13/spf13-vim
		* https://github.com/amix/vimrc
	* 使用插件，让vim更强大：http://vimawesome.com/