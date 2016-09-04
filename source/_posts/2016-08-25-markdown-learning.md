---
title: markdown-learning
date: 2016-08-25 21:01:23
categories: base
tags: 
 - base
 - markdown
comments: false
---
Markdown学习笔记
===============
Markdown的官方网站：http://daringfireball.net/projects/markdown/

<!--more-->

# 标题
在段落面前加1~6个\#号即为对应级别的标题

>\#一级标题
>\## 二级标题
>\### 三级标题

# 强调
使用\*\\\_包含文本表示强调， 分别对于HTML标签中的\<em\>和\<strong\>标签
>*这里强调*
>**这里强调**
>_这里强调_
>__这里强调__

# 列表
使用\*\+\-或1.表示无序列表和有序列表

有序列表
1. 一
2. 二
3. 三

无序列表
+ 一
+ 二
+ 三

# 链接
使用\[links\]\(url\)表示超链接
点[这里](http://daringfireball.net/projects/markdown/syntax)链接到MarkDown官网

# 图片
使用!\[links\]\(url\)表示链接到图片
![皮卡皮卡](http://www.golue.com/uploads/allimg/201012/14225Q942-31.jpg)
# 代码
使用\`\`\`包含代码片段即可
```
let input = item => item + 1;
```
# 引用
使用\>\+文本表示引用
本文示例参考至
>http://daringfireball.net/projects/markdown/syntax#list

# 表格
<pre>
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
</pre>

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

# 字符转义
以下字符需要使用\\转义, 或使用html转义字符
>\   反斜线
>\`   反引号
>\*   星号
>_   底线
>{}  花括号
>[]  方括号
>()  括弧
>\#   井字号
>\+   加号
>\-   减号
>\.   英文句点
>!   惊叹号
