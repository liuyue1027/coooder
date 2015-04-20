title: "CSS使用::selection改变选中文本样式"
date: 2015-04-20 11:05:51
categories:
- 雕虫小技
tags:
- CSS3
---
![::selection](/images/articles/selection.png)

#### 例：

``` css
::selection{
    background: green;
}

::-moz-selection{
    background: green;
}
```
####浏览器支持:

IE9+、Opera、Google Chrome 以及 Safari 中支持 ::selection 选择器。

Firefox 支持替代的 ::-moz-selection。

####可用CSS属性：

color、background、cursor 、outline。
