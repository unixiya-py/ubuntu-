### 切换软件源：

默认中国服务器，我们把它切换成aliyun的。
在设置--软件和更新里--下载自--其他站点--中国--
http://mirrors.aliyun.com/ubuntu

### 更新：

sudo apt-get update  
sudo apt-get upgrade  

### 把中文支持更新完全
在设置--语言支持里，点开自动提示。

### 移除附带软件
sudo apt-get remove libreoffice-common
sudo apt-get remove unity-webapps-common    

### 将启动器移动到屏幕底部
$ gsettings set com.canonical.Unity.Launcher launcher-position Bottom
