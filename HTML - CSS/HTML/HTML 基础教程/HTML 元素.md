HTML 元素
---

#### HTML 文档是由 HTML 元素定义的。

---
### HTML 元素
HTML 元素指的是从开始标签（start tag）到结束标签（end tag）的所有代码。

| 开始标签 | 元素内容 | 结束标签 |
| --- | --- | --- |
| `<p>` | This is a paragraph | `</p>` |
| `<a href="default.htm">` | This is a link | `</a>` |
| `<br />` |   |   |

**注释：**开始标签常被称为开放标签（opening tag），结束标签常称为闭合标签（closing tag）。

---
### HTML 元素语法
* HTML 元素以**开始标签**起始
* HTML 元素以**结束标签**终止
* **元素的内容**是开始标签与结束标签之间的内容
* 某些 HTML 元素具有**空内容（empty content）**
* 空元素在开始标签中进行关闭（以开始标签的结束而结束）
* 大多数 HTML 元素可拥有属性

<span style="color: #ff9955;">提示：</span> 您将在本教程的下一章中学习更多有关属性的内容。

---
### 嵌套的 HTML 元素
大多数 HTML 元素可以嵌套（可以包含其他 HTML 元素）。

HTML 文档由嵌套的 HTML 元素构成。

**HTML 文档实例：**
```html
<html>

<body>
<p>This is my first paragraph.</p>
</body>

</html>
```
上面的例子包含三个 HTML 元素。

---
### HTML 实例解释
** `<p>` 元素：**
```html
<p>This is my first paragraph.</p>
```
这个 `<p>` 元素定义了 HTML 文档中的一个段落。

这个元素拥有一个开始标签 `<p>`，以及一个结束标签 `</p>`。

元素内容是：This is my first paragraph。
