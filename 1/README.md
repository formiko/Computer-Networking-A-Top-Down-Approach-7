# 计算机网络和因特网
## 1.1 什么是因特网
* 通过两种方式描述因特网
  1. 描述因特网的具体构成：基本硬件和软件组件
  2. 根据为分布式应用提供服务的联网基础设施来描述因特网
### 1.1.1 具体构成描述
* 各种网络设备都称为**主机**（host）或**端系统**（endsystem）
* 端系统通过**通信链路**（communication link）和**分组交换机**（packet switch）连接到一起
* 链路的**传输速率**（transmission）以比特/秒（bit/s，或bps）度量
* 发送端系统将数据分段，并为每段加上首部字节，由此形成的信息包称为**分组**（packet）
* 最著名的两种分组交换机是**路由器**（router）和**链路层交换机**（link-layer switch）
* 分组交换机从它的一条入通信链路接收到达的分组，并从它的一条出通信链路转发该分组
* 从发送端系统到接收端系统，一个分组所经历的一系列通信链路和分组交换机称为通过该网络的**路径**（route或path）
* 端系统通过**因特网服务提供商**(Internet Service Provider，ISP）接入因特网，包括本地电缆或电话公司那样的住宅区ISP、公司ISP、大学ISP，在公共场所提供WiFi接入的ISP、提供移动接入的蜂窝数据ISP
* 每个ISP自身就是由一个由多台分组交换机和多段通信链路组成的网络
* 端系统互联，因此ISP也必须互联。较低层的ISP通过国的、国际的高层ISP（如 Level 3 Communications、AT&T、Sprint 和 NTT）互联起来。
* 端系统、分组交换机和其他因特网部件都要运行一系列**协议**（protocol），这些协议控制因特网中信息的接收和发送
* **TCP**（Transmission Control Protocol，传输控制协议）和**IP**（Internet Protocol，网际协议）是因特网中两个最为重要的协议
* IP协议定义了在路由器和端系统之间发送和接收的分组格式
* 因特网的主要协议统称为**TCP/IP**
* **因特网标准**（Internet standard）由因特网工程任务组（Internet Engineering Task Force，IETF）研发。IETF的标准文档称为**请求评论**（Request For Comment，RFC）。RFC最初只是普通的请求评论（因此而得名）
