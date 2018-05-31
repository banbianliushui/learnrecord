1.[CSS grid](https://www.smashingmagazine.com/2018/05/future-of-web-design/)
```css
.grid {
  display: grid;
  grid-template-columns: 100px 100px 100px 100px;
  grid-column-gap: 20px;
}
```
2.[understanding-sizing-css-layout -grid](https://www.smashingmagazine.com/2018/01/understanding-sizing-css-layout/)

3.动画函数
https://easings.net/zh-cn

4. 初始包含块
  一个元素盒子的位置和大小有时相对于一个确定的矩形计算，这个矩形叫做元素的包含块.元素的包含块定义如下:

  根元素所在的包含块，被称为初始包含块。对于连续媒体，它具有视口的尺寸，且固定在一个画布的原点；它是分页媒体的页面区域。 初始包含块'direction' 属性和根节点相同。
  对应其他元素，如果元素的position位置是'relative' 或 'static'，包含块由最近的块容器祖先盒子的内容边缘形成。
  如果元素有'position：fixed'，则包含块由连续媒体的视口或分页媒体的页面区域 建立.
  如果元素有'position：absolute'，则包含块由具有'absolute'，'relative'或'fixed'的'position'的最近祖先建立，通过以如下方式建立：
    在祖先是内联元素的情况下，包含块是围绕在 为元素生成的第一个和最后一个内联框的填充padding框的边界框。 在CSS 2.1中，如果内联元素被分割成多行，那么包含块是未定义的。
    否则，包含块由祖先的padding边缘形成。
  如果没有这样的祖先元素，则包含块是初始包含块。
The containing block in which the root element lives is a rectangle called the initial containing block. For continuous media, it has the dimensions of the viewport and is anchored at the canvas origin; it is the page area for paged media. The 'direction' property of the initial containing block is the same as for the root element.
For other elements, if the element's position is 'relative' or 'static', the containing block is formed by the content edge of the nearest block container ancestor box.
If the element has 'position: fixed', the containing block is established by the viewport in the case of continuous media or the page area in the case of paged media.
If the element has 'position: absolute', the containing block is established by the nearest ancestor with a 'position' of 'absolute', 'relative' or 'fixed', in the following way:
In the case that the ancestor is an inline element, the containing block is the bounding box around the padding boxes of the first and the last inline boxes generated for that element. In CSS 2.1, if the inline element is split across multiple lines, the containing block is undefined.
Otherwise, the containing block is formed by the padding edge of the ancestor.
If there is no such ancestor, the containing block is the initial containing block.
[Rendering: repaint, reflow/relayout, restyle](http://www.phpied.com/rendering-repaint-reflowrelayout-restyle/)
[初始包含块](https://www.w3.org/TR/CSS21/visudet.html#containing-block-details)
