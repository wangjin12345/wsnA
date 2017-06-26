# ![wsnA](https://user-images.githubusercontent.com/10429180/27527222-23499754-5a7d-11e7-9fc2-afba0b392230.png "Logo")  wsnA 
#### A tools of analysis by ANOVA for TinyOS application

wsnA是一个TinyOS应用程序运行模式分析工具, 分析的数据源是基于Cooja仿真环境收集的TinyOS应用运行时函数调用日志.
目前wsnA可以基于一些简单的方式识别出那些与网络环境密切相关的函数调用.

wsnAMain实现一个较为友好的可视化界面.

其中TaskWatch可以方便的集成到其它工程, 对于节点日志的分析主要是由它来完成.

``` python
from TaskWatch import NodeLogcalls
node = NodeLogcalls('logcalls path')
```
