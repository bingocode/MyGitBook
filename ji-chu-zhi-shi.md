# Android系统架构

一Linux内核层：Android系统是Linxu内核的，为android设备的各硬件提供底层驱动（显式驱动，蓝牙驱动等）

二系统运行库层：以一些C/C++库提供支持。如SQLite库提供数据库支持，OpenGL\ES库提供3D绘图支持，Webkit库提供浏览器内核支持，还有一些Android运行时库，提供核心库，允许java语言编写Android应用，还有Dalvik虚拟机（5.0系统后改为ART运行环境），使得android应用能够独立运行在独立的进程中，并拥有一个自己的Dalvik虚拟机实例，相比于java虚拟机，Dalvik专门为移动设备定制，对于手机内存，CPU性能优化处理

三应用框架层：构建应用程序用到的各种API

四应用层: ：所有安装在手机上的应用程序





