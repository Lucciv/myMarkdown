# Sublime Text Snippets

## Table

| tabTrigger | File Path ( .sublime-snippet ) | HTML/CSS | Functional Description |
| :--------- | :------------------ | ---------------------- | ---------- |
| aa         | H001-aPlus | HTML | <a> Plus |
| pp         | H002-pPlus | HTML | <p> Plus |
| ss | H003-spanPlus | HTML | <span> Plus |
| ccwh | C001-width and height | CSS | Input width and height (px) |
| ccabstl | C002-absolute_top_left | CSS | position: absolute;top: 0px;left: 0px; |
| ccabstr | C003-absolute_top_right | CSS | position: absolute;top: 0px;right: 0px; |
| ccabbl | C004-absolute_bottom_left | CSS | position: absolute;bottom: 0px;left: 0px; |
| ccabbr | C005-absolute_bottom_right | CSS | position: absolute;bottom: 0px;right: 0px; |
| ccbc | C006-background_color | CSS | background-color: #; |
| ccbi | C007-background_image | CSS | background: url(../images/) no-repeat; |
| ccbr | C008-border | CSS | border:1px solid #000; |
| ccfc | C009-fontsize_color | CSS | font-size: 16px; color: #000; |
| cclh | C010-height and lineheight | CSS | line-height: px; height: px; |
| ccpt | C011-padding_top | CSS | padding-top: 30px; |
| ccbk | C012-bc_skyblue | CSS | background-color: skyblue; |
| ccwo | C013-width100 and overflow | CSS | width: 100%;overflow: hidden; |
| ccwb | C014-width100 | CSS | width: 100%; |
| shtitle | 004-HTML/CSS-gov_TitleBox | HTML/CSS | Work Model - Title Box |
| shtitlepic | 005-HTML/CSS-gov_TitleBox_withPic | HTML/CSS | Work Model - Title Box with Pic |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

[TOC]

## How do I use

> **IMPORTANT**: If you are also using *Emmet*, add the following to *Emmet*'s user settings file:
>
> ```
> "disabled_single_snippets": "fig meta nav ol script style ul"
> ```

1. `Sublime Text` - `Menu` - `Tool` - `Developer` - `New Snippet` , eg : 

```xml
<snippet>
	<content><![CDATA[
Hello, ${1:this} is a ${2:snippet}.
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>hello</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.python</scope>
</snippet>
```

2. In HTML File, Input <tabTrigger> and press `Tab` ;
3. In CSS File, **Must** press `.` before input <tabTrigger> and press `Tab` .

## HTML

### Input HTML <a> Tag

```xml
<snippet>
	<content><![CDATA[
<a href="#" target="_blank" class="${1}">${2}</a>
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>aa</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>text.html</scope>
</snippet>
```

## CSS

## JavaScript

## Work Model

### Title Box

#### Syntax_html

```xml
<snippet>
  <content><![CDATA[
<!-- TitleBox -->
<div class="${1:gov}_title_box">
  <p class="${1:gov}_title_text">${2:标题}</p>
  <a href="#" target="_blank" class="${1:gov}_title_more">更多</a>
</div>
<!-- END TitleBox -->
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>shtitle</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <scope>text.html</scope>
</snippet>
```

#### Syntax_css

```xml
<snippet>
	<content><![CDATA[
/*== Title Box ==*/
.${1:gov}_title_box { position: relative; overflow: hidden; width: 100%; height: ${2:40}px; ${12:border-bottom: ${13:1}px solid #${14:666};} }
.${1:gov}_title_text { font-size: ${3:18}px; ${6:font-weight: bold;} line-height: ${2:40}px; ${4:color: #${5:666};} }
.${1:gov}_title_box .${1:gov}_title_more { font-size: ${7:14}px; position: absolute; top: ${10:12}px; right: ${11:10}px; ${8:color: #${9:666};} }
/*== END Title Box ==*/
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>sctitle</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### Tile Box with Pic

#### Syntax_html

```xml
<snippet>
  <content><![CDATA[
<!-- TitleBox -->
<div class="${1:gov}_title_box">
  <table cellspacing="0" class="${1:gov}_title_textbox">
  	<tr>
  		<td class="${1:gov}_title_lefthorn"></td>
  		<td class="${1:gov}_title_ttext">${2:标题标题}</td>
  		<td class="${1:gov}_title_righthorn"></td>
  	</tr>
  </table>
  <a href="#" target="_blank" class="${1:gov}_title_more">更多</a>
</div>
<!-- END TitleBox -->
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>shtitlepic</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <scope>text.html</scope>
</snippet>
```

#### Syntax_css

```xml
<snippet>
	<content><![CDATA[
/*== Title Box with Pic ==*/
.${1:gov}_title_box { position: relative; overflow: hidden; width: 100%; height: ${2:40}px; ${12:border-bottom: ${13:1}px solid #${14:666};} }
.${1:gov}_title_box .${1:gov}_title_more { font-size: 14px; position: absolute; top: 12px; right: 10px; color: #666; }
.${1:gov}_title_ttext { font-size: ${3:18}px; ${7:font-weight: bold;} line-height: ${2:40}px; color: #${4:666}; ${5:background-color: #${6:000};} }
.${1:gov}_title_lefthorn,
.${1:gov}_title_righthorn { width: ${8:10}px; height: ${9:40}px; margin: 0; padding: 0; background: url(../images/${10:title_bg_horn_left.png}) no-repeat; }
.${1:gov}_title_righthorn { background: url(../images/${11:title_bg_horn_right.png}) no-repeat; }
/*== END Title Box with Pic ==*/
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>sctitlepic</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

