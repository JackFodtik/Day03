# Day03
Flex 布局

### 一、代码编辑器——VSCode

#### 1、为什么选择VSCode?

市面上有很多非常优秀的编辑器，例如 sublime、notpad++、vim，每一种编辑器都有自身的特点，所以我们选用哪种编辑器，完全可以结合自己的实际情况选择。我推荐你现在开始使用 Visual Studio Code，简称 VScode 。

> **VScode 几大特点：**
> 
> * 跨平台，支持 Windows 7/8/10、Linux、MacOS
> * 支持 JavaScript、C#、C++、Python、PHP、Markdown等多种编程语言
> * 支持语法高亮、智能代码补全、代码片段、代码对比等等
> * 支持 Git 版本管理
> * 支持并排编辑
> * 支持代码调试
> * 支持第三方扩展

Visual Studio Code 官网：https://code.visualstudio.com/

#### 2、VScode安装

开始使用 VScode 之前，当然是先进行安装。VScode 支持 Windows、Linux、MAC 三大主流操作系统，[下载安装包](https://code.visualstudio.com/)（网速慢的同学请移步[国内镜像](https://pan.baidu.com/s/1n3sKsIeI4-7CbU_LRasd_A)，提取码：ib3r ）建议下载VScode stable版本！

> **stable版本和insiders版本有什么区别？**
> 
> 区别就是，蓝色的vscode stable是非常稳定的发行版本，绿色的vscode insiders版本相当于测试版，其中可能会有一些bug存在，使用的过程中需要小心一些。


#### 3、VScode扩展

扩展功能让 VScode 变得非常强大，比如通过扩展添加支持的语言等功能。VScode官网有一个[扩展市场](https://marketplace.visualstudio.com/vscode)，当然我们也可以通过VScode编辑器直接搜索我们想要的扩展。

> 安装扩展：只需要点击扩展的安装按钮，然后启用扩展重启vscode，扩展即可以安装完毕。
> 
> 搜索扩展：你也可以在扩展功能里的输入栏里输入自己想找的扩展名称，回车之后就会显示你想要查找的扩展。
> 
> 卸载扩展：点击卸载按钮，即可卸载扩展。


### 二、CSS 基础

#### 1、CSS 简介

CSS 是指层叠样式表(Cascading Style Sheets) ，用来定义如何显示 HTML 元素。

样式通常存储在样式表文件中，文件后缀为 .css 。


#### 2、CSS 注释

```
/* 注释内容 */
```

注意：注释不能相互嵌套！

#### 3、使用CSS的三种方式

* 内联样式

> 通过给标签设置 style 属性

* 内部样式

> 通过给 head 标签中的 style 标签来设置

* 外部样式（强烈推荐！）

> 通过 link 标签来引用外部 css 文件


#### 4、CSS 规则

CSS 规则由两个主要的部分构成：选择器，以及一条或多条声明。

* 选择器指明了“样式”的作用对象，也就是“样式”作用于网页中的哪些元素。

* 声明使用花括号 {} 来包围，一条声明是由一个属性和一个值组成，属性和值之间用 : 分隔，多条声明之间用 ; 分开。


#### 5、CSS 选择器

* class 选择器

> class 选择器又称为类选择器，就是给元素加上 class 属性和属性值，然后在选择器用 . 开头进行选择。

> 任何元素都可以设置 class 属性，大小写敏感。

> 可以有多个元素携带同一个class，另外，同一个元素，class 属性可以携带多个类名，用空格隔开，而不是写多个 class 属性和属性值。

### 三、Flex 布局（重点）

#### 怪异模式

box-sizing: content-box;  /* 元素的真实宽度 = width + padding + border */

box-sizing: border-box;   /* padding 和 border的值是包含在width内 */

#### 案例：骰子布局

<img src="https://github.com/ai-course-team/Day03/blob/master/flex.png">


