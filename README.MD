# html标签
* html
* head
* style
* body
* header
* nav
* section
* footer
* h1~h6
* p
* a
* img
* br
* hr







# JavaScript 简介

  JavaScript 是互联网上最流行的脚本语言，这门语言可用于 HTML 和 web，更可广泛用于服务器、PC、笔记本电脑、平板电脑和智能手机等设备。

## JavaScript 是脚本语言

* JavaScript 是一种轻量级的编程语言。
* JavaScript 是可插入 HTML 页面的编程代码。
* JavaScript 插入 HTML 页面后，可由所有的现代浏览器执行。

## 我的第一个js

 ```js
  <script>
      alert("hello JavaScript!")
  </script>
 ```

## what is jQuery?

* jQuery 是一个 JavaScript 库。极大地简化了 JavaScript 编程。

## jQuery库包含以下功能

* HTML 元素选取
* HTML 元素操作
* CSS 操作
* HTML 事件函数
* JavaScript 特效和动画
* HTML DOM 的修改
* AJAX
  等等...

### $()

### .attr

* .attr() 方法设置或返回被选元素的属性值

### .index()

### .click()

### .mouseover() .mouseout()  ?  .mouseenter() .mouseleave()

### .siblings()

### .addClass() .removeClass()

### .eq()

## 复习

1. $("选择器")  可以获取节点
2. 获取节点的方法：eq find siblings
3. 获取索引值:index
4. 获取属性的方法：attr css
5. 添加和删除样式：addClass removeClass
6. 事件：click mouseenter mouseleave mouseover mouseout
7. mouseenter mouseover区别？

## jquery动画方法

#### show hide fadeOut fadeIn slideDown slideUp toggle animate

#### stop()

### remove() 方法移除被选元素，包括所有的文本和子节点。

### event.pageX 属性返回鼠标指针的位置，相对于文档的左边缘。

### event.pageY 属性返回鼠标指针的位置，相对于文档的上边缘。

### text() 方法设置被选元素的文本内容。

### append() 方法在被选元素的结尾（仍然在内部）插入指定内容。

### val()获取value值

### parseInt() 函数可解析一个字符串，并返回一个整数。Number()

### parseFloat() 函数可解析一个字符串，并返回一个浮点数。

## if语句

  * if 语句
    只有当指定条件为 true 时，该语句才会执行代码。

```js
if (条件)
  {
  只有当条件为 true 时执行的代码
  }
```

## Date 日期对象：内置对象

### Date是构造函数：构造函数可以通过new来创建对象

### setInterval() 方法可按照指定的周期（以毫秒计）来调用函数或计算表达式。

### setInterval() 方法会不停地调用函数，直到 clearInterval() 被调用或窗口被关闭。

### location 对象包含有关当前 URL 的信息。

## DOM

![DOM](http://www.w3school.com.cn/i/ct_htmltree.gif)

* DOM中的树状结构：节点：元素节点，文本节点，属性节点



### 事件委托就是利用事件冒泡原理，把处理任务委托给父元素或者祖先元素（通常用父元素），我们通过目标对象来判断事件源，并执行事件处理。

### 事件委托带来的优点：

1. 不需要为每一个元素都添加监听事件而是通过委托给父元素来处理。这样就减少了内存，性能提高了

2. 可以方便动态添加元素。不需要再为新添加的元素重新绑定事件。

### jQuery中将事件委托给父级元素的方法.parent()

### scrollTop() 方法返回或设置匹配元素的滚动条的垂直位置。

### offset() 方法返回或设置匹配元素相对于文档的偏移（位置）。




## 事件捕获，事件冒泡

### JavaScript中事件传播过程：

#### 事件的处理流成分为三阶段：

1. 事件捕获阶段：当某个元素触发某个事件时，首先会触发根元素document，然后事件将沿着dom树向下传播给目标节点的每一个祖先节点，直到目标节点。

2. 目标阶段：到达目标元素之后，执行目标元素的事件处理函数

3. 事件冒泡阶段：从目标元素开时，事件将沿着DOM树向上传播，直到根节点。

![DOM](http://images2015.cnblogs.com/blog/324770/201606/324770-20160630170126421-1509815715.jpg)







1. HTML 元素
2. jQuery 对象
3. DOM 元素



## 变量

### 变量命名规则

1. 必须以字母、下划线或美元符号开头，后面可以跟字母、下划线、美元符号和数字。

2. 变量名区分大小写，如:A与a是两个不同变量。

3. 不允许使用JavaScript关键字和保留字做变量名。

![关键字和保留字](http://img.mukewang.com/529c07c000014f5103080447.jpg)

## 数据类型

* 字符串、数字、布尔、数组、对象、Null、Undefined





## for循环

```js
  for(var i = 0;i < xx;i++){}
```
