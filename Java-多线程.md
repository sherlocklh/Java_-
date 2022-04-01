# Java-多线程

## 线程创建方式：

![image-20210827140840108](C:\Users\91539\AppData\Roaming\Typora\typora-user-images\image-20210827140840108.png)

![image-20210827140957259](C:\Users\91539\AppData\Roaming\Typora\typora-user-images\image-20210827140957259.png)

![image-20210827160605082](C:\Users\91539\AppData\Roaming\Typora\typora-user-images\image-20210827160605082.png)

# 网络编程

![image-20210901212433577](C:\Users\91539\AppData\Roaming\Typora\typora-user-images\image-20210901212433577.png)

https://blog.csdn.net/vic_qxz/article/details/80481612

应用层：

直接面向用户提供服务的，完成用户希望在网络上完成的各种工作（用户接口，实现各种服务）

表示层：

对来自应用层的命令和数据进行解释，对各种语法赋予相应的含义，并按照一定的格式传送给会话层（处理用户信息的表示问题，如编码，数据格式转换和加密解密等）

会话层：

不同机器上的用户之间建立和管理会话。向两个实体的表示层提供建立和使用连接的方法。将不同实体之间的表示层的连接称为会话。（在网络上传输数据之前，必须先建立会话）

传输层：

向用户提供可靠的端到端的差错和流量控制，保证报文的正确传输

网络层：

解决不同子网之间的通信。寻址，交换，路由算法，连接服务（IP）

数据链路层：

mac地址，通过各种控制协议，将有差错的物理信道变为无差错，能可靠传输数据帧的数据链路

物理层：

利用传输介质为数据链路层提供物理连接，实现比特流的透明传输



ping和普通发消息的关系：

![image-20210917134145617](C:\Users\91539\AppData\Roaming\Typora\typora-user-images\image-20210917134145617.png)



