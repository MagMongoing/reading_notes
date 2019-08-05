1、MySQL的复制原理以及流程
(1)、先问基本原理流程，3个线程以及之间的关联；

(2)、再问一致性延时性，数据恢复；

(3)、再问各种工作遇到的复制bug的解决方法。

 

2、MySQL中myisam与innodb的区别，至少5点

(1)、问5点不同；

(2)、问各种不同mysql版本的2者的改进；

(3)、2者的索引的实现方式。

 

3、问MySQL中varchar与char的区别以及varchar(50)中的30代表的涵义

(1)、varchar与char的区别；

(2)、varchar(50)中50的涵义；

(3)、int(20)中20的涵义；

(4)、为什么MySQL这样设计。

[备注] 本人也面试了近12个2年MySQL DBA经验的朋友，没有一个能回答出第(2)、(3)题

 

4、问了innodb的事务与日志的实现方式

(1)、有多少种日志；

(2)、日志的存放形式；

(3)、事务是如何通过日志来实现的，说得越深入越好。

 

5、问了MySQL binlog的几种日志录入格式以及区别

(1)、各种日志格式的涵义；

(2)、适用场景；

(3)、结合第一个问题，每一种日志格式在复制中的优劣。

 

6、问了下MySQL数据库cpu飙升到500%的话他怎么处理？

(1)、没有经验的，可以不问；

(2)、有经验的，问他们的处理思路。

 

7、sql优化

(1)、explain出来的各种item的意义；

(2)、profile的意义以及使用场景；

(3)、explain中的索引问题。

 

8、备份计划，mysqldump以及xtranbackup的实现原理

(1)、备份计划；

(2)、备份恢复时间；

(3)、备份恢复失败如何处理。

 

9、500台db，在最快时间之内重启

 

10、在当前的工作中，你碰到到的最大的MySQL DB问题是？

 

11、innodb的读写参数优化

(1)、读取参数，global buffer pool以及 local buffer；

(2)、写入参数；

(3)、与IO相关的参数；

(4)、缓存参数以及缓存的适用场景。

 

12、请简洁地描述下MySQL中InnoDB支持的四种事务隔离级别名称，以及逐级之间的区别？

 

13、表中有大字段X(例如：text类型)，且字段X不会经常更新，以读为为主，请问

(1)、您是选择拆成子表，还是继续放一起；

(2)、写出您这样选择的理由。

 

14、MySQL中InnoDB引擎的行锁是通过加在什么上完成(或称实现)的？为什么是这样子的？