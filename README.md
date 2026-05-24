# wmt_qt_study
[WIP] My Qt5 and Qt4 study

## Windows sources
* qt-opensource-windows-x86-mingw492-5.6.1-1.exe
* qt-creator-opensource-windows-x86-4.0.0.exe
* videoviewer.zip, work_qt_20220531.7z, my qt company project code  

## Embedded Linux sources
* qt-everywhere-opensource-src-4.8.6.tar.gz
* qt4-nes_v5_xiaozhi.tar.gz
* https://github.com/weimingtom/wmt_d1s_study
* https://github.com/weimingtom/xiaozhi_playground/tree/master/qt4-nes_without_input
* https://github.com/weimingtom/xiaozhi_playground/tree/master/qt4-nes_with_input

## Unused sources
* qt-everywhere-opensource-src-5.15.8.tar.xz
* qt-everywhere-src-6.2.4.tar.xz
* qt-embedded-linux-opensource-src-4.5.3.tar.gz

## Install Qt5 with apt install in Xubuntu 20.04
* Xubuntu 20.04: sudo apt install qt5-default
```
但目前我只知道xubuntu 20.04可以很容易apt install qt5-default，
其他诸如ubuntu 25.04则无法轻松安装qt5，所以我优先用xubuntu 20.04，
或者等以后有时间研究怎么从源码编译安装qt5 ​​​
```

## Install Qt5 with apt install in Xubuntu 25.04
* Xubuntu 25.04: sudo apt install qtbase5-dev  
* See also: https://www.thundercomm.com/rubik-pi-3/cn/docs/rubik-pi-3-user-manual/1.1.2/qt5-user-guide  
* sudo apt install build-essential     
* sudo apt install qtcreator  
* sudo apt install qtbase5-dev qtchooser qt5-qmake qtbase5-dev-tools qtbase5-examples qtbase5-doc-html
* ??? not need qt5-doc ????   
```
一定要确保make和gcc/g++已经安装，否则需要在qtcreator的Preferences -> Compilers里面
重新点Re-detect按钮（不过有可能重启qtcreator也会自动检测）
qt5-doc不知道为什么装不上
```
```
我测试过，如果是Xubuntu 25.04的话，如果要用qt5写代码，除了装gcc g++ cmake make以外，
只要再装qtcreator和qtbase5-dev就可以了，qtbase5-dev就相当于以前的qt5-default，
或者可能以前的qt5-default就包含了qtbase5-dev，只是后来这个包消失了（可能在ubuntu 20之后），
所以只能用qtbase5-dev这个apt包安装qt5
```

## 昉·惊鸿-7110 Linux Qt开发指南
* https://www.bilibili.com/video/BV1tFMczDEes/
* https://doc.rvspace.org/JH7110/DevKit/QT/JH7110_DevKit_QSG/QT/introduction.html
