
telnet 192.168.0.16 8000
telnet 192.168.0.16 8000


gsql -d <数据库名称> -h <集群地址> -U <数据库用户> -p <数据库端口> -W <集群密码> -r

*Public 115.120.251.254
gsql -d <gaussdb> -h <115.120.251.254> -U <dbadmin> -p <8000> -W <!NCckh30568!> -r
*Private IP address 192.168.0.14 
gsql -d <gaussdb> -h <192.168.0.14> -U <dbadmin> -p <8000> -W <!NCckh30568!> -r

path /tmp/tools
cd /tmp/tools
ls -l
rm -rf /tmp/tools

wget https://obs.cn-north-1.myhuaweicloud.com/dws/download/dws_client_9.1.1_euler_kunpeng_x64.zip
unzip dws_client_9.1.1_euler_kunpeng_x64.zip


