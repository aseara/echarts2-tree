# echarts2-tree

echarts2 版本2.2.7

echarts2中tree的连线是没有箭头类型，需求要求在连线的开始和结束时都增加箭头。

查看源码后，发现force(力导向图)有画箭头的方法。根据里面的代码在tree中增加新的连线类型。