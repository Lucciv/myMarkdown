# Sublime Text Snippets

## Table

| tabTrigger | File Path ( .sublime-snippet ) | HTML/CSS | Functional Description |
| :--------- | :------------------ | ---------------------- | ---------- |
| aa         | H001-aPlus | HTML | <a> Plus |
| pp         | H002-pPlus | HTML | <p> Plus |
| ss | H003-spanPlus | HTML | <span> Plus |
| ai | H004-ImageLink | HTML | Create Image Link |
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
| shai/scai | 001-HTML/CSS-gov_ImageLinkBox | HTML/CSS | Work Model - Image Link Box |
| sh/sc | 002-HTML/CSS-gov_ | HTML/CSS | Work Model - |
| shlist/sclist | 003-HTML/CSS-gov_ListBox | HTML/CSS | Work Model - List Box |
| shtablist/sctablist | 004-HTML/CSS-gov_TabListBox | HTML/CSS | Work Model - Tab List Box |
| shtitle/sctitle | 005-HTML/CSS-gov_TitleBox | HTML/CSS | Work Model - Title Box |
| shtitlepic/sctitlepic | 006-HTML/CSS-gov_TitleBox_withPic | HTML/CSS | Work Model - Title Box with Pic |
| sh/sc | 00-HTML/CSS-gov_ | HTML/CSS | Work Model - |
|  |  |  |  |

[TOC]

## How do I use

> **IMPORTANT**: If you are also using *Emmet*, add the following to *Emmet*'s user settings file:
>
> ```
> "disabled_single_snippets": "fig meta nav ol script style ul"
> ```

