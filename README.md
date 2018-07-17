# zju-rvpn-ubuntu
这份文档将帮助你在 ubuntu16.04_64位 上搭建 rvpn 服务，让我们开始吧！

## 安装jre(java runtime environment)
选择1 安装旧版本的jre  
(1)下载 Linux 的 Java虚拟机安装文件: jre-版本-linux-x64.bin  
登录java(oracle) http://www.oracle.com/technetwork/java/javase/downloads/index.html  
用邮箱注册一个账号  
在上述页面找到 Java Archive, 点击 DOWNLOAD, 然后点击 Java SE 6, 找到 Java SE Runtime Environment 6u27, 选择 Accept License Agreement,  点击 jre-6u27-linux-x64.bin, 下载到 ~/Downloads 或者 ~/下载  
(2)打开终端  
```Bash
cd /usr/local/  
sudo mkdir java # 或者 sudo mkdir -p /usr/local/java  
cd ~/下载  # 或者在下载页面右键打开终端  
sudo cp -r jre-6u27-linux-x64.bin /usr/local/java  
```
