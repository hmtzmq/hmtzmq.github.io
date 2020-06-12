# hmtzmq.github.io
--------------------------------------
一键安装代码:

bash <(curl -L -s https://raw.githubusercontent.com/wulabing/V2Ray_ws-tls_bash_onekey/master/install.sh) | tee v2ray_ins.log

BBR 加速代码: BBR 加速：

wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh

如果安装不了 BBR 请先运行以下代码：

yum -y install wget
------------------------------------------------------------------------------------------------------------------------------

wget -O fuck_Aliyun.sh https://git.io/fpN6E && bash fuck_Aliyun.sh
------------------------------------------------------------------------------------------------------------------------------
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/wulabing/V2Ray_ws-tls_bash_onekey/master/install.sh" && chmod +x install.sh && bash install.sh
同上
------------------------------------------------------------------------------------------------------------------------------
更新系统组件

#Debian/Ubuntu：
apt-get update

#RedHat/CentOS：
yum update

下载bash命令并注册到系统
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/leitbogioro/WedTools/master/Linux_reinstall/InstallNET.sh' && chmod a+x InstallNET.sh

全自动化安装Debian 9（官方支持期限至2022年·）
bash InstallNET.sh -d 9 -v 64 -a

全自动化安装CentOS 7
bash InstallNET.sh -c 7.2 -v 64 -a

默认的SSH登录密码是Vicer 用户root
改密passwd

这个纯净版系统安装后，并没有自带curl组件，后者是一款利用URL语法在命令行下工作的文件传输工具，很多脚本、命令需要使用这个组件，安装curl：
apt-get install curl
