# x
## 基于区块链的粉丝经济

[基于区块链的粉丝经济](#_Toc60775938)

[1.背景与现状](#_Toc60775939)

[2.区块链与粉丝集资的匹配度分析](#_Toc60775943)

[3.基于区块链的粉丝经济方案设计](#_Toc60775944)

[4.关键技术及方法](#_Toc60775950)

[5.应用与实践](#_Toc60775953)

[6.商业模式](#_Toc60775954)

[7结束语](#_Toc60775961)

## 1.背景与现状

**明星效应促进新消费时代偶像电商实现流量向销量的转化**

粉丝经济，即粉丝群体对偶像行为及其作品的自发关注、分享、持续大量传播所带来的商业传播影响力，以及以粉丝为主要核心消费者，围绕偶像所做出的直接或间接的购买行为，所产生的经济效益。

偶像类艺人通过节目形成流量大爆发，原先的粉丝应援力量已经不足以匹配其现在的流量，粉丝们会主动寻求外援协助项目落地。粉丝集资的平台也有不少，如摩点,Owhat。据了解，之前在摩点App上集资提现会有3%的手续费，但后来又改为不收取服务费。Owhat对于粉丝集资则一直强调无手续费。换句话说，虽然集资抽成对平台来说不是一笔小数目——在《创造101》播出期间，吴宣仪后援会某次集资金额近207万，假如按3%的比例来算，平台手续费就在6万以上。

但这几年，粉丝应援集资数额越来越大，百万、千万级别金额的经费不在少数，因为应援集资出现矛盾的情况时有发生。的确出现过不少站子捐款逃跑，卖了周边却不发货，账目明细与打款对不上的事件，粉丝很少能讨回说法，向平台投诉、警方报案也很难追责。对应援账目现状，其实在一些日常应援活动中，账目明细也几乎是所有应援站的敏感话题。首先，影响力大、职务健全的应援站，其财务也比较规范化，但不意味着账目明细更加透明，因为数据透明会被对家监控，这中间存在某种竞争关系。其次，小的应援站人力有限，记账工作比较繁杂。另外，也存在一些灰色地带的站长不愿意公开账目，还有一些数据不适合公开，比如粉丝会为艺人刷量。

**目前粉丝经济平台的问题**![image-20210106003636177](https://i.loli.net/2021/01/06/GxLqNETcrQiAVIy.png)

##   开发环境的配置

| 类别              | 标准配置                 | 最低配置                 |
| ----------------- | ------------------------ | ------------------------ |
| 计算机硬件配置CPU | Intel(R) Corei72.60GHz   | Intel(R) Corei5 3.50GHz  |
| 内存              | 8GB                      | 8GB                      |
| 显卡              | 集成                     | 集成                     |
| 网卡              | 千兆以太网               | 千兆以太网               |
| 软件配置          | Windows 10系统           | Windows 10系统           |
| 软件              | Remix，solidity0.6.0版本 | Remix，solidity0.5.0版本 |

 

##  运行环境的配置

| 类别          | 标准配置                 | 最低配置                 |
| ------------- | ------------------------ | ------------------------ |
| 计算机硬件CPU | Intel(R) Corei72.60GHz   | Intel(R) Corei5 3.50GHz  |
| 内存          | 8GB                      | 8GB                      |
| 显卡          | 集成                     | 集成                     |
| 网卡          | 千兆以太网               | 千兆以太网               |
| 软件配置      | Windows 10系统           | Windows 10系统           |
| 软件          | Remix，solidity0.6.0版本 | Remix，solidity0.5.0版本 |
|               | NodeJS v12.18.3          | NodeJs v11               |

  [src=http___www.zhicheng.com_uploadfile_2018_0716_20180716113805635.jpg&refer=http___www.zhicheng.jfif](C:\Users\86188\Desktop\src=http___www.zhicheng.com_uploadfile_2018_0716_20180716113805635.jpg&refer=http___www.zhicheng.jfif) 