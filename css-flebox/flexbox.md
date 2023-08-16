## flex-direction属性
- row
- row-reverse
- column
- column-reverse
row水平方向，column是垂直方向。

## 3种方式改变网络中元素顺序
1. 通过直接改变 HTML 代码中的元素顺序
2. 通过使用`row-reverse`或`column-reverse`可以翻转弹性盒子里行和列的元素顺序
3. 通过使用`order`属性来改变每个子元素的排列顺序

## 练习
练习：`index.html`中的弹性子元素目前成一列显示，且从上到下依次排列，重写代码使元素变成一行显示，且顺序从右往左。 你可以有多个方式来完成它！

## `align-items`和`justify-content`
### `align-items`在副轴上对齐元素
stretch
flex-start
flex-end
center


### justify-content在主轴上居中元素

### 练习：在 index.html 文件中，更新 style 来居中和对齐 box 中的元素。


## 总结
Flexbox 是关于内容的流向，而 Grid 则更关注内容的结构。 Grid 很擅长搭建页面结构，而 flexbox 则可以用于控制 grid 中的单个区域。

CSS Grid vs. Flexbox

Grid 是一种二维布局方式，而 Flexbox 是一维的。
Grid 重点关注布局, 而 Flexbox 重点关注内容的流向。
Flexbox 适用于应用的组件，而 Grid 适用于应用本身的布局。
CSS Gird 并不是 Flexbox 的替代者，它们都有各自擅长的地方，专业的开发者应该灵活结合使用它们，来创造出所需的页面布局。

总体来说，CSS Grid 擅长搭建布局结构，而 Flexbox 则擅长处理元素的流向。


## 参考链接
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox#The_two_axes_of_flexbox

[flex元素排序](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox#ordering_flex_items)