### 1.标题
1）加 “井号”
文本前面加 “#”， 可以让文本变为标题，# 越多字号越小

注意：一级标题一个#， 二级标题##， 以此类推， 最多六级标题（同h6）  
建议在井号后加一个空格  

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

<code> # 一级标题 </code>  
<code> ## 二级标题 </code>  
<code> ### 三级标题 </code>  
<code> #### 四级标题 </code>  
<code> ##### 五级标题 </code>  
<code> ###### 六级标题 </code>

2）加 “ = ” 或者 “ - ”   

注意：这种方式只能表示一级和二级两种标题的文本， 文本写好后换行再写“等号” >> 产生一级标题；文本写好后换行再写“中横线”>> 产生二级标题；另外写任意多个等号或者中横线都会产生对应标题效果，只写一个也可以  

示例：  

一级
=
二级
-
<code>源码：</code>  
<code>一级</code>  
<code>= 或者 n个=</code>  
<code>二级</code>  
<code>- 或者 n个-</code>  

***
  
  
### 2.列表  

1) 无序列表：文字前面加“星号”或者“中横线”或者“加号”定义无序列表 ,无序列表各项前面是圆点  

* 无序列表项示例
- 无序列表项示例
+ 无序列表项示例

<code>源码： * 无序列表项 </code>  
<code>源码： - 无序列表项 </code>  
<code>源码： + 无序列表项 </code>

2）有序列表：直接在文本前面加上一个数字即可（注意编号后面要有点号，只要是数字即可，数字不用按照顺序） 

1. 有序列表项  
1. 有序列表项  
0. 有序列表项

<code>源码：1. 有序列表项</code>  
<code>源码：1. 有序列表项</code>  
<code>源码：0. 有序列表项</code>

***
### 3.引用

定义引用： 文本前面加 “ 大于号 ” 即可  

注意：引用里面可以正常用markdown的语法

1）中间没有空行的引用：第一行前面一个“大于号”， 或者每行前面都有一个“大于号”  

示例：
> P-one  
line-one  
line-two  
line-three   

示例：
> P-two  
> line-one  
> line-two

源码：  
<code>首行加大于号</code>  
<code> > P-one</code>  
<code>line-one</code>  
<code>line-two</code>  
<code>line-three</code>

<code>每行都加大于号源码：</code>  
<code> > P-one</code>  
<code> > line-one</code>  
<code> > line-two</code>  
<code> > line-three</code>

2）中间有空行的引用：只能用每行都加“ 大于号 ”   

示例：    
> 第一行  
>  
> 第三行

源码：  
<code> > line-one</code>  
<code> >  </code>  
<code> > line-three</code>

3）应用中可以嵌套引用：两个“大于号”代表嵌套引用（嵌套之后的内容都是嵌套引用的内容了，即使只写了一个“大于号”）

示例：    
> 第一行  
> > 嵌套引用  
> 第三行

源码：  
<code> > 第一行</code>  
<code> > > 嵌套引用  </code>  
<code> > 第三行</code>

***

### 4.图片和链接  

注意： 图片的路径要用图床来表示（图床是专门存放图片的服务器）  

1）图片：“叹号” 加 “方括号” 加 “圆括号”

![图片替代文字](http://upload-images.jianshu.io/upload_images/2368113-537bd1ac9fc24a0b?imageMogr2/auto-orient/strip%7CimageView2/1/w/300/h/240)

<code>源码：! [图片替代文字] (http://upload-images.jianshu.io/upload_images/2368113-537bd1ac9fc24a0b?imageMogr2/auto-orient/strip%7CimageView2/1/w/300/h/240) </code>


2）链接：“方括号” 加 “圆括号”  

[链接](http://www.baidu.com)  

<code>源码：[链接] (http://www.baidu.com)</code>
***
### 5.粗体与斜体
1）粗体：两个“ 星号 ”包含一串文本，创建粗体文本  
  
示例：**粗体文本**

<code>源码：\*\*粗体文本\*\*</code>

2）斜体：一个“ 星号 ”包含一串文本，创建斜体文本  

示例：*斜体文本*  

<code>源码：\*斜体文本\*</code>
***
### 6.表格 

示例：  

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

<code>源码：</code>  
<code>| Tables        | Are           | Cool  |</code>  
<code>| ------------- |:-------------:| -----:|</code>  
<code>| col 3 is      | right-aligned | $1600 |</code>  
<code>| col 2 is      | centered      |   $12 |</code>  
<code>| zebra stripes | are neat      |    $1 |</code>
***
### 7.代码段
1）使用两个顿号包裹代码段  

示例：`alert('aa');`  

<code>源码：\`alert('aa');\` </code>

2）如果要查看源码，用`<code></code>`或者`<pre></pre>`包裹代码段

### 8.分割线
定义分割线：另起一行，直接输入3个星号，即可创建一条分割线  

示例：
***

<code>源码：***</code>



