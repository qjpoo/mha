## 文件说明

```
m1  s1  s2 三台mysql服务器做好基于gtid的主从复制   
.
├── Atlas-2.2.1.el6.x86_64.rpm                  # 读写分离软件
├── email
│   ├── send
│   ├── sendEmail
│   └── testpl                                  # 测试是否能发邮件
├── manager-cnf
│   └── dg.cnf                                  # manager管理的配置文件
├── master_ip_failover                          # 故障转移的脚本
├── mha4mysql-manager-0.56-0.el6.noarch.rpm     # manager软件
├── mha4mysql-node-0.56-0.el6.noarch.rpm        # node软件  
└── mysql-cnf
    ├── m1-my.cnf                               # m1 mysql的配置文件
    ├── s1-my.cnf                               # s1 mysql的配置文件
    └── s2-my.cnf                               # s1 mysql的配置文件
```
