# hmtzmq.github.io
--------------------------------------
https://github.com/2dust/v2rayNG/releases

http://www.lysesoft.com/products/andftp/

https://juicessh.com/changelog

https://accounts.binance.me/zh-CN/register?ref=35795682

------

ssh连接

 1.ssh-keygen -t rsa

 2. cd /root/.ssh

     ls

 3.mv id_rsa.pub authorized_keys  

     chmod 600 authorized_keys

 4.编辑sshd_config，7.4以上版本无此文件(RSAAuthentication)和PubkeyAuthentication两行前面的 # 去掉

      vi /etc/ssh/sshd_config

(为了安全还可以修改默认的SSH端口，找到#port 22，去掉前面的#，然后修改port后的数字。未测试)

 5.systemctl restart sshd.service

 6.使用andftp，把文件id_rsa下载到我们的电脑

7. 将PasswordAuthentication后面的yes改成no

     vi /etc/ssh/sshd_config

     systemctl restart sshd.service

​一键安装代码:

yum install -y git     #CentOS安装命令

apt install -y git     #Debian安装命令

wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/wulabing/V2Ray_ws-tls_bash_onekey/dev/install.sh" && chmod +x install.sh && bash install.sh



-------------------


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

----------------------------------------------------------------------------------------------------------------------------
centos7.7
wget --no-check-certificate -O AutoReinstall.sh https://git.io/AutoReinstall.sh && chmod +x AutoReinstall.sh && bash AutoReinstall.sh
----------------------------------------------------------------------------------------------------------------------------
Linux 密码
Pwd@CentOS
Pwd@Linux
----------------------------------------------------------------------------------------------------------------------------
修改 Linux 密码
passwd

