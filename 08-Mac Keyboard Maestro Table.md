# Keyboard Maestro Table

## 00_Quick AppliCations

|   Applications   |  快捷键   |    功能     |
| :--------------: | :-------: | :---------: |
|   QuickOpenApp   | ⌘ + ⇧ + 0 | 打开App面板 |
|      iTerm       |     1     |             |
|      WeChat      |     2     |             |
|      Trello      |     3     |             |
|    YoudaoNote    |     4     |             |
|     Evernote     |     5     |             |
| Keyboard Maestro |     6     |             |
|     BaiduYun     |     7     |             |
|      XunLei      |     8     |             |
|      Chrome      |     9     |             |

## 01_Folders

|   Applications   |    快捷键    |                     功能                     |
| :--------------: | :----------: | :------------------------------------------: |
| Finder Palettle  | ⌘ + ⇧ + ⌥ +1 |                打开Finder面板                |
| Activate_Finder | 1 |打开Finder主文件夹|
| Learn_JavaScript |      2      |       Git文件夹 / JavaScript文件夹       |
| Writing_Markdown |      3      |                Markdown文件夹                |
|    Watch_Film    |      4      | 下载文件夹 / 电影文件夹 |
|    Watch_Pic     |      5      |          JieTu文件夹 / 图片文件夹           |
| Reading |      6      | iBook文件夹 / LearnBook文件夹 |
| Work |      7      | myWork文件夹 |
| OpenDownloads |      8      | Downloads文件夹 |
| Open_aPic |      9      | MacV文件夹 |

## 02_Bookmark

|  Applications   |    快捷键    |                             功能                             |
| :-------------: | :----------: | :----------------------------------------------------------: |
| Chrome Palettle | ⌘ + ⇧ + ⌥ +2 |                        打开Chrome面板                        |
|     GitHub      |      1       |                [GitHub](https://github.com/)                 |
|    Learning     |      2       |          [廖雪峰Web](https://www.liaoxuefeng.com/)           |
|       GTD       |      3       | [番茄土豆](https://pomotodo.com/app/) / [Rescuetime](https://www.rescuetime.com/dashboard) / [WakeTime](https://wakatime.com/dashboard) |
|   Information   |      4       | [少数派](https://sspai.com/) / [cnBeta](https://www.cnbeta.com/) |
|      Books      |      5       | [我的小书屋](http://mebook.cc/) / [豆瓣读书](https://book.douban.com/) / [亚马逊图书](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/b/ref=sa_menu_books_l1?ie=UTF8&node=658390051) |
|      News       |      6       | [网易新闻](https://news.163.com/)/ [百度新闻](http://news.baidu.com/) |
|       IT        |      7       | [StackOverflow](https://stackoverflow.com/) / [开源中国](https://www.oschina.net/) |
|       Pic       |      8       | [福利吧](http://fuliba.net/) / [游民星空](http://www.gamersky.com/) / [鼠绘漫画](http://www.ishuhui.com/) |
|    书签_电影    |      9       | [胖鸟](http://www.pniao.com/) / [豆瓣电影](https://movie.douban.com/) / [时光网](http://www.mtime.com/) |
|       DD        |      0       |                           ZZ / TT                            |

## 03_Common Operation

|  Applications   |    快捷键    |              功能              |
| :-------------: | :----------: | :----------------------------: |
| CommonOperation | ⌘ + ⇧ + ⌥ +3 |           打开CO面板           |
|   SearchBaiDu   |      1       |            搜索百度            |
|   SearchBook    |      2       |            搜索书名            |
|  SearchEnglish  |      3       |             查词典             |
|    MoveFilm     |      4       |        复制到电影文件夹        |
|     MoveDD      |      5       |         复制到DD文件夹         |
|     UPMove      |      6       | 从优盘里的电影复制到电影文件夹 |
|   CleanRepeat   |      7       |         匹配去重复文件         |

思路-搜索百度：

1. 复制；
2. 打开`Alfred 3`；
3. 输入`bd`；
4. 按空格键；
5. 粘贴；
6. Enter。

思路-搜索书名：

1. 复制；
2. 打开`Alfred 3`；
3. 输入`dbr`；
4. 按空格键；
5. 粘贴；
6. Enter。

思路-查词典：

1. 复制；
2. 打开`Alfred 3`；
3. 输入`ii`；
4. 按空格键；
5. 粘贴；
6. Enter。

思路-MoveFilm：

1. 打开`Downloads`文件夹；
2. 复制；
3. 打开`Movies`文件夹；
4. 剪贴。

思路-MoveDD：

1. 复制（文件名）；
2. 打开DD文件夹；
3. 重名；
4. 粘贴；
5. 打开`Downloads`文件夹；
6. 复制（某个文件）；
7. 打开DD文件夹；
8. 剪贴。

思路-CleanRepeat：

1. 复制（文件名）；
2. 打开指定文件夹；
3. 按`⌘ +R`;
4. 粘贴；
5. 按Esc。

## 04_Git

思路M1：

1. 打开`iTerm2`，并用`Git`同步更新到myMarkdown文件夹；
2. 打开`Typora`并打开myMarkdown文件夹；
3. 复制`Typora`的Markdown笔记，然后复制到有道云笔记，点击同步；
4. 用`Git`上传更新已修改的Markdown笔记。

Push To Markdown Git:

1. 打开`iTerm2`,输入`cd /Users/lucciv/Documents/myGitHub/myMarkdown/`并进入`myMarkdown`文件夹;
2. 输入`git add -A`;
3. 输入`git commit -m "Add Markdown Files"`;
4. 输入`git push -u origin master`;
5. 输入`git status`;
6. 打开GitHub网站。

|          Applications          |    快捷键    | 功能                                    |
| :----------------------------: | :----------: | :-------------------------------------- |
| Open Markdown_Keyboard Maestro | ⌘ + ⇧ + ⌥ +4 | 打开Markdown面板                        |
|       OpenMarkdownNotes        |      1       | 打开Markdown笔记                        |
|       PushToMarkdownGit        |      2       | `Markdown Files`**更新**并**上传**`Git` |
|      PullToMarkdownFiles       |      3       | `Git`**更新**到`Markdown Folder`        |
|          PushToJsGit           |      4       | `Js Files`**更新**并**上传**`Git`       |
|         PullToJsFiles          |      5       | `Git`**更新**到`Js Folder`              |

## 05-Brew

|   Applications   |    快捷键    |     功能     |
| :--------------: | :----------: | :----------: |
|       Brew       | ⌘ + ⇧ + ⌥ +5 | 打开Brew面板 |
|   Brew_Upgrade   |      1       |              |
| BrewCask_Upgrade |      2       |              |
|   Brew_Update    |      3       |              |
|   Mas_Upgrade    |      4       |              |

## 06-Sublime

| Applications  |    快捷键    |      功能       |
| :-----------: | :----------: | :-------------: |
|    Sublime    | ⌘ + ⇧ + ⌥ +6 | 打开Sublime面板 |
| OpenSublimeJs |      1       |        1        |
|               |      2       |                 |
|               |      3       |                 |
|               |      4       |                 |

OpenSublimeJs

思路1：

1. 打开SublimeText App；
2. 把Sublime调窗口4/3；
3. 打开`myJavascriptTest`文件夹；
4. 把那个文件夹调窗口4/1；
5. 拖动文件夹移动到Sublime侧边栏。

思路2：

1. 打开SublimeText App；
2. 按`⌘ +O`打开文件夹；
3. 按`⌘ +f`搜索`myJavascriptTest`文件夹；
4. 按`Return`。