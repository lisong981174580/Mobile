## 移动端学习
> 物理尺寸类型:4.2、4.3、4.7、5.5、5.7、9.7
> 物理像素值=设备独立像素*设备像素比
### viewport
* width:设置layout viewport的宽度，值为一个正整数，或字符串“device-width"
* height:设置layout viewport的高度,这个属性对我们并不重要，很少使用
* initial-scale:设置页面的初始缩放值，为一个数字，可以带小数
* minimum-scale:设置页面最小缩放值，为一个数字，可以带小数
* maximum-scale:设置页面的最大缩放值，为一个数字，可以带小数
* user-scalable:是否允许用户进行缩放，值为‘no'或’yes'
```
<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no" />
```
### css度量单位
* px
* rem
> 相对于根元素字体大小
* em
> 相对于当前元素字体大小
* vh、vw
> viewport的百分比计量单位
* vmin、vmax
> viewport的百分比计量单位

### flex的布局
> http://www.runoob.com/w3cnote/flex-grammar.html
#### 网格布局
> http://www.css88.com/archives/8661

#### 响应式布局
> 针对不同的屏幕尺寸设置不同的样式
```
@media screen and (max-device-width: 480px) {
/* 如果设备宽度 <= 480px，将会应用这里的 CSS 代码 */
}
@media screen and (max-width: 768px) {
/* 如果视口宽度 <= 768px，将会应用这里的 CSS 代码 */
}

```
### 字体图标
> fontawesome.dashgame.com

```
//首先引入压缩文件
<i class="fa fa-camera-retro fa-lg"></i> fa-lg
<i class="fa fa-camera-retro fa-2x"></i> fa-2x
<i class="fa fa-camera-retro fa-3x"></i> fa-3x
<i class="fa fa-camera-retro fa-4x"></i> fa-4x
<i class="fa fa-camera-retro fa-5x"></i> fa-5x
```