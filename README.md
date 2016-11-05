试试如何在markdown里使用文本来描述图片：

- 参考了这个页面：<https://github.com/TLmaK0/gravizo>
- 使用了[graphviz](http://www.graphviz.org/)中的[DOT](http://www.graphviz.org/content/dot-language)语言，[在线试验页面](https://mdaines.github.io/viz.js/)
- 主要使用了这个服务：<http://www.gravizo.com/>，[在线转换页面](http://www.gravizo.com/#converter)
 
![my-graph](http://g.gravizo.com/g?
digraph G {
  node [shape=box]
  "发布任务，选出参加人员以及确定 owner"
  -> "商量表现形式"
  -> "准备资料并下发"
  -> "owner 和成员进行沟通，制定时间表 和人员与场景的分配图"
  -> "进行排练，根据实际情况调整方案"
  -> "制定替补方案，在必要时启用"
  -> "准备现场要用的东西，检查东西是否可用"
  -> "开始前调试摄像机、分发资料"
  -> "活动开始声明注意事项，老师讲开场白"
  -> "并布置任务"
  -> "各小组组织活动"
  -> "老师进行总结，活动结束"
  -> "拍照留念并庆祝活动成功"
  -> "做 retro 进行活动总结"
  -> "对 retro 之后的建议进行书面总结"
})

```
![my-graph](http://g.gravizo.com/g?
digraph G {
  node [shape=box]
  "发布任务，选出参加人员以及确定 owner"
  -> "商量表现形式"
  -> "准备资料并下发"
  -> "owner 和成员进行沟通，制定时间表 和人员与场景的分配图"
  -> "进行排练，根据实际情况调整方案"
  -> "制定替补方案，在必要时启用"
  -> "准备现场要用的东西，检查东西是否可用"
  -> "开始前调试摄像机、分发资料"
  -> "活动开始声明注意事项，老师讲开场白"
  -> "并布置任务"
  -> "各小组组织活动"
  -> "老师进行总结，活动结束"
  -> "拍照留念并庆祝活动成功"
  -> "做 retro 进行活动总结"
  -> "对 retro 之后的建议进行书面总结"
})
```