title: Elastic-Job-Lite 源码分析 —— 作业失效转移【编辑中】
date: 2017-11-07
tags:
categories: Elastic-Job
permalink: Elastic-Job/job-failover

-------

![](http://www.yunai.me/images/common/wechat_mp_2017_07_31.jpg)

> 🙂🙂🙂关注**微信公众号：【芋道源码】**有福利：  
> 1. RocketMQ / MyCAT / Sharding-JDBC **所有**源码分析文章列表  
> 2. RocketMQ / MyCAT / Sharding-JDBC **中文注释源码 GitHub 地址**  
> 3. 您对于源码的疑问每条留言**都**将得到**认真**回复。**甚至不知道如何读源码也可以请教噢**。  
> 4. **新的**源码解析文章**实时**收到通知。**每周更新一篇左右**。  
> 5. **认真的**源码交流微信群。

-------

# 1. 概述

本文主要分享 **Elastic-Job-Lite 作业失效转移**。

涉及到主要类的类图如下( [打开大图](http://www.yunai.me/images/Elastic-Job/2017_11_07/01.png) )：

![](http://www.yunai.me/images/Elastic-Job/2017_11_07/01.png)

* 粉色的类在 `com.dangdang.ddframe.job.lite.internal.failover` 包下，实现了 Elastic-Job-Lite 作业失效转移。
* FailoverService，作业失效转移服务。
* FailoverNode，作业失效转移数据存储路径。
* FailoverListenerManager，作业失效转移监听管理器。

> 你行好事会因为得到赞赏而愉悦  
> 同理，开源项目贡献者会因为 Star 而更加有动力  
> 为 Elastic-Job 点赞！[传送门](https://github.com/dangdangdotcom/elastic-job/stargazers)

# 2. 作业失效转移条件

# 3. 获取作业分片上下文集合

# 666. 彩蛋