![](https://s1.ax1x.com/2018/09/14/iEJ236.gif)

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

2. Folder location for saving **snippet files** : 
   1. Win : `C:\Users\Administrator\AppData\Roaming\Sublime Text 3\Packages\User\SnippetFolder`
   2. Mac : ``
3. Filename Extension : `.sublime-snippet`;
4. In HTML **Snippet File**, Revise `scope` code : `<scope>text.html</scope>`;
5. In CSS **Snippet File**, Revise `scope` code : `<scope>source.css</scope>`;
6. In HTML File, Input <tabTrigger> and press `Tab`; 
7. In CSS File, **Must** press `.` before input <tabTrigger> and press `Tab`;

## HTML

### H001-aPlus

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

### H002-pPlus

```xml
<snippet>
	<content><![CDATA[
<p class="${1}">${2}</p>
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>pp</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>text.html</scope>
</snippet>
```

### H003-spanPlus

```xml
<snippet>
	<content><![CDATA[
<span class="${1}">${2}</span>
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ss</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>text.html</scope>
</snippet>
```

## CSS

### C001-width and height

```xml
<snippet>
	<content><![CDATA[
width: ${1:0}px;height: ${2:0}px;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccwh</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C002-absolute_top_left

```xml
<snippet>
	<content><![CDATA[
position: absolute;top: ${1:0}px;left: ${2:0}px;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccabstl</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C003-absolute_top_right

```xml
<snippet>
	<content><![CDATA[
position: absolute;top: ${1:0}px;right: ${2:0}px;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccabstr</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C004-absolute_bottom_left

```xml
<snippet>
	<content><![CDATA[
position: absolute;bottom: ${1:0}px;left: ${2:0}px;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccabsbl</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C005-absolute_bottom_right

```xml
<snippet>
	<content><![CDATA[
position: absolute;bottom: ${1:0}px;right: ${2:0}px;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccabsbr</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C006-background_color

```xml
<snippet>
	<content><![CDATA[
background-color: #${1};
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccbc</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C007-background_image

```xml
<snippet>
	<content><![CDATA[
background: url(../images/${1}) no-repeat;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccbi</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C008-border

```xml
<snippet>
	<content><![CDATA[
border:${1:1}px solid #${2:000};
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccbr</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C009-fontsize_color

```xml
<snippet>
	<content><![CDATA[
font-size: ${1:16}px; color: #${2:000};
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccfc</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C010-height and lineheight

```xml
<snippet>
<content>
	<![CDATA[line-height: ${1:N1}px; height: ${1:N1}px;]]>
</content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>cclh</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C011-padding_top

```xml
<snippet>
	<content><![CDATA[
padding-top: 30px;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccpt</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C012-bc_skyblue

```xml
<snippet>
	<content><![CDATA[
background-color: skyblue;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccbk</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C013-width100 and overflow

```xml
<snippet>
	<content><![CDATA[
width: 100%;overflow: hidden;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccwo</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### C014-width100

```xml
<snippet>
	<content><![CDATA[
width: 100%;
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ccwb</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

## JavaScript

## Work Model

### Image Link Box

#### Syntax_html

```xml
<snippet>
	<content><![CDATA[
<a href="#" target="_blank" class="${1:gov}_imgLinkBox"><img src="static/images/${2}" alt=""></a>
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>ai</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>text.html</scope>
</snippet>
```

#### Syntax_css

```xml
<snippet>
	<content><![CDATA[
${1:gov}_imgLinkBox img { display: block; margin: ${2:30}px auto; border: ${3:1}px solid #${4:000};${5:background-color: skyblue;} }
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>scai</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### List Box

#### Syntax_html

```xml
<snippet>
  <content><![CDATA[
<!-- GovList -->
<ul class="${1:gov}_list_box">
  <li>
    ${2:<span class="${1:gov}_list_dot"></span>}
    <a href="#" target="_blank">标题标题标题标题...</a>
    ${3:<span class="${1:gov}_list_time">2017-09-09</span>}
  </li>
  <li>
    ${2:<span class="${1:gov}_list_dot"></span>}
    <a href="#" target="_blank">标题标题标题标题...</a>
    ${3:<span class="${1:gov}_list_time">2017-09-09</span>}
  </li>
  <li>
    ${2:<span class="${1:gov}_list_dot"></span>}
    <a href="#" target="_blank">标题标题标题标题...</a>
    ${3:<span class="${1:gov}_list_time">2017-09-09</span>}
  </li>
</ul>
<!-- END GovList -->
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>shlist</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <scope>text.html</scope>
</snippet>
```

#### Syntax_css

```xml
<snippet>
	<content><![CDATA[
/*Tab ListBox*/
.${1:gov}_tablistbox { overflow: hidden; width: 100%; }
.${1:gov}_tablistline { position: relative; display: block; width: 100%; height: ${3:24}px; line-height: ${3:24}px; padding-left: ${1:26}px; }
.${1:gov}_tablistdot { position: absolute; top: ${6:12}px; left: ${7:14}px; display: block; width: ${4:3}px; height: ${4:3}px; background-color: #${5:666}; }
.${1:gov}_tablisttime, .${1:gov}_tablisttext { ${8:font-size: ${9:12}px;} ${10:color: #${11:000};} }
.${1:gov}_tablisttext:hover { ${14:text-decoration: underline;} ${12:color: #${13:666};} }
/*END Tab ListBox*/
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>sctablist</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

### Tab List Box

#### Syntax_html

```xml
<snippet>
	<content><![CDATA[
<!-- Tab ListBox -->
<div class="${1:gov}_tablistbox">
  <div class="${1:gov}_tablistline">
    <a href="#" target="_blank">
      ${2:<span class="${1:gov}_tablistdot"></span>}
      <span class="${1:gov}_tablisttext">标题标题标题...</span>
    </a>
    ${3:<span class="${1:gov}_tablisttime">2018-09-09</span>}
  </div>
  <div class="${1:gov}_tablistline">
    <a href="#" target="_blank">
      ${2:<span class="${1:gov}_tablistdot"></span>}
      <span class="${1:gov}_tablisttext">标题标题标题...</span>
    </a>
    ${3:<span class="${1:gov}_tablisttime">2018-09-09</span>}
  </div>
  <div class="${1:gov}_tablistline">
    <a href="#" target="_blank">
      ${2:<span class="${1:gov}_tablistdot"></span>}
      <span class="${1:gov}_tablisttext">标题标题标题...</span>
    </a>
    ${3:<span class="${1:gov}_tablisttime">2018-09-09</span>}
  </div>
</div>
<!-- Tab ListBox END -->
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>shtablist</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>text.html</scope>
</snippet>
```

#### Syntax_css

```xml
<snippet>
	<content><![CDATA[
/*Tab ListBox*/
.${1:gov}_tablistbox { overflow: hidden; width: 100%; }
.${1:gov}_tablistline { position: relative; display: block; width: 100%; height: ${3:24}px; line-height: ${3:24}px; padding-left: ${1:26}px; }
.${1:gov}_tablistdot { position: absolute; top: ${6:12}px; left: ${7:14}px; display: block; width: ${4:3}px; height: ${4:3}px; background-color: #${5:666}; }
.${1:gov}_tablisttime, .${1:gov}_tablisttext { ${8:font-size: ${9:12}px;} ${10:color: #${11:000};} }
.${1:gov}_tablisttext:hover { ${14:text-decoration: underline;} ${12:color: #${13:666};} }
/*END Tab ListBox*/
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	<tabTrigger>sctablist</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	<scope>source.css</scope>
</snippet>
```

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

