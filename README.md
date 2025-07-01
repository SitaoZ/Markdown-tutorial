# Markdown-tutorial
Markdown 是一种轻量级的标记语言，排版语法简洁，可以HTML混编，转化成HTNL、PDF和.md文件。
语法简洁，只需要记住相应的标记符号即可。

## 标题符号
段落使用#标记，注意#和标题之间需要空格，增加拓展性，适用于不同markdown编辑器。
```bash
# 一级标题
## 二级标题
### 三级标题
```
## 段落标记
创建段落使用空白行将文本分隔，不需要使用空格和制表符缩进段落。  

## 换行语法
在一行文本的末尾添加两个或者多个空格，然后按回车键，即可创建一个换行符号`(<br>)`  
注意，很多编辑器都支持两个或者多个空格换行，虽然可视化差，但是比较实用。  

## 强调语法
将文本加粗或者斜体来强调重要性.  
**加粗**，在文本前后添加两个星号(asterisks)或者下划线(underscores)，不需要空格。

**斜体**，在文本前后添加一个星号或者一个下划线。
***同时加粗和斜体***，使用三个星号和下划线

注意：如在单词中间，不要使用下划线，需要使用星号。

## 引用语法
使用>在段落前，即可创建引用
**嵌套块引用**，在要嵌套的段落前添加一个>>符号

## 列表语法

**有序列表**
要创建有序列表，使用数字紧跟一个英文句点即可。数字不必按照数学顺序排列，但是列表应该以数字1起始。  
**无序列表**
创建无序列表，使用-, *, +号实现。使用缩进创建嵌套列表。


## 代码块语法
使用反引号``创建。

## 分割线语法

创建分割线，在单独的一行或者使用三个或者多个星号(***)，破折号(---)，下划线(___)，且不能包括其他内容。

## 链接语法
链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。
```bash
[超链接显示名](超链接地址)

# 可以给链接增加title，当鼠标悬停在链接上时会出现的文字
[超链接显示名](超链接地址 "超链接title")

```

## 图片语法
```bash
# 格式
![这是图片](/assets/img/philly-magic-garden.jpg "Magic Gardens")
```

## 转义字符语法
在原本用于格式化的字符前面添加反斜杠\，即可显示字符。

```bash
Character	Name
\	        backslash
`	        backtick (see also escaping backticks in code)
*	        asterisk
_	        underscore
{ }	      curly braces
[ ]	      brackets
( )	      parentheses
#	        pound sign
+	        plus sign
-	        minus sign (hyphen)
.	        dot
!	        exclamation mark
|	        pipe
```
## 内嵌HTML语法


## 上下标
- 上标 10<sup>8</sup>
```bash
<sup>8</sub>
```


- 下标 log<sub>2</sub>
```bash
<sub>2</sub>
```

## 特殊符号

- &ge;
- &le;



[markdown](https://markdown.com.cn/basic-syntax/line-breaks.html)
