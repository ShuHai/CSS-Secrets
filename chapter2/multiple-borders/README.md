让我们先回顾一下box-shadow的基本知识。
Box-shadow是边框阴影效果，默认参数为X轴偏移量，Y轴偏移量，模糊程度以及阴影宽度和颜色。
我们可以通过box-shadow来模拟外框，通过连续加几层box-shadow来实现多重边框。
注意的地方：box-shadow只是阴影无法进行各种诸如点击绑定事件之类的操作.
outline是元素的轮廓属性，作用于border外侧，利用轮廓来实现多重边框效果的好处在于可以创建虚线边框之类box-shadow做不到的功能。缺点在于只能实现两层边框，如果要更多层我们依旧要借助于box-shadow。