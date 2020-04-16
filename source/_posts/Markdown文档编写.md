---
title: Markdown文档编写
date: 2020-04-16 10:08:10
tags: hexo
---
Markdown文档的编写规则其实很简单，下面是演示结果：
<!-- more -->
## 标题
在想要设置为标题的文字前面加#（#和内容之前需要空一个空格），Markdown一共支持六级标题，几级标题加几个#。

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

## 段落
Markdown划分段落非常简单，就是在段落前后保留一个空行即可。

就是这么简单！

## 区块引用
>如果我们需要对一段内容进行强调显示时，Markdown提供了一个特殊符号>（>和之前需要空一个空格）用于段落区块引用。
>
>Markdown支持同时强调引用多个段落。

## 超链接
中括号里写显示文字+小括号里写地址；图片超链接在前面加一个！。

[超链接显示文字](https://blog.csdn.net/sanallen/article/details/92081911)

![风景](https://cn.bing.com/images/search?view=detailV2&ccid=%2bUL1ALZq&id=CCE9ACB6D55C92E295D021E67454D4C0586B44E4&thid=OIP.-UL1ALZqQLbVMNynhlNV2QHaE8&mediaurl=http%3a%2f%2fimg17.3lian.com%2fd%2ffile%2f201701%2f23%2f9036cbb567b39115e528f26255ca9601.jpg&exph=800&expw=1200&q=%e5%9b%be%e7%89%87%e5%a4%a7%e5%85%a8%e9%a3%8e%e6%99%af&simid=607999229361784806&selectedIndex=4)

## 无序列表
无序列表使用*、+、-标识，但是一般使用来标识无序列表

*无序列表项
*无序列表项
*无序列表项

Markdown支持多级列表嵌套，但是建议一般不使用超过两级列表，另外建议两级列表从缩进3个空格开始(适用于无序列表)，如下所示：

*无序列表项
	*第二层列表项
	*第二层列表项
*无序列表项
*无序列表项

## 有序列表
有序列表使用数字.标识

1.有序列表项1
2.有序列表项2
3.有序列表项3
4.有序列表项4
	1.有序列表项41
	2.有序列表项42
5.有序列表项5

## 分割线

***

---

## 字体
*这里包含斜体内容*

**这里包含加粗内容**

## 参考文档
[Markdown文档编写指南](https://blog.csdn.net/sanallen/article/details/92081911)