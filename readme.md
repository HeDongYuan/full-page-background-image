# full-page-background-image

我们的目标是让**一张**背景图能够覆盖整个浏览器窗口，并且随着浏览器窗口大小的改变而自适应。

进一步可以考虑多张背景图，进而实现fullpage的效果

## 单全屏

当前考虑两种实现

1. [full-page-background-image-1.html](https://github.com/byr-gdp/full-page-background-image/blob/master/full-page-background-image-1.html) 
2. [full-page-background-image-2.html](https://github.com/byr-gdp/full-page-background-image/blob/master/full-page-background-image-2.html)

`background-size`取值问题得完善

## 多全屏

### 实现原理

1. div绝对定位
2. width/height 100%
3. top根据第几屏来设置

[multiple-page-background-image.html](https://github.com/byr-gdp/full-page-background-image/blob/master/multiple-page-background-image.html.html)