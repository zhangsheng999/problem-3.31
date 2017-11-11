# problem-3.31

# 背景介绍
# > 桌球模型  桌球模型则是一个常见的模型。即使桌球在台面上反射时是弹性的，且与台面之间没有摩擦，但只要台面形状对称性略低，则立即可以看到混沌现象。当台面上的桌球数目逐渐变多，并且球与球之间可以发生弹性碰撞时，问题则更加复杂，此所谓分子刚球(2d情况下是硬盘)模型，我们也将展示这样的结果。


### 题目 ： Study the behavior for other types of tables. one interesting possibility is a square table with a circular interior wall located either in the center, or slightly off-center. Another possibility is an elliptical table.

## 1，边界为圆形时的台球的运动
   [代码](https://github.com/zhangsheng999/1111/blob/master/%E5%9C%86.txt)
    
  ![](https://github.com/zhangsheng999/1111/blob/master/%E5%9C%86.png?raw=true)
 
##### 由图可知在半径为r的圆形桌面上台球的运动应该是高度规则的

## 2, A square table with a circulai interior wall located either in the center（边界为运动场时台球的运动）
[代码](https://github.com/zhangsheng999/1111/blob/master/%E8%BF%90%E5%8A%A8%E5%9C%BA.txt)


![](https://github.com/zhangsheng999/1111/blob/master/%E8%BF%90%E5%8A%A8%E5%9C%BA.png?raw=true)

##### 上图即为运动场模型，即在两个半圆之间加上一块矩形区域，矩形长度为σr，这样使得球台的对称性很大破坏。可以发现，现在台球的轨迹几乎可以铺满整个台面，运动无规律性也大大提高。

##### 图(1)(2)则分别是边界为体育场形状σ=o.oo5时的台球轨迹和相空间x，Vx在y=0的截面。


## 3，An elliptical table(边界为椭圆时台球的运动)
[代码](https://github.com/zhangsheng999/1111/blob/master/%E6%A4%AD%E5%9C%86.txt)

![](https://github.com/zhangsheng999/1111/blob/master/%E6%A4%AD%E5%9C%86.png?raw=true)

##### 上图展示了边界是椭圆的情况，并且台球发射位置恰为椭圆焦点，这样台球运动每次都会再次经过焦点。与运动场模型不同的是，运动场是边界形状不是圆形等高度规则的形状，而椭圆是边界为圆锥曲线的具有一定对称性的规则图形。

##### 边界为椭圆时的台球运动情况，长短轴分别是a=3^½，b=1，台球从焦点出发，将会不断回到焦点。(a)图展示台球轨迹，而(b)展示台球相空间x，Vx的图形，取y=0的截面，由于台球每次都必须经过焦点，因此截面只会出现在｜x｜=2^½


## 其实这次所讨论的桌球模型也是混沌现象的一种。可以发现，在一定合适条件下桌球运动是能呈现出良好的规律性的，例如像圆形桌面台球。但是稍微有一点对称性被破坏的情况，则效果显而易见，会产生混沌现象，例如椭圆模型以及运动场模型。


# > 致谢

#### 万分感谢陈遥洋学长提供的代码以及帮助。



