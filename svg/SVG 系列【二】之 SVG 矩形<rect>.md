

##SVG 系列【二】
####SVG 矩形
####SVG 预定义形状
- ***矩形 <rect>***
- 圆形 <circle>
- 椭圆 <ellipse>
- 线 <line>
- 折线 <polyline>
- 多边形 <polygon>
- 路径 <path>

#### SVG 矩形属性
``` xml
<svg xmlns="http://www.w3.org/2000/svg" version="1.1">
  <rect x="50" y="20" rx="20" ry="20" width="100" height="100" style="fill:blue;fill-opacity:0.5;stroke:pink;stroke-width:5;stroke-opacity:0.8;"/>
</svg>
```
##### 属性
- x/y 属性定义矩形距离浏览器左侧/顶部的距离（px）
- width/height 属性定义矩形的宽/高
- rx/ry 属性定义矩形的四个角圆角
- CSS 属性 fill 定义矩形的填充颜色
- CSS 属性 fill-opacity 定义定义填充颜色透明度（0 - 1）
- CSS 属性 stroke 定义矩形边框的颜色
- CSS 属性 stroke-width 定义矩形边框的宽度
- CSS 属性 stroke-opacity 定义边框颜色的透明度（0 - 1）

##### 效果
![image](http://www.uis.cc/uploadfile/2014/1115/20141115094855464.jpg)