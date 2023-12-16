# Chia铭文 FAQ:

## 支持什么操作系统？

代码可以支持Linux (Ubuntu, Centos, Redhat, Deepin等）MacOS 都经过了测试。

Windows有版友也跑起来了。


## 我怎么安装python  或者python3?

英文教程 ： https://www.python.org/download/releases/2.5/msi/
中文教程： https://www.liaoxuefeng.com/wiki/1016959663602400/1016959856222624

确定你的python安装好再进行下一步

## 如何安装 Chia 客户端。
https://www.chia.net/downloads/ 


## 如何验证chia客户端安装完成。

### A) Linux 系统，打开命令行，输入 `chia` 你应该看到如下信息
   `Usage: chia [OPTIONS] Command [ARGS]`
   
   如果没有看到以上信息做如下操作：
      i) 用你熟悉的编辑器打开 ~/.bashrc  如果你熟悉Linux 可以用 vi , emacs等工具，如果不熟悉，可以用gedit等工具打开。 (gedit 安装教程：https://help.ubuntu.com/community/gedit）
      ii）再~/.bashrc文件加入一行 export PATH=$PATH:/usr/bin
      iii) 在命令行输入 source ~/.bashrc
      iv) 再重新测试chia命令就应该可以了。

### B) Mac 系统，打开命令行，输入 `chia` 你应该看到如下信息
   `Usage: chia [OPTIONS] Command [ARGS]`
   
      如果没有看到以上信息做如下操作：
      i) 用你熟悉的编辑器打开 ~/.bashrc  如果你熟悉Linux 可以用 vi , emacs等工具，如果不熟悉，可以用atom 编辑器等工具打开。 (atom 安装教程 https://formulae.brew.sh/cask/atom) 
      ii）再~/.bashrc文件加入一行 
export PATH=/Applications/Chia.app/Contents/Resources/app.asar.unpacked/daemon
      iii) 在命令行输入 source ~/.bashrc
      iv) 再重新测试chia命令就应该可以了。



                 	

