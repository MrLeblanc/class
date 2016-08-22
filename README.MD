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

## $

## .attr

* .attr() 方法设置或返回被选元素的属性值

## .index()

## .click()

## .mouseover() .mouseout()  ?  .mouseenter() .mouseleave()

## .siblings()

## .addClass() .removeClass()

## .eq()

## 复习
1. $("选择器")  可以获取节点
2. 获取节点的方法：eq find siblings
3. 获取索引值:index
4. 获取属性的方法：attr css
5. 添加和删除样式：addClass removeClass
6. 事件：click mouseenter mouseleave mouseover mouseout
7. mouseenter mouseover区别？

## DOM

![DOM](http://www.w3school.com.cn/i/ct_htmltree.gif)

* DOM中的树状结构：节点：元素节点，文本节点，属性节点

## 事件委托，事件捕获，事件冒泡

### JavaScript中事件传播过程：

#### 事件的处理流成分为三阶段：

1. 事件捕获阶段：当某个元素触发某个事件时，首先会触发根元素document，然后事件将沿着dom树向下传播给目标节点的每一个祖先节点，直到目标节点。

2. 目标阶段：到达目标元素之后，执行目标元素的事件处理函数

3. 事件冒泡阶段：从目标元素开时，事件将沿着DOM树向上传播，直到根节点。

![DOM](http://images2015.cnblogs.com/blog/324770/201606/324770-20160630170126421-1509815715.jpg)


### 事件委托就是利用事件冒泡原理，把处理任务委托给父元素或者祖先元素（通常用父元素），我们通过目标对象来判断事件源，并执行事件处理。

### 事件委托带来的优点：

1. 不需要为每一个元素都添加监听事件而是通过委托给父元素来处理。这样就减少了内存，性能提高了

2. 可以方便动态添加元素。不需要再为新添加的元素重新绑定事件。
