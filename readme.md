备注：

 ### 离思五首

<table>
    <tr>
         <td>曾经沧海难为水</td>
     </tr> 
</table>
 
<table>
    <tr>
         <td>除却巫山不是云</td>
     </tr> 
</table> 

<table>
    <tr>
         <td>取次花丛懒回顾</td>
     </tr> 
</table>   

<table>
    <tr>
         <td>取次花丛懒回顾</td>
     </tr> 
</table>
        
>小于号表示注释块

>      小于号加五个空格

*两边加一个星号或者下划线代表斜体*

__两边加两个星号或者下划线表示加粗__

* 无序列表1
* 无序列表2
* 无序列表3
* 无序列表4
* 无序列表5
* 文字开头添加(*, +, and -)实现无序列表（要加空客）

1. 有序列表1
2. 有序列表2
3. 有序列表3
4. 有序列表4
5. 使用数字后面跟上句号。（还要有空格）

##### 图片（Images）
图片的处理方式和链接的处理方式，非常的类似。
###### 内联方式：
![alt text](/img/1.jpg "Title")


### 代码（HTML中所谓的Code）
#### 实现方式有两种：
第一种：简单文字出现一个代码框。使用反引号。（`不是单引号而是左上角的ESC下面~中的`）
 `<p>青青河边草</p>`
 
第二种：用<code>。
<code>野火烧不尽</code>

### 在 HTML 文件中，有两个字符需要特殊处理： < 和 & 。
 < 符号用于起始标签，& 符号则用于标记 HTML 实体，
 如果你只是想要显示这些字符的原型，你必须要使用实体的形式，
 像是<用 “&lt;”; 和 & 用  “&amp;”;。
 4 &lt; 5
& 字符尤其让网络文档编写者受折磨，如果你要打「AT&T」 ，你必须要写成「AT&amp;T」。
而网址中的 & 字符也要转换。比如你要链接到：
http://images.google.com/images?num=30&q=larry+bird
必须写成：
http://images.google.com/images?num=30&amp;q=larry+bird

### Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。
类 Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题），例如：
This is an H1
=============

This is an H2
--------------

#### 类 Atx 形式则是在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶，例如：
# 这是 H1
## 这是 H2
###### 这是 H6

#### 你可以选择性地「闭合」类 atx 样式的标题，
这纯粹只是美观用的，若是觉得这样看起来比较舒适，
你就可以在行尾加上 #，而行尾的 # 数量也不用和开头一样
（行首的井字符数量决定标题的阶数）：
# 这是 H1 #

## 这是 H2 ##

### 这是 H3 ######

#### 区块引用 Blockquotes
Markdown 标记区块引用是使用类似 email 中用 > 的引用方式。如果你还熟悉在 email 信件中的引言部分，
你就知道怎么在 Markdown 文件中建立一个区块引用，那会看起来像是你自己先断好行，
然后在每行的最前面加上 > ：
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

##### 区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > ：
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

分隔线
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：
* * *

***

*****

- - -

---------------------------------------




