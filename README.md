# debian-6-dd-script
Debian6.0 DD脚本

确保安装了所需软件:

Debian/Ubuntu: apt-get update && apt-get install -y xz-utils openssl gawk file

RedHat/CentOS: yum update && yum install -y xz openssl gawk file

下载安装脚本并赋予权限：

wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/binghe3337/debian-6-dd-script/master/InstallNET.sh' && chmod a+x InstallNET.sh

安装：

bash InstallNET.sh -d 6 -v 32 -a -p &lt;password&gt;

打开主机控制面板的VNC：

Keyboard布局选择默认的USA，Can't access repo选择continue

使用SSH登陆，用户名root，密码为Vicer或自己设定的密码。
