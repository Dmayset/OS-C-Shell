# OS-C-Shell
C shell

本次实验用到了 readline库， 安装命令如下： yum install readline-devel

在编译main文件时需要加上 -lreadline 参数

运行文件是要：sudo ./main,因为实现 ping 命令需要创建线程
