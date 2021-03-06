---
id: 5a9036d038fddaf9a66b5d32
title: 使用 grid-template-columns 添加多列
challengeType: 0
videoUrl: 'https://scrimba.com/p/pByETK/c7NzDHv'
forumTopicId: 301117
---

# --description--

简单地添加一个网格元素并不会有任何明显的效果。你还需要明确网格的结构。在一个网格容器中使用`grid-template-columns`属性可以添加一些列，示例如下：

```css
.container {
  display: grid;
  grid-template-columns: 50px 50px;
}
```

上面的代码可以在网格容器中添加两列，宽度均为 50px。 `grid-template-columns`属性值的个数表示网格的列数，而每个值表示对应列的宽度。

# --instructions--

给网格容器设置三个列，每列宽度均为`100px`。

# --hints--

`container`类应该有`grid-template-columns`属性，该属性有三个值，均为`100px`。

```js
assert(
  code.match(
    /.container\s*?{[\s\S]*grid-template-columns\s*?:\s*?100px\s*?100px\s*?100px\s*?;[\s\S]*}/gi
  )
);
```

# --solutions--

