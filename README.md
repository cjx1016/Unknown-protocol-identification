网络流量未知协议识别
===
- 研究意义
    网络协议的准确分类与识别是提高差异性服务质量保障、入侵检测、流量监控及计费管理等方面的基础。随着网络技术的不断革新，新型网络应用协议不断涌现，它们的协议规范属于公司专利或者技术秘密，没有公开可得到的协议规范文档，这给网络协议分类与识别带来了新的挑战。

- 背景知识  
  - 协议  
    1. 运行在网络中的设备和软件都遵守着一定的规则, 这些规则被称为协议 。**网络上传输的数据要按照一定的协议格式进行打包封装成数据包后才能在网络中正确地传输。**由于网络中存在多种协议, 故需要分析网络中传输的数据包使用何种协议,即对数据包进行协议分析。  
    2. 私有协议/未知协议：指的是协议规格不公开的协议，从民用上看包括QQ协议、Skype协议等社交网络协议，以及商业用途的通信协议和工业系统的工控协议等等。从军事上看，包括所有军事用途的对外不公开的协议。  
    3. 网络协议由三个部分组成：语义、语法和时序。语义是解释控制信息每部分的意义，它规定了需要发出何种控制信息以及完成的动作与做出什么样的响应；语法是用户数据和控制信息的结构与格式以及数据出现的顺序；时序是对事件发生顺序的详细说明。  
  - 协议分析技术  
    协议分析技术是一个大的概念，这里面包括两个分支，一个是协议逆向工程，一个是流量分类与识别，即DPI，这两个技术是相辅相成的。  
  - 协议逆向工程  
    **协议逆向工程是指在不依赖协议描述的情况下，通过对协议实体的网络输入输出、系统行为和指令执行流程进行监控和分析，提取协议语法、语义和同步信息的自动化过程，是工程化的协议逆向分析方法。**随着网络规模的扩大和应用种类的增多，对协议逆向的准时性和时效性要求越来越高，自动化协议逆向分析技术成为人们追求的目标。  
  - 网络流量协议的分类与识别（DPI）  
    DPI技术，Deep Packet Inspect，中译为深度包检测，其概念建立在精细分析数据包，力求从头到尾分析数据包，通过分析协议数据包内部，由此分析协议的相关属性。可以说，协议逆向工程中的最简单的部分实际上就是DPI技术。  
    


