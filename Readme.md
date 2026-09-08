cat /etc/os-release
cd /



mkdir -p /var/tmp/tools
cd /var/tmp/tools

gsql -d gaussdb -h 192.168.0.14 -U dbadmin -p 8000 -W '!NCckh30568!' -r

wget https://obs.cn-north-1.myhuaweicloud.com/dws/download/dws_client_9.1.1_euler_kunpeng_x64.zip &&unzip dws_client_9.1.1_euler_kunpeng_x64.zip

source gsql_env.sh
