# linux-tcp-
实现断点续传，秒传，校验，客户端和服务器之间的下载上传大文件

server里的my_md5.c是计算md5的算法函数，此项目直接写了脚本调用了系统的命令去计算，因此这个文件用不上
一些ip，端口写在了配置文件里