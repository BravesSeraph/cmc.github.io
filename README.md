# cmc.github.io

### 使用Fiddler和Proxifier对Filmora进行抓包
1，安装Proxifier

下载地址：http://soft.onlinedown.net/soft/971579.htm

2，配置代理服务器

配置文件->代理服务器->添加

ip：127.0.0.1  端口选择Filddler监听的端口，我的是8888

我的协议选择的是HTTPS

3，设置Fiddler

打开Fiddler->工具->选项->HTTPS，然后全勾上，这里的配置和抓移动端配置一样。注意要选择“从所有进程”
连接->Fiddler监听端口：8888  ，注意这个端口要和Proxifier的代理端口保持一致。


### 参考资料
[用Proxifier+Fiddler对PC客户端进行抓包]（https://blog.csdn.net/qq_41397201/article/details/91596196）
