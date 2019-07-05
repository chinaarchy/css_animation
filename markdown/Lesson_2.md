### lesson 2
CSS3 2D转换
#### 对应参数及兼容性
```css
div
{
transform: rotate(30deg);
-ms-transform: rotate(30deg);		/* IE 9 */
-webkit-transform: rotate(30deg);	/* Safari and Chrome */
-o-transform: rotate(30deg);		/* Opera */
-moz-transform: rotate(30deg);		/* Firefox */
}
```
#### 转换方法
- translate()  修改位置
- rotate()   旋转
- scale()    缩放
- skew()  翻转根据X轴和Y轴
- matrix()  将以上所有方法融合
