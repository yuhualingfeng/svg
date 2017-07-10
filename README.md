##SVG中的元素
###svg
svg元素定义了一个画布,它有以下属性:

+ width:画布的宽度
+ height:画布的高度

```
<svg width="400" height="400"></svg>
```

###circle
circle元素是在画布中定义一个圆,它有以下属性:

+ cx:圆相对画布的横向偏移量
+ cy:圆相对画布的纵向偏移量
+  r:圆的半径

css属性:

+ fill:颜色填充

```
<svg width='400' height='400'>
	<circle cx='50' cy='50' r='30' style='fill:#ff6600;'></circle>
</svg>
```

###animate
animate元素定义一个图形的动画,它有以下属性:

+ attributeName:产生动画的属性
+ attributeType:产生动画的属性类型,有两个可选值:`XML`,`CSS`
+ from:产生动画的属性的初始值
+ to:产生动画的属性的最终值
+ dur: 动画持续时间

###animateMotion
沿着某一路径运动
##SVG中的CSS属性

+ fill
+ fill-opacity
+ stroke
+ stroke-width
+ stroke-opacity



##参考手册
https://developer.mozilla.org/zh-CN/docs/Web/SVG
https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API
http://theoatmeal.com/