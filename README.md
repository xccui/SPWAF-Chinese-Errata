# 《基于Apache Flink的流处理》勘误表

|章节|页数  |位置 |类型    |更正前        |更正后         | 提交者 |
|---|-----|-----|-------|-------------|--------------|----------|
|封面|/|副标题|翻译|~~操作~~|**运维**|Xingcan|
||
|译者序|/|第13/16行|拼写|~~Visia~~|**Vasia**|Xingcan|
|前言|3|第14行|拼写|示例~~CD-ROW~~|示例**CD-ROM**|Fanxi|
|前言|3|第17行|错别字|通常包括~~数~~名|通常包括**书**名|-|
||
|第2章|38|第6行|翻译|~~每分钟收到事件数目的是由数据本身的时间来定义的~~|**每分钟的事件数目应该由数据自身所含的时间信息来定义**|Zhanglu He|
||
|第3章|62|图3-9左上1图|错别字|~~不~~位线|**水**位线|Guihai Liu|
|第3章|64|倒数第3行|错别字|Flink对它们都一~~直~~同仁|Flink对它们都一**视**同仁|Guihai Liu|
||
|第5章|97|第6行|拼写|~~Labmda函数~~|**Lambda**函数|Fanxi|
|第5章|99|倒数第6行|错别字|它会将白色方块不~~将~~改动直接输出|它会将白色方块不**加**改动直接输出|Guihai Liu|
|第5章|100|第2行|错别字|// O: 输~~入~~元素的类型|// O: 输**出**元素的类型|Guihai Liu|
|第5章|100|第5行|拼写|fla~~g~~Map转换|fla**t**Map转换|Guihai Liu|
|第5章|100|倒数第3行|错别字|使用你之~~见~~看到过的|使用你之**前**看到过的|Guihai Liu|
|第5章|111|倒数第6行|代码|~~env.env.getParallelism~~|**env.getParallelism**|zh0122|
|第5章|111|倒数第3、8行|代码|~~env:~~|**env =**|Xingcan|
|第5章|112|第8行|代码|~~result: =~~|**result =**|Xingcan|
||
|第6章|131|倒数第14行|错别字|它通过跟踪~~至~~今为止|它通过跟踪**迄**今为止|Guihai Liu|
|第6章|135|倒数第14行|拼写|~~getRunteimContext()~~|**getRuntimeContext()**|Yichao Yang|
|第6章|139|示例6-7第6/13行|标点|~~《》~~|**\"\"**|Jeff Yang|
|第6章|141|第21行|代码|~~ctx.timerService().deleteEventTimeTimer(curTimerTimestamp)~~|**ctx.timerService().deleteProcessingTimeTimer(curTimerTimestamp)**|Yichao Yang|
|第6章|168|示例6-18|原文代码|~~input1.keyBy(...).between(...)~~|input1.keyBy(...)**.intervalJoin(input2.KeyBy(...))**.between(...)|Yichao|
||
|第8章|219|第13行|翻译|~~精确一次~~|**至少一次**|Mason More|
||
|第9章|280|第7行|拼写|~~k~~eytabs|**K**eytabs|Guihai Liu|
||
|第11章|327|第2行|错别字|~~可以~~用户行为|**可疑**用户行为|Guihai Liu|
||
|作者介绍|/|第5行|翻译|~~费比安~~|**Fabian**|Xingcan|
||
|封底|/|第17行|翻译|~~一次精确~~|**精确一次**|Guihai Liu|
