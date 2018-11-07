
工程介绍：
    eureka-server:注册中心
    admin-server: 监控管理中心
    

redis: 
    120.79.23.207:16379
mysql:
    120.79.23.207
    3306
    用户:root
    密码:root
nginx:
    120.79.23.207:10080

rabbitmq:
    120.79.23.207
        5673->5672
        15673->15672
        liuye/liuye
       

mongodb:
    120.79.23.207
        27017->27017
        admin->sdyin
        
hadoop:
    http://120.79.33.160:50070/
    
elasticsearch:
    http://120.79.23.207:9200

mysql主从
    master 47.107.124.85 3306 root/root test/123456
    slave  47.107.124.85 3307 root/root
    
zookeeper 集群
    47.107.124.85 2181
    47.107.124.85 2182
    47.107.124.85 2183
