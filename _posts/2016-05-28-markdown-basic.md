---
layout:      post
title:       MarkDown基本语法
tags: markdown
---

# MarkDown基本语法
记录一下 MarkDown 的基本语法，以便平时查看。
### 标题
\# 一级标题  
\## 二级标题  
\### 三级标题  
\#### 四级标题  
\##### 五级标题  
\###### 六级标题

### 换行
1. 在当前行的结尾添加 2 个空格即可
2. 在当前行的结尾添加 `<br>`或`<br/>`

### 粗斜体
`*斜体文本*` 或  `_斜体文本_`,( *斜体文本* )  
`**粗体文本**` 或 `__粗体文本__`,( **粗体文本** )  
`***粗斜体文本***` 或 `___粗斜体文本___`,( ***粗斜体文本*** )

### 分隔符

在需要分割的地方输入 3 个减号: `-` ,当前后都有段落是请空一行后输入

---

### 列表
1. 普通无序列表
>列表文本前输入`[减号+空格]`  
>列表文本前输入`[加号+空格]`  
>列表文本前输入`[星号+空格]`
2. 普通有序列表
> 列表文本前输入 `[数字+空格]`  
> `1. 列表文本`

### 引用
在引用文本前输入`>`,引用可以嵌套,多一个`>`就多一层嵌套.

### 代码
使用` ```(键盘Tab键上的键) `包裹一段代码,支持多种语法高亮.  
>` ```python`  
def hello():  
print 'Hello World'  
` ``` `
```python
def hello():
  print 'Hello World'
```

### 行内HTML元素
支持的 HTML 元素有`<kdb> <b> <i> <em> <sup> <br>`  
键位显示为`<kdb>`,如 `<kdb>Ctrl<kdb>` <kdb>Ctrl<kdb>

### 链接
1. 文字链接 `[链接名称](链接网址URL) 如:[Google](https://www.google.com)` [Google](https://www.google.com)  
2. 网址链接 `<网址链接> 如:<https://www.google.com>` <https://www.google.com>  
3. 图片链接 `![图片名称](图片的URL) 如:![Google](http://www.google.com/logo.png)` ![Google](http://www.google.com/logo.png)
>***使用技巧*** :  
可以将一个网址声明为变量,并在文档结尾给变量赋值.  
`[Google][g] 网址变量为g`  
在文档结尾赋值`[g]: https://www.google.com`
