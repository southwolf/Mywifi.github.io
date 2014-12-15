---
layout: post
category : FrontEnd
tagline: "Shadow DOM 系列教程"
tags : [shadow DOM]
---
{% include JB/setup %}

如果你做过网站，那么很可能你已经用过一些JavaScript类库。既然如此，你可能会对这些不知名的类库作者心存感激。

这些作者——web开发领域的勇士们——都面对着同样的一个问题——封装。他们会花大量的精力在面向对象的经典问题之一上面，即如何封装自己的代码，以便与类库使用者的代码分离。

除了SVG，现在的Web平台只提供了一种原生的方法去隔离代码块，这并不优雅。没错，我说的就是iframe。对大部分需要封装的场景来说，frames太重而且限制太多。

如果我需要把每个自定义的按钮都放到iframe里，你是什么感觉，会不会疯掉？

所以，我们需要一些更好的东西。事实上，大部分的浏览器已经变相地提供了一种强大技术去隐藏一些实现细节。这个技术就是所谓的“shadow DOM”。

我的名字是DOM，Shadow DOM
Shadow DOM是指浏览器的一种能力，它允许在文档（document）渲染时插入一棵DOM元素子树，但是这棵子树不在主DOM树中。

[[译]什么是Shadow Dom？](http://www.toobug.net/article/what_is_shadow_dom.html)
[[译]Shadow DOM第一课](http://www.toobug.net/article/shadow_dom_101.html)
[[译]Shadow DOM第二课](http://www.toobug.net/article/shadow_dom_201.html)
[[译]Shadow DOM第三课](http://www.toobug.net/article/shadow_dom_301.html)