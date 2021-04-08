
随着工业4.0 概念的提出，现代工业逐渐向智能制造转型，各类采集器、控制器、传感器等设备以及移动通信、智能分析等技术开始融入到工业生产过程的各个环节中，形成了高度依赖云计算、大数据等技术，进行实时数据收集和处理以最终实现智能化生产的工业物联网。近两年，5G 技术飞速发展，其 **高带宽、低时延、广覆盖、高可靠** 的特性与工业领域对于数据通信的需求高度匹配，为工业物联网平台构建提供了有力保障。

但与此同时，工业物联网的发展也面临着不容忽视的挑战。工业物联网下游涉及大量精密的工业设备接入，而工业领域的控制协议种类繁多，不同的设备厂商有其各自专有的工业协议。 **要想实现终端设备数据上云，除了借助 5G 提供的传输效率保障，还需要解决各厂商标准迥异的工业协议的整合统一。** 

基于这一痛点，EMQ 团队研发了 [边缘工业协议网关软件 EMQ X Neuron](https://www.emqx.io/cn/products/neuron)（以下简称 Neuron ），着眼工业物联网发展需求和未来布局，力图为 5G 时代工业 4.0 平台的构建赋能。Neuron 取自「神经元」一词，代表了 **EMQ 对这一产品的定位与愿景**：在工业物联网庞大复杂的数据传输系统中，Neuron 作为布局在边缘端的基本功能单元，可以对每一组织内的终端数据信息进行接收与整合，并传输至更上游的「神经中枢」即云端平台，经过进一步的数据分析处理，做出符合业务需求的快速响应与决策，从而实现整个工业物联网系统的高效柔性运转。

## Why EMQ X Neuron ?

### 70+ 工业协议支持

支持超过 **70 种主流工业协议**接入（这一数量还将持续增加），包括 **Modbus RTU、Modbus TCP、Ethernet/IP、OPC/UA** 等，解析并转换为统一的 [MQTT 协议](https://www.emqx.io/cn/mqtt) 后，与 EMQ X Edge 和 Kuiper 集成进行边缘流式分析与计算，或直接接入云端工业物联网平台。

### 超越普通的网关

可同时运行 **业务逻辑服务、事件触发脚本、边缘规则处理引擎、标准工业警报判定** ，赋予设备边缘层更多能力。Neuron 也提供了扩展接口，可以实现自定义协议的接入。

### Web 管控平台

一站式平台网关配置管理。所有配置、规则、标签可通过 **Web平台统一管理**，通过 Web 服务可省却现场操作，远程即可实现设备的监控、维护、配置管理等功能。

![Web 管控平台.png](https://static.emqx.net/images/657a2478f2604fb042f4b1b533dd5b2a.png)

### 跨平台、低功耗

软件由 C 语言实现，适合轻量级的工业类设备，包括各类硬件，支持 **X86、ARM、MIPS 32 位与 64 位 CPU 架构**，以及主流的 **Linux 系统**。




Neuron 的发布无疑将使 5G 时代的工业物联网如虎添翼。不仅如此，我们将通过集成 Neuron，Edge 和 Kuiper 等软件，实现在边缘端的工业协议解析、数据汇聚和流式处理的一整套边缘解决方案；其与云端的 EMQ X Broker/Enterprise 等系列产品进一步集成，则可以实现一个端到端的从边缘到云端的完整工业解决方案。

![跨平台、低功耗.png](https://static.emqx.net/images/ba0d5b290ecb9d0a8f7e92b60462a405.png)

这一完整工业解决方案计划于 **2020 年 9 月**发布，将探索边云协同的全栈全场景，在构建面向 5G 的泛工业物联网平台，赋能工业领域的网络化、数字化和智能化等方面做出积极努力，助力推进工业4.0 进程。

我们相信和期待一个人与机械高效协作的未来，并愿意为之付出不竭努力。


> **Neuron 产品研发的主要贡献者：** Joey Cheung，Neuron 产品线总监，15 年自动化设备控制软件、HMI、SCADA 编写经验，参与过国内外大型工业自动化生产线项目，现专注工业物联网平台的软件开发。


