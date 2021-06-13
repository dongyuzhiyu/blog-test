# a标签

a标签的格式为``<a href="" ></a>``,它可以让用户跳转到外部页面、内部锚点、邮箱和电话。

其中的主要的属性有href和target。

href的取值可以是网址，可以是路径，也可以是伪协议。

伪协议中``jacascript:代码；``其中代码为空，可以在点击超链接后不做任何操作。若换成空值，点击超链接会刷新页面；若为#xxx之类的，点击后会跳到页面顶部。

target的取值可以是_blank、_top、_parent、_self。

其中_blank是在新的标签页打开，_self是在当前页面打开，_top是在多层页面时在最上层页面打开，_parent是多层页面时在上一层页面打开。

# img标签

img标签的格式为``<img src="">``，属性中只修改高或者宽，另一个会自适应。响应式代码是``max-width= 100%``.

# table标签
 
其代码格式为
```
<table>
    <thead></thead>
    <tbody></tbody>
    <tfoot></tfoot>
</table>
```

th表示表头

# 感想

收益匪浅



