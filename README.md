# Smartisan-index-special-effects
# 锤子科技官方首页特效  极简版

# 原理： 
     ①使用CSS3的transform-style: preserve-3d构建一个3D透视空间。
   
     ②获取鼠标X，Y轴线性运动变量。 
   
     ③为了使鼠标左右移动图片产生左右偏转，得把鼠标运动到banner图中间点为“0,0”，这样的话往左为负，往右为正。
   
     ④把变量赋值给CSS3的rotateX,rotateY。
   

## 刚开始我们给图片外层的div添加两个事件监听，

    ①当它移动时候触发rotate函数，

    ②当它移出的时候触发outBox函数，

    ③e.pageX是鼠标的X轴，this.offsetWidth/2是本身宽度的一半，this.offsetLeft距离它上一层（父级）距离左边框的距离，

    ④e.pageY是鼠标的Y轴，this.offsetHeight/2是本身高度的一半，this.offsetTop距离它上一层（父级）距离上边框的距离，

### 具体见源码及其注释！！！

