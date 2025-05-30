# RN8302B 三相计量芯片资源包

## 简介

本资源包提供了关于RN8302B三相计量芯片的完整资料，包括程序代码、硬件设计文件以及开发使用手册。RN8302B是一款高性能的三相计量芯片，广泛应用于智能电表、能源管理系统等领域。

## 资源内容

### 1. 程序代码
- 包含RN8302B的驱动程序和示例代码，方便开发者快速上手。
- 提供了多种编程语言的接口，支持C、C++等主流编程语言。

### 2. 硬件设计
- 提供了RN8302B的硬件设计原理图和PCB布局文件。
- 包含电源设计、信号调理电路等关键部分的详细说明。

### 3. 开发使用手册
- 详细介绍了RN8302B的功能特性、技术参数和使用方法。
- 提供了软件校表、防窃电功能、低功耗模式等高级功能的实现指南。

## 功能特性

### 计量功能
- 提供全波、基波有功电能，非线性误差<0.1%，满足0.5S和0.2S级有功电能表精度要求。
- 提供全波、基波无功电能，非线性误差<0.1%。
- 提供全波、基波视在电能。
- 提供有功、无功功率方向，支持无功四象限判断。
- 具有潜动启动功能，启动阈值可调。
- 电表常数可调。
- 提供有功、无功、视在的快速脉冲计数。
- 提供全波、基波，有功、无功和视在脉冲输出。

### 测量功能
- 提供全波和基波有功、无功、视在功率。
- 提供全波、基波和谐波三相电压电流有效值。
- 提供全波、基波功率因数。
- 提供电压线频率，测量误差<0.02%。
- 提供各相电压电流相角，测量误差<0.02°。
- 提供七路过零检测，过零阈值可设置。
- 提供电压相序错检测。
- 提供失压指示，失压阈值可设置。
- 提供灵活的电压、电流波形缓存数据。
- 提供电压暂降检测。
- 提供过压、过流检测。

### 防窃电功能
- 提供零线电流测量。
- 提供低功耗模式NVM2，用于电流比较预判，阈值2档可设置，功耗小于150μA。
- 提供低功耗模式NVM1，实现低功耗电流有效值测量，功耗小于2mA。
- 提供全失压主动上报功能，典型应用平均功耗仅为7μA。

### 软件校表
- 提供七路ADC通道增益校正。
- 提供七路ADC通道相位校正，其中A、B、C三路电流通道支持分段相位校正。
- 提供功率增益校正。
- 提供有功、无功功率分段相位校正。
- 提供有功、无功、有效值Offset校正。
- 提供校验和寄存器，对校表数据自动校验。

### 其他特性
- 适用于三相三线、三相四线制。
- 单+3.3V电源供电，具有电源监控功能。
- 内置1.25V ADC基准电压，温度系数典型值5ppm/℃，也可外接基准电压。
- 具有高速SPI接口，传输速率可达3.5Mbps，提供写保护功能。
- 具有一个中断输出引脚。
- 工作电压范围：3.0V-3.6V。
- 工作温度范围：-40℃-85℃。
- 采用LQFP44绿色封装。
- 通过欧盟RoHS指令2011/65/EU附录的修订指令(EU)2015/863的测试需求。

## 使用说明

1. **程序代码**：根据开发手册中的说明，将提供的程序代码集成到您的项目中。
2. **硬件设计**：参考硬件设计文件，搭建RN8302B的硬件电路。
3. **开发使用手册**：详细阅读开发使用手册，了解RN8302B的各项功能和使用方法。

## 注意事项

- 请确保在设计硬件电路时，严格按照提供的原理图进行，以避免不必要的错误。
- 在编写程序代码时，请参考开发手册中的API说明，确保功能的正确实现。

## 联系我们

如有任何问题或建议，请联系我们的技术支持团队。

## 下载链接
[RN8302B三相计量芯片资源包](https://pan.quark.cn/s/865d74973283) 

(备用: [备用下载](https://pan.baidu.com/s/1-zg1G9Qacwu1lhmnGW58hw?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
