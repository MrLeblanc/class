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

### 背景属性
* background	简写属性，作用是将背景属性设置在一个声明中。
* background-color	设置元素的背景颜色。
* background-image	把图像设置为背景。
* background-position	设置背景图像的起始位置。
* background-repeat	设置背景图像是否及如何重复。

### 文本属性

* color	设置文本颜色
* line-height	设置行高。
* letter-spacing	设置字符间距。
* text-align	对齐元素中的文本。
* text-indent	缩进元素中文本的首行。

### 字体属性

* font-family	设置字体系列。
* font-size	设置字体的尺寸。
* font-weight	设置字体的粗细。

### a链接

* a:link - 普通的、未被访问的链接
* a:visited - 用户已访问的链接
* a:hover - 鼠标指针位于链接的上方
* a:active - 链接被点击的时刻


### 鼠标访问时的样式cursor

* auto	默认。浏览器设置的光标。
* crosshair	光标呈现为十字线。
* pointer	光标呈现为指示链接的指针（一只手）
* move	此光标指示某对象可被移动。
* e-resize	此光标指示矩形框的边缘可被向右（东）移动。
* ne-resize	此光标指示矩形框的边缘可被向上及向右移动（北/东）。
* nw-resize	此光标指示矩形框的边缘可被向上及向左移动（北/西）。
* n-resize	此光标指示矩形框的边缘可被向上（北）移动。
* se-resize	此光标指示矩形框的边缘可被向下及向右移动（南/东）。
* sw-resize	此光标指示矩形框的边缘可被向下及向左移动（南/西）。
* s-resize	此光标指示矩形框的边缘可被向下移动（南）。
* w-resize	此光标指示矩形框的边缘可被向左移动（西）。
* text	此光标指示文本。
* wait	此光标指示程序正忙（通常是一只表或沙漏）。
* help	此光标指示可用的帮助（通常是一个问号或一个气球）。

### 列表属性

list-style

### css框模型（盒模型）

![](http://www.w3school.com.cn/i/ct_boxmodel.gif)

### 边框

border

### 外边距合并

![](http://www.w3school.com.cn/i/ct_css_margin_collapsing_example_1.gif)

### 解决float问题

![](http://www.w3school.com.cn/i/ct_css_positioning_floating_clear_div.gif)

### 选择器
* 元素选择器
类选择器
ID选择器
选择器组
后代选择器
子元素选择器 >
相邻兄弟选择器 ＋

### 居中

### 元素属性

### 透明度opacity

### select option   

### textarea





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


## 数学对象

* Math.floor(number)  舍弃小数点后面的数字取整数

* Math.ceil(number)  进位取整数

* Math.random()  返回一个随机浮点数(小于1大于零的随机小数)

## 数组

```js
  var X = ["x","xx","xxx","xxxx"...]
  X[n]
  X.length;
  X.push
```


## for循环遍历数组

```js
  for(var i = 0;i < xx;i++){}
```

## 形参，实参

## switch

```js
  switch(n){
    case "x": ............;break;
    ......
  }
```

## window对象

* alert
* confirm
* prompt

## 获取节点

* document.getElementsById("")
* document.getElementsByClassName("") 需要用for循环遍历才可选中需要的节点
* document.getElementsByTagName("") 需要用for循环遍历才可选中需要的节点

## 添加节点

* document.creatElement("") 添加一个对象
* document.creatTextNode("") 添加一个文本的内容
* event.target 获取当前选中的节点
* removeChild
* parentNode

## 事件

* addEventListener("事件",function(){},false);

## 数组的方法

* .split("x") 将字符串以x为分割点分割为一个数组

## 函数

* arguments
* prototype  像对象添加属性和方法




![](http://img.mukewang.com/53e198540001b66404860353.jpg)
![](http://img.mukewang.com/532fe7cf0001e7b505170269.jpg)
![](http://img.mukewang.com/532fe841000174db05160622.jpg)
![](http://img.mukewang.com/533295ab0001dead05190599.jpg)
