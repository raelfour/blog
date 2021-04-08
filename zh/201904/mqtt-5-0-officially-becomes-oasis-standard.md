NB-IoT是由 3GPP 标准化组织制定的一种新型蜂窝技术，属于低功率广域 （LPWA） 物联网连接的一种，主要用于连接带宽资源受限的终端，允许终端以比 GRPS、3G、LTE等技术更少的资源收集和交换数据。

NB-IoT 在2017-2018年发展迅速，全球众多运营商陆续实现了商用部署。NB-IoT 的低成本、低功耗和广覆盖使得用户能够实现传统蜂窝网络无法支持的新场景新应用。

**NB-IOT 技术的优势**

- 为物联网和 M2M 设计的新蜂窝技术
- 覆盖距离单元 10km 的大面积区域
- 电源效率，一个电池在现场工作长达10年
- 低成本， NB-IoT 模块成本在20元左右，且有逐年降低的趋势

**NB-IoT 应用场景**

- 消费电子
- 城市物流
- 智慧城市
- 智能家居
- 公用事业
- 自然灾害管理

从2017年起，EMQ X 公司开始与某顶级运营商合作研发物联网平台项目，在2018年发布了支持 NB-IoT 技术的全新物联网应用使能平台 （AEP）。该平台允许广大行业客户的 NB-IoT 终端，通过运营商 NB-IoT 网络直接接入，并通过平台开放能力快速构建物联网应用。 

借助于 AEP 平台提供的设备接入、消息路由、数据存储，以及设备管控服务，可大大简化应用程序的开发过程，大多数应用通过平台组件的拖放以及模板定义即可完成；客户亦可通过平台丰富的 API 接口，配合少量编码工作，就可以拥有功能完整的自研 IoT 应用，客户开发的应用能够直接运行在平台上，可节省大量运营成本。 

在本项目中，EMQ X 物联网消息中间件作为平台的核心部件，用于接入运营商全国范围内（以 NB-IoT 为主，亦包括 3G，4G，PON，LAN 等所有网络）的各类物联网设备，通过高效的协议解析与消息路由能力将海量的设备消息汇聚到平台数据层，也为后端的设备管理和应用模块提供可靠的反向控制通道。 

EMQ X 创新的分布式集群方案，能够实现新节点的自动增加和故障节点的自动删除，有力保障了 AEP 平台接入容量的自动伸缩和长期稳定运行，提升了运营商客户业务的可靠性。



![img](https://static.emqx.net/images/carrier-nb-iot-20190403.jpeg)



EMQ X 具备的海量设备接入、千万级高并发、物联网全协议栈、以及毫秒级低延时等能力，助力电信级物联网AEP平台在数月内搭建完成，有效的支撑了该运营商 NB-IoT 乃至整个 IoT 平台战略的落地与商业化运营。