# 《javaScript》的诞生

## 一、javascript是什么

JavaScript（简称“JS”） 是一种具有函数优先的轻量级，解释型或即时编译型的编程语言。虽然它是作为开发Web页面的脚本语言而出名，但是它也被用到了很多非浏览器环境中，JavaScript 基于原型编程、多范式的动态脚本语言，并且支持面向对象、命令式、声明式、函数式编程范式。

## 二、javaScript的历史

* 1994年，网景公司（Netscape）发布了Navigator浏览器0.9版。这是历史上第一个比较成熟的网络浏览器，轰动一时。但是，这个版本的浏览器只能用来浏览，不具备与访问者互动的能力。......网景公司急需一种网页脚本语言，使得浏览器可以与网页互动。
* JavaScript在1995年由Netscape公司的Brendan Eich，在网景导航者浏览器上首次设计实现而成。因为Netscape与Sun合作，Netscape管理层希望它外观看起来像Java，因此取名为JavaScript。但实际上它的语法风格与Self及Scheme较为接近。

* JavaScript最初由Netscape的Brendan Eich设计，最初将其脚本语言命名为LiveScript，后来Netscape在与Sun合作之后将其改名为JavaScript。JavaScript最初受Java启发而开始设计的，目的之一就是“看上去像Java”，因此语法上有类似之处，一些名称和命名规范也借自Java，但JavaScript的主要设计原则源自Self和Scheme。JavaScript与Java名称上的近似，是当时Netscape为了营销考虑与Sun微系统达成协议的结果。微软同时期也推出了JScript来迎战JavaScript的脚本语言。
* 语言组成
  
  1.ECMAScript，描述了该语言的语法和基本对象
  
  2.ECMAScript，描述了该语言的语法和基本对象

  3.浏览器对象模型（BOM），描述与浏览器进行交互的方法和接口。

![javascript的组成](https://bkimg.cdn.bcebos.com/pic/730e0cf3d7ca7bcb3409f115bf096b63f624a89d?x-bce-process=image/resize,m_lfit,w_440,limit_1/format,f_auto)

## 三、javascript的10个缺陷

* JavaScript由于当时设计阶段过于仓促加上没有设计先例可参考等原因，导致JavaScript的设计不够完善，存在部分缺陷。
* JavaScript的10个缺陷

1. 不适合开发大型程序

Javascript没有名称空间（namespace），很难模块化；没有如何将代码分布在多个文件的规范；允许同名函数的重复定义，后面的定义可以覆盖前面的定义，很不利于模块化加载。

2. 非常小的标准库

Javascript提供的标准函数库非常小，只能完成一些基本操作，很多功能都不具备。

3. null和undefined

null属于对象（object）的一种，意思是该对象为空；undefined则是一种数据类型，表示未定义.

4. Javascript的全局变量，在所有模块中都是可见的；任何一个函数内部都可以生成全局变量，这大大加剧了程序的复杂性。

5. Javascript的所有语句，都必须以分号结尾。但是，如果你忘记加分号，解释器并不报错，而是为你自动加上分号。有时候，这会导致一些难以发现的错误。
6. 加号运算符

+号作为运算符，有两个含义，可以表示数字与数字的和，也可以表示字符与字符的连接。

7. NaN
   
NaN是一种数字，表示超出了解释器的极限。它有一些很奇怪的特性:

8. 数组和对象的区分

由于Javascript的数组也属于对象（object），所以要区分一个对象到底是不是数组，相当麻烦。

9. == 和 ===

==用来判断两个值是否相等。当两个值类型不同时，会发生自动转换，得到的结果非常不符合直觉。

10. 基本类型的包装对象

Javascript有三种基本数据类型：字符串、数字和布尔值。它们都有相应的建构函数，可以生成字符串对象、数字对象和布尔值对象。

[详情请查看文章](http://www.ruanyifeng.com/blog/2011/06/10_design_defects_in_javascript.html)

## 四、ECNAScript的标准

1. 1997年6月，第一版ECNAScript发布
2. 1999年12月，第三版发布，这个版本使用最广
3. 第四版流产
4. 2009年，第五版发布，增加了一些功能
5. 2015年6月，新的浏览器都支持这一版。ES6目前主要学习这一版。
6. 之后每年发布一版，版本号以年份命名

## 五、JavaScript的现状

1. 互联网前端岗位缺人，因为没有大学开设相关专业，主要都来源于自学和培训机构。
2. 前端是进入互联网的捷径
3. 前端没有内卷，但培训机构开始内卷了，要注意辨别培训机构是否优质。