https://ping.pe   https://ip.sb/      powercfg -h off        chrome.exe"  -incognito         
https://github.com/MHSanaei/3x-ui     
https://github.com/mack-a/v2ray-agent     

https://my.vultr.com  
https://www.oracle.com/cloud/sign-in.html     
https://app.cloudcone.com.cn/?ref=2444   
https://nerdvm.racknerd.com/login.php   

https://dash.cloudflare.com/login    icook.tw/443/8443/2053/2083/2087/2096  linitef764@ovobri.com   
https://idx.google.com     bash <(wget -qO- https://raw.githubusercontent.com/yonggekkk/argosb/main/argosb.sh)  
https://replit.com/login     fork：replit.com/@yonggekkk           bivit10443@clubemp.com  

iptables -P INPUT ACCEPT   
iptables -P FORWARD ACCEPT   
iptables -P OUTPUT ACCEPT  
iptables -F   

echo root:16  | sudo chpasswd root  
sudo sed -i 's/^#\?PermitRootLogin.*/PermitRootLogin yes/g' /etc/ssh/sshd_config  
sudo sed -i 's/^#\?PasswordAuthentication.*/PasswordAuthentication yes/g' /etc/ssh/sshd_config   
sudo rm -rf /etc/ssh/sshd_config.d/*   
sudo service sshd restart   
***systemctl enable ssh.service  

slmgr.vbs /upk  
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX  
slmgr /skms win.kms.pub  
slmgr /ato  

Cloudflare套CDN：  dash.cloudflare.com/login  
1. 添加DNS记录并开启小黄云  
2. SSL/TLS加密改为完全   SSL/TLS边缘证书打开自动 HTTPS 重写  
3. 规则/概述/创建规则/选择配置/源服务器规则Origin Rules   
添加：字段：主机名   运算符：通配符   值：开启小黄云的域名  And   
添加：字段：SSL/HTTPS    值：开启   
目标端口：选择：重写到...vps节点端口   
