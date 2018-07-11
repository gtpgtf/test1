# 牛刀小试 — Linux
```
- 不积跬步，无以至千里;不积小流，无以成江海。
```

## 一、单选题



### 1.按照Ubuntu版本发布规律，2013年04月发行的版本，版本号应该是(    )
    A. 13.04	B. 13.02	C. 13.06	D. 12.08

### 2.Linux系统是参照(    )系统演变而来的
    A.unix	B.windows	C:Android	D.IOS

### 3.Redhat、Ubuntu、Debian都是基于（    ）系统的发行版
    A. Windows	B. linux	C. Anroid	D. ox

### 4.Ubuntu下安装管理软件包使用（    ）命令
    A.brew	B.yum	C.ls	D.apt-get

### 5.进入或切换目录使用( )命令
    A. ls   B. ln  C. cd  D. pwd

### 6.查看当前目录下的文件信息用( )命令
    A. ctrl+l  B. ls  C. cd  D. cd -

### 7.查看当前所在目录位置使用( )命令
    A. pwd  B. ls  C. ctrl+d  D. ctrl+f

### 8.用于复制文件命令（ ）
    A.rm		B.mv	C.cp			D.ctrl+c

### 9.下面哪个Linux命令可以一次显示一页内容（ ）
    A. pause 		B. cat 	C. more 		D. grep 

### 10.设置/test/a.txt属主有读写执行权限，属组，有读写，其他账户无权限（ ）
    A、 chmod 760 /test/a.txt		
    B、 chmod 762 /test/a.txt
    C、 chmod 761 /test/a.txt		
    D、 chmod 777 /test/a.txt

### 11.如何删除/tmp下所有A开头的文件？( )
    A、rm -rf /tmp/A*		B、rm /tmp/A*
    C、rm -if /tmp/A*		D、rm -i /tmp/A*

### 12.mv命令不具备（  ）功能
    A、移动文件		B、查看	C、重命名		D、移动文件夹

### 13.如何创建g1 组( )
    A、 groupdel g1	B、 groupadd g1	C、 chmod g1		D、 chown g1

### 14.下面远程登录写法正确的是( )
    A、sh uname@127.0.0.1 	B、 ssh 127.0.0.1@uanme
    C、ssh uname@127.0.0.1	D、 scp uname@127.0.0.1

### 15.远程拷贝文件用的命令是( )
    A、cp 		B、 scp	C、 ssh		D、 tar

### 16.用于归档文件的命令是( )
    A、cp 		B、 tar	C、 ping		D、 sip

### 17.根目录用什么表示( )
    A、/	B、 //	C、 \	D、 home

### 18.搜索文件的命令为( )
    A、grep	B、 cd	C、 ls	D、 find

### 19.强制删除文件夹的命令是( )
    A、rm -rf		B、 rm -r		C、 rm -f			D、 rm

### 20.创建文件夹的命令是( )
    A、touch		B、 tar	C、 mkdir		D、 vi

### 21.搜索文件内容的命令为( )
    A、grep		B、 cd	C、 ls		D、 find

### 22.查看IP地址的命令是( )
    A、ps		B、 du	C、 ifconfig	D、 ping

### 23.查看进程的命令是( )
    A、ps -aux	B、 ping	C、 ifconfig	D、 df

### 24.修改文件权限的命令是( )
    A、chown	B、 chgrp	C、 chuser	D、 chmod

### 25.以下说法正确的是(  )
    A、cd表示进入某个文件夹	B、Touch表示创建一个文件夹
    C、mkdir表示创建一个文件	D、rm可以直接删除文件夹

### 26.下列不是重启命令的是（ ）
    A、reboot	B、shutdown -r now 	C、init 0	  D、init 6

### 27.要使用SSH服务器服务端需要安装（ ）
    A、apt -get			B、pip
    C、openssh-server 		D、openssh-client

### 28.下列说法正确的是（ ）
    A、检测整个磁盘空间使用du	B、检测目录所占用的磁盘空间使用df
    C、查看ip地址使用Ping		D、可以使用cal查看日历

### 29.下面关于查看进程信息的命令说法正确的是（ ）
    A、使用df可以查看进程信息		B、可以使用du查看进程信息  
    C、ps-aux可以查看进程信息		D、top跟显示进程无关


## 二、判断题

### 1.需要自动补齐当前命令后续的字符用tab键（  ）
### 2.显示文本文件内容可以用cat命令(    ) 
### 3.重定向 > 表示输出，会将内容重定向到文件末尾（ ）
### 4.用who命令查询当前登录的用户(   ) 
### 5.使用pwd可以查看当前目录所有文件（  ） 
### 6.tar -jxvf可以压缩打包文件（  ）
### 7.Linux中查找文件的命令是grep（   ）

## 三、简答题

* 什么是绝对路径，什么是相对路径？

* 什么是操作系统?
* 常见的linux发行版本?(三种)
* 单用户操作系统和多用户操作系统的区别?
* Linux的根目录是什么?
* /home目录是什么?
* Linux终端命令格式
* 命令ls –la 的效果是什么?
* 清屏的命令是什么?
* 放大和缩小窗口字体大小的操作是什么?
* 使用man时的操作键 b键的作用?
* 通配符[]表示什么?
* cd – 的含义?
* 如何递归创建目录?
* 重定向>和>>的区别?
* 写出关机的命令 三种?
* 写出重启的命令 三种?
* 用户权限rwx分别表示什么?全拼是什么?
* 如何更改文件权限?
* 退出当前登录用户的命令?
* 查看进程的详细状况的命令是什么?
* apt是什么?
* 安装跑小火车的命令是什么?
* Vim编辑器命令行模式下写出三种退出并保存的指令?
* Vim编辑器命令行模式下强制退出的指令?
* Vim编辑器如何复制多行

 




























