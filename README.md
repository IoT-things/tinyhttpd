# Tinyhttp 学习
---

本项目是用来学习 tinyhttp 的。

参考仓库1: https://github.com/EZLippi/Tinyhttpd

[README](./1.md)

参考仓库2：https://github.com/cbsheng/tinyhttpd

[READNE](/2.md)

参考理解:

1、管道学习：https://blog.csdn.net/qq_42914528/article/details/82023408

2、标准输出输入理解,(STDIN，STNOUT(printf)),通过管道连接两个进程，子进程中执行.cgi脚本，将数据通过 print 输出(重定向到管道)，父进程中，将 POST 的数据写入到管道中，供子进程使用，并将子进程数据的数据发送到 socket。
