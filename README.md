# Unity-Visual-Components
**Visual Components**<br><br>
![Visual Components](https://github.com/ChallengerCY/Unity-Visual-Components/blob/master/Unity-VisualComponents/Picture%26Gif/Visual%20Components.gif)

**Text**
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Text组件，也被称为标签组件，拥有一个文本区域来显示需要显示的文本。可以设置字体、字体样式、字体大小以及文本是否具有富文本的能力。可以设置文本的对齐方式。horizontal 和 vertical overflow 可以设置换行方式。还有一个Best Fit选项可以将文本大小调整到最合适的样式。

**Image**
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Image包括一个RectTransform组件和一个Image组件，Image组件下面的Source Image可以设置一个sprite，color可以选项设置它的color。Material选项可以设置它的材质。Image Type可以设置Sprite的展示方式。<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Simple-以相同大小展示。<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sliced 使用3*3分割sprite，使得Sprite的边缘部分不会拉伸，只有中间区域会被拉伸。 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tiled-平铺Sprite。 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Filled - 和Simple相同的方式展现Sprite，可以通过比例填充来显示Sprite。<br>
Set Native Size选项用于当Image Type为Simple或者Filled选项模式下，将Image重置为和Sprite一样的大小。
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Images资源可以通过"Texture Type"选项中的Sprite( 2D / UI)设置成UI sprites。与老的GUI sprites 相比，Sprites有额外的导入设置，最大的区别是添加了Sprite editor。Sprite editor提供了9-slicing 选项，可以将图片分成九个区域，这样调整Sprites之后，除了中心以外其他部位不会发生变化。

**Raw Image**
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Image使用Spirte但是Raw Image使用Texture.Raw Image只在必要时使用，否则Image会适用于大多数情况。

**Mask**
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mask不是一个可以直观看到的组件，它是用来修改子元素显示外观的组件。Mask将子元素限制为父元素的形状。因此，如果子节点比父节点大，那么只有父节点内的子节点部分是可见的。

**Effects**
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
可视化组件还可以应用各种简单的特效，例如一个简单Shadow或者Outline。
