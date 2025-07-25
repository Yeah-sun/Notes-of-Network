# Notes-of-Network
(本人关于计算机网络学习的笔记)
#### 1.基本概念:
* 互联网(internet)
* 学习中需要搭建的环境
* 初步认识客户端-服务器
* Java的跨平台原理和C/C++的跨平台区别
--
* [x] 网络协议
* [x] 网络分层模型
* [x] 网络请求过程
* [x] 计算机之间的通信基础
* [x] 计算机之间的连接方式
    1.网线直连
    2.同轴电缆(Coaxial)
    3.集线器(Hub)
    4.网桥(Bridge)
    5.交换机(Switch)
    6.路由器(Router)
#### 2.MAC地址和IP地址
* [x] **初识MAC地址**:
  * MAC地址的表示格式
  * MAC地址的查询与获取
  * ARP广播与ICMP
* [x] **初识IP地址**:
  - IP地址的组成
  - IP地址的分类
  - 子网掩码的CIDR
  - 子网划分
     1. 为什么要进行子网划分
     2. 子网划分--等长子网划分和变长子网划分
  - 超网
     1.  合并网段
     2.  合并网段的规律
   
#### 3.路由
* [x] 初识路由
* 静态路由与动态路由
* 静态路由的实例展示
* 路由表-4种路由形式
  * 特定主机路由
  * 网络路由
  * 默认路由
  * 汇总路由
  --
* [x] 琐碎知识
* 数据包的传输过程
* 网络,互联网,因特网
* ISP网络服务商
* 服务器机房
* 网络分类
* 常见的几种接口
* 上网方式-1.电话线入户 2.光纤入户 3.网线入户
* 家用无线路由器的逻辑结构
* 公网IP,私网IP,NAT
  
 #### 4.物理层和数据链路层
* [x] 物理层
* 再次回忆网络互联模型
* 再次回忆请求过程
* 再次回忆网络分层
* 数字信号,模拟信号
* 数据通信模型
* 信道的理解
* [x] 数据链路层
* 初识数据链路
* 数据链路层的3个基本问题:
  * 封装成帧
  * 透明传输
  * 差错检验
* CSMA/CD协议,以太网帧
* PPP协议
* 网卡

#### 5.网络层
*  整体初识网络层
*  网络层首部
   * 版本,首部长度,区分服务
   * 总长度  
   * 标识,标志,ping的常见用法
   * 片偏移
   * 生存时间
   * 协议,首部校验和
* 网络层数据部分
   * ARP,ICMP,IP 
  
#### 6.传输层
* 初识传输层的俩个协议
* UDP(Transmission Control Protocol)
   * 数据格式
   * 校验和
   * 端口
* TCP(User Datagram Protocol)
   * 数据格式以及俩个细节
   * 检验(checksum)和数据偏移(data offset)
   * 标志位(Flags)
   * 序号(Sequence Number),确认号(Acknowledge Number),窗口(Window)
   * TCP的4大要点
     * 可靠传输
     * 流量控制
     * 拥塞控制
     * 连接管理 