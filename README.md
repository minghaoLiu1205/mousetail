#####作品描述：
这是一个采用面向对象方法编写的一个鼠标再屏幕上滑过会出现很多五颜六色的小球的效果。其中有三个类型的鼠标炫彩小尾巴，读者可以自行选择使用。

#####所属分类：
面向对象编程

#####设计难点：
通过创建数组的方法管理小球的产生和消失

#####业务逻辑分析：
定时器一直开启，如果用户移动鼠标，创建小球的实例。小球的实例会自动进入数组，定时器会遍历小球数组，调用所有小球的update方法，此时小球就能移动、减小半径。

#####效果展示：
[查看演示](http://donymh.cn/tail/)