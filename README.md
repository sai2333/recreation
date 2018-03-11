# recreation
## 吃喝玩乐,[demo](http://saiblog.top/recreation/index.html)
使用了boostrap栅格布局，boostrap导航条和boostrap的轮播图。slick.js插件实现多图轮播。用到部分CSS3动画。
## 导航条和轮播图 ##
[![9WfG0x.md.png](https://s1.ax1x.com/2018/03/11/9WfG0x.md.png)](https://imgchr.com/i/9WfG0x)
* 轮播图是一个默认的boostrap轮播。图片是1920*1080的格式，在1920宽度以上的情况下设置了700px。其他设备宽度自适应。
* 导航条使用了反色导航条，修改了下拉菜单的样式，还有表单的样式。
[![9Wfhcj.md.png](https://s1.ax1x.com/2018/03/11/9Wfhcj.md.png)](https://imgchr.com/i/9Wfhcj)
下拉菜单使用了CSS3的translateX(x)过渡效果。同时导航条是固定页头的。

## 活动内容 ##
[![9WfoBq.md.png](https://s1.ax1x.com/2018/03/12/9WfoBq.md.png)](https://imgchr.com/i/9WfoBq)
* 使用了栅格排列
* 使用CSS3的translateY(y),和background-image替代蒙板。
* hover，focus时，模板opacity:0,添加阴影，y轴移动效果。

## 多图轮播 ##
[![9Whi4O.png](https://s1.ax1x.com/2018/03/12/9Whi4O.png)](https://imgchr.com/i/9Whi4O)
* slick.js插件，自适应设备。可拖拽滑动图片。
* CSS3阴影和translateY(y)

总结：练习的这个demo页头用了boostrap的导航条和表单固定，轮播图。之后分成4部分内容，除了多图轮播，其他部分使用栅格完成布局。页脚同样使用栅格布局。
* 由于768px设备导航条溢出，所以舍弃了搜索框。
* 修改1440px到768px 导航条的每个链接的间距。超大屏幕默认40px。
* 有些图片使用蒙板确实会好看些。增加用户的交互效果，蒙板可以嵌套在图片父元素里面。使其width和height百分百。然后使用background：rgba();
