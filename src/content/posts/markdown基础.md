---
title: markdown基础
published: 2025-12-31
mood: excellent
description: '这是关于我的markdown学习内容'
tags: [Markdown,Study]
category: 'Study Notes'
---
# markdown学习

## 标题

```
# 一级标题（这是一级标题）
## 二级标题（这是二级标题）
```

## 效果

# 1.一级标题

## 二级标题

快捷键

```
选择按住CTRL加1~6赋予几级标题
按住ctrl加0就是普通文本
按住ctrl加+/-号可以加减标题级别
```

# 2.段落

### 换行

```
这是1段落
这是2段落（按住enter）（按住shift加enter）
```

效果

这是1段落

这是2段落

----

这是1段落
这是2段落

### 分割线

```
---加空格，或者***加空格
或者```和***
```



效果

---

***

# 3.字体显示

## 字体

```
**这是粗体**
*这是斜体*
==这是高亮==
<u>这是下划线</u>
~~这是删除线~~
```

**这是粗体**
*这是斜体*
==这是高亮==
<u>这是下划线</u>
~~这是删除线~~

快捷键

**粗体**：**ctrl+b**
*斜体*：*ctrl+I*
<u>下划线</u>：<u>ctrl+u</u>
~~删除线~~：~~shift+alt+5~~

## 上下标



```
上标：X^2^(x<sup>2</sup>)
下表：H~2~O(H<sub>2</sub>)
```

效果

x<sup>2</sup>
H<sub>2</sub>O

# 4.列表

## 无序列表

```
*/-/+加空格（按两次空格退出列表状态）
```

效果

+ 苹果
+ 菠萝
+ 梨子

```
分类增加按tab（退出enter反复按）
```

- 一级分类别
    - 二级分类
        - 三级分类

快捷键

ctrl+[或]

## 有序列表

```
数字.加空格
```

效果：

1. 苹果
2. 菠萝
3. 草莓

## 任务列表

```
- [ ] A(-空格[空格]空格)
- [x] B
```

效果：

- [ ] A

- [x] B

#  5.区块显示

```
>加enter
```

效果：

>1
>
>>2
>
>>> 3

# 6.代码显示

## 行内代码

```
`print("nihao")`(是`号)
```

`print("nihao")`

`快捷键`：`ctrl加shift加`

## 代码块

````
```python
```
````

效果：

```python
```

快捷键:ctrl加shift加k

# 7.链接

```
www.baidu.com
[百度](https://www.baidu.com)
[百度](https://www.baidu.com "https://www.baidu.com")
```

效果：

www.baidu.com
[百度](www.baidu.com)
[百度](www.baidu.com "wwww.baidu.com")

快捷键：CTRL加k

```
标题跳转：[标题](# 1.一级标题)
```

[标题](# 1.一级标题)

# 8.脚注

```
文本[^1]
[^1]
```

文本[^1]
[^1]:这是对文本的解释第一行<br>这是第二行

文本2[^2]

# 9.插入图片

```
![图片说明](图片链接 "图片标题")
比如![插入图片](D:\zcw\OneDrive\Desktop\new_study\markdown\markdown学习\屏幕截图 2025-12-28 162014.png"图片标题")
```

![插入图片](D:\zcw\OneDrive\Desktop\new_study\markdown\markdown学习\屏幕截图 2025-12-28 162014.png"图片标题")

快捷键：CTRL加shift加i

<img src="./屏幕截图 2025-12-28 162014.png"  />

# 10.表格

```
|  1   |  2   |  3   |
| :--- | :--: | ---: |
|  4   |  5   |  6   |
|  7   |  8   |  9   |
|  10  |  11  |  12  |
```

效果

| 1    |  2   |    3 |
| :--- | :--: | ---: |
| 4    |  5   |    6 |
| 7    |  8   |    9 |
| 10   |  11  |   12 |

快捷键：CTRL加T

(大纲在最前边输出[TOC])

:::note
Highlights information that users should take into account, even when skimming.
:::