# pageStyle
用来存储一些好看的ui设计，和样式



### calc()函数

在CSS中，`calc()` 函数用于在样式表达式中进行计算。它可以用来执行基本的数学运算，如加法 (+), 减法 (-), 乘法 (*) 和除法 (/)。`calc()` 特别有用，因为它允许你混合使用不同的单位，例如百分比 (%)、像素 (px)、em单位、rem单位、视窗单位 (vw/vh) 等。

这个函数可以用在任何接受数值的CSS属性上，比如 `width`、`height`、`margin`、`padding`、`top`、`left`、`right`、`bottom`、`font-size` 等。

在上述例子中：

- `width: calc(100% - 50px);` 计算元素宽度为其容器宽度减去50像素。
- `font-size: calc(1.5em + 2px);` 计算字体大小为基于当前字体大小的1.5倍加上2像素。
- `margin-top: calc(100vh - 2 * 100px);` 计算上边距为视窗高度减去200像素（两倍的100像素）。
- `width: calc(100% - var(--sidebar-width));` 使用CSS变量 `--sidebar-width` 来计算元素宽度。





box-sizing: border-box; /* 包含内边距和边框在内的高度计算 */
