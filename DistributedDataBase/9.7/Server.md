Business node 

Code Server

hint EulerOS RD

Middle Agent；




// targetServerType=master 表示只向主库发送写请求
String url = "jdbc:postgresql://192.168.1.10:5432,192.168.1.20:5432/mydb?targetServerType=master";

// targetServerType=preferSlave 表示优先将读请求发给副机
String urlRead = "jdbc:postgresql://192.168.1.10:5432,192.168.1.20:5432/mydb?targetServerType=preferSlave";
