1. 斜体和粗体

使用 * 和 ** 表示斜体和粗体。

示例： *斜体* ，**粗体**


2. 分级标题

在想要设置为标题的文字前面加#来表示，注：标准语法一般在#后跟个空格再写文字，貌似简书不加空格也行，使用H标签也可以。
示例：

# 这是一级

## 这是二级

### 这是三级

#### 这是四级

##### 这是五级

###### 这是六级

<H1>这是一级</H1>

<H2>这是二级</H2>

<H3>这是三级</H3>

<H4>这是四级</H4>

<H5>这是五级</H5>

<H6>这是六级</H6>



3. 斜体加粗及删除线

要倾斜和加粗的文字左右分别用三个*号包起来，要加删除线的文字左右分别用两个~~号包起来，示例：

**这是加粗的文字**

*这是倾斜的文字*` 

***这是斜体加粗的文字*** 

~~这是加删除线的文字~~ 



4. 引用

在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>
n个...

>这是引用的内容

>>这是引用的内容


5. 分割线
三个或者三个以上的 - 或者 * 都可以。示例：

---

----

***

*****



6. 图片

语法：

![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加

![blockchain](https://www.baidu.com/img/pcdoodle_2a77789e1a67227122be09c5be16fe46.png "百度")



7. 超链接

语法：

[超链接名](超链接地址 "超链接title")，title可加可不加

[简书](http://jianshu.com)

[百度](http://baidu.com)

<a href="https://www.jianshu.com/u/1f5ac0cf6a8b" target="_blank">我的简书</a>



8. 列表

*无序列表*

语法：
无序列表用 - + * 任何一种都可以，可用tab 或者空格 + -、+ 或者 * +文字内容使列表嵌套示例：

- 第一层列表内容1
	* 第二层1
	* 第二层2
		- 第三层1
		- 第三层2
+ 第一层列表内容2
	* 第二层21
* 第一层列表内容3
	- 第二层31

注意：-+* 跟内容之间都要有一个空格

*有序列表*

语法：数字加点，示例：

1. 列表内容
2. 列表内容
3. 列表内容

***注意：序号跟内容之间要有空格***

9. 列表嵌套

上一级和下一级之间敲三个空格即可，示例：

- 一级无序列表内容

   二级无序列表内容
   
   二级无序列表内容
   
+ 一级无序列表内容

10. 表格
语法：

表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟

11. 代码

语法：单行代码：代码之间分别用一个反引号包起来

`代码内容`
示例
```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    
    fun();
```

    这是一个代码块，此行左侧有四个不可见的空格。


12. 流程图 部分支持

```flow

st=>start: 开始

op=>operation: My Operation

cond=>condition: Yes or No?

e=>end

st->op->cond

cond(yes)->e

cond(no)->op

&```


13. 标签分类

在编辑区任意行的列首位置输入以下代码给文稿标签：

标签： 数学 英语 Markdown

或者

Tags： 数学 英语 Markdown


14. 超链接

自动超链接 语法：

<http://example.com/>

引用式链接 语法：

[link1]:http://www.baidu.com/ 

[引用式链接例子《就是外在文字》][link1]

引用式链接-简化语法：

[百度][]

[百度]: http://google.com/



15. 带有链接的图片

[![图片例子](https://www.baidu.com/img/pcdoodle_2a77789e1a67227122be09c5be16fe46.png "图片说明文字")](http://www.baidu.com/ "链接说明文字")

引用式图片引用

[link2]:https://www.baidu.com/img/pcdoodle_2a77789e1a67227122be09c5be16fe46.png "其实就是HTML 的<a> 标签的 Title 属性"
![引用式图片链接例子《就是Alt属性》][link2]

16. HTML引用

<b>加粗</b>

<strong>加粗</strong>

<i>倾斜</i>

<em>倾斜</em>

<u>下划线</u>

<ins>下划线</ins>

<s>删除线</s>

<del>删除线</del>

这是<sub>下标</sub>

这是<sup>上标</sup>

<b style=“font-size:80px; color:red”>加粗</b>


17. Todo List

-/+/*+空格+[+空格/x+] +空格+文字内容；示例：

- [ ] 待办事项
- [x] 已完成的待办事项
+ [v] 正在处理

18. 脚注

在文档末尾写上[+^+数字+]:+文字内容 声明一个脚注
然后就跟文献引用一样，在要引用该脚注的文字后插入[+^+数字+]即可

该方法根据实验证明有效[^1]
[^1]:文章链接