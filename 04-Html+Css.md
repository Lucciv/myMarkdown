# HTML+CSS

[TOC]

## 1. 多行文字垂直居中

`HTML`代码：

```html
<div class="govbox">
  <a class="govGeTx" href="#" target="_blank">
      <span>测试文字测试文字测试文字测试文字测试文字文字测试文字测试</span>
  </a>
</div>
```

 `CSS`代码：

```css
.govGeTx
{
    line-height: 116px;
    display: block;
    width: 440px;
    height: 116px;
    padding: 0 30px;
    text-align: center;
    border-top: 4px solid #decea5;
    background-color: #f0e9d5;
}
.govGeTx span
{
    line-height: 22px;
    display: inline-block;
    vertical-align: middle;
}
```



## 2.列表文字浮动时空白换行的解决方案

`HTML`代码：

```html
<ul class="govMapListBox">
  <li><a href="#" target="_blank" class="govMapText">标题标</a></li>
  <li><a href="#" target="_blank" class="govMapText">标</a></li>
  <li><a href="#" target="_blank" class="govMapText">标题</a></li>
  <li><a href="#" target="_blank" class="govMapText">标</a></li>
  <li><a href="#" target="_blank" class="govMapText">标题</a></li>
  <li><a href="#" target="_blank" class="govMapText">标题标题</a></li>
  <li><a href="#" target="_blank" class="govMapText">标题标题标题</a></li>
  <li><a href="#" target="_blank" class="govMapText">标题标</a></li>
  <li><a href="#" target="_blank" class="govMapText">标题标</a></li>
</ul>
```

 `CSS`代码：

```css
.govMapListBox{width: 100%;overflow: hidden;}
.govMapListBox li{float: left;white-space: nowrap;margin-right: 40px;margin-bottom: 20px;}
```



## 3.CSS不定宽度的块级元素水平居中

`HTML`代码：

```html
<div class="div1">
	<div class="div2">aaa</div>
</div>
```

 `CSS`代码：

```css
.div1{float:left;position:relative;left:50%;}
.div2{position:relative;left:-50%;}
```

