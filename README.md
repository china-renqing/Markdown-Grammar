# 基于Typora的Markdown文件的快捷写法（语法）

### Hi there 👋

* 这是本人第一次编写和上传，写的效果不是很好，希望各位能够多指点，如果有写的不好的地方，或者不对的地方，或者需要改进的地方，希望各位多多提醒，共同进步。
* <font color="blue" face="STCAIYUN">编写不易，我理解了</font>

话不多说，直接看写法和效果

* 代码块儿中表示的是写法
* 代码块儿下方就是对应写法的效果呈现
* 后面如果有新的写法我也会及时更新



---

##  一、标题相关编写和呈现

#### 标题编写：

```javascrio
最多支持的一共是六级标题，再网下会字节原样输出
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

#### 标题效果图：

* 呈现

  * ># 一级标题
    >
    >## 二级标题
    >
    >### 三级标题
    >
    >#### 四级标题
    >
    >#####  五级标题
    >
    >###### 六级标题



---

## 二、字体相关编写和呈现

#### 字体编写：

~~~
~~这是删除字体~~
*这是斜体字*
**这是加粗字体**
***这是加粗斜线字体***
~~~

#### 字体效果图：

* 呈现

  * >~~这是删除字体~~
    >*这是斜体字*
    >**这是加粗字体**
    >***这是加粗斜线字体***

---

## 三、列表和表单相关编写和呈现

#### 列表编写：

~~~
1、标题
* 一级标题
   * 二级标题
      * 三级标题
//注意：此处是三个空格
~~~

#### 列表效果图：

呈现：

>* 一级标题
>  * 二级标题
>    * 三级标题

---

#### 表单编写：

```txt
* 写法一：					  //该写法至少写三行，第二行的:(冒号)用于控制左居中，右居中，和居中
							//第一个横杠不可少，否正不成表，第二个横杠设置居中时不可少,否正居中无效，横杠可多个
表头1|表头2|表头3			
-|:-:|-:
😋|😜|😘

* 写法二
|表头1|表头2|表头3|
//该写法直接生成表头，内容自行添加
```

#### 表单效果图：

* 写法一呈现：

  * >| 表头1 | 表头2 | 表头3 |
    >| ----- | :---: | ----: |
    >| 😋     |   😜   |     😘 |

* 写法二呈现：

  * >| 表头1    | 表头2    | 表头3    |
    >| -------- | -------- | -------- |
    >| 自行填充 | 自行填充 | 自行填充 |



***

## 四、图片和超链接的相关创建和呈现

#### 图片编写：

```
![百度图片](https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png,"百度搜索")
![搜狗搜索](https://dlweb.sogoucdn.com/pcsearch/web/index/images/logo_300x116_e497c82.png "搜狗搜索")
			//写法:	![title](url ”hoverTitle“)		起手写好：![]()	再逐步添加
			//! 感叹号，固定格式语法
			//[]中括号钟填写的文字，也就是图片正下方的文字，本人使用的是Typora进行编写未显现，手动加的
			//(url "hoverTile")小括号里面填写的是图片地址，当然这个图片地址可以是自己的电脑的本地地址,
            //hoberTitle，用于编写鼠标悬停的时候显示的值，在url后面加一个空格然后加双引号包裹
```

#### 图片效果图：

* 呈现

  * >![百度搜索](https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png "百度搜索")
    >
    >​																								百度搜索
    >
    >![搜狗搜索](https://dlweb.sogoucdn.com/pcsearch/web/index/images/logo_300x116_e497c82.png "搜狗搜索")
    >
    >​																								搜狗搜索

#### 超链接编写：

~~~
[百度搜索](https://www.baidu.com)
[搜狗搜索](https://www.sougou.com)
[庆蝈蝈的GitHub](https://www.GitHub.com/china-renqing)
<a url="https://www.GitHub.com/china-renqing">庆蝈蝈的GitHub</a>
~~~

#### 超链接效果图：

* 呈现：

  * >[百度搜索](https://www.baidu.com)
    >[搜狗搜索](https://www.sougou.com)
    >[庆蝈蝈的GitHub](https://www.GitHub.com/china-renqing)
    >
    ><a url="https://www.GitHub.com/china-renqing">庆蝈蝈的GitHub</a>



***

## 五、引用和分割线的相关编写和呈现

#### 分割线编写：

```
占位
***
*****
---
-----
三个或者三个以上的星号(*)，或者减号(-)即可
```

#### 分割线效果图：

* 呈现

  * >占位
    >
    >***
    >
    >*****
    >
    >---
    >
    >-----

#### 引号编写：

~~~
>
//一个大于符号即可，可写多层
~~~

#### 引号效果图：

* 呈现：

  * >
    >
    >>
    >>
    >>>
    >>>
    >>>>
    >>>>
    >>>>

## 六、代码（单行代码和代码块儿）的编写和呈现

#### 单行代码编写：

```
`这里呈现的是一个单行代码`
`int i=1`
这是正文，用于区分区别
```

#### 单行代码效果图：

* 呈现

  * >`这里呈现的是一个单行代码`
    >
    >`var i=1`
    >
    >这是正文，用于区分区别

#### 代码块儿编写：

```
//直接敲击三个 ` 符号，然后敲击回车即可生成一个代码块儿

直接生成的代码块儿1
​```
直接生成的代码块儿2
~~~
//也可以在其它文本文件敲好，然后复制粘贴过来后直接生成代有数据的码块儿
通过复制粘贴生成的代码块儿
​```
这是代码块儿语句1
这是代码块儿语句2
这是代码块儿语句3
​```
```

#### 单行代码效果图：

* 呈现

  * >直接生成的代码块儿1
    >
    >```
    >
    >```
    >
    >直接生成的代码块儿2
    >
    >~~~
    >
    >~~~
    >
    >通过复制粘贴生成的代码块儿
    >
    >```
    >这是代码块儿语句1
    >这是代码块儿语句2
    >这是代码块儿语句3
    >```

## 八、字体颜色的编写和呈现

#### 字体颜色编写：

```
<font color="red">我是红色</font>
<font color="green" size=4>我是绿色</font>
<font color="#F7F" size=5 face="STCAIYUN">我是紫色华文彩云</font>
//color控制颜色，size控制大小，face控制字体
```

#### 字体颜色效果图：

* 呈现

  * ><font color="red">我是红色</font>
    ><font color="green" size=4>我是绿色</font>
    ><font color="#F7F" size=5 face="STCAIYUN">我是紫色华文彩云</font>



## 九、流程图的编写和呈现

#### 流程图编写：

```
​```flow
st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...
para=>parallel: parallel tasks

st->op1->cond
cond(yes)->io->e
cond(no)->para
para(path1, bottom)->sub1(right)->op1
para(path2, top)->op1
​```
```

#### 流程图效果：

* 呈现

  * >```flow
    >st=>start: Start:>http://www.github.com/china-renqing
    >e=>end
    >op1=>operation: My Operation
    >sub1=>subroutine: My Subroutine
    >cond=>condition: Yes or No?
    >io=>inputoutput: catch something...
    >para=>parallel: parallel tasks
    >
    >st->op1->cond
    >cond(yes)->io->e
    >cond(no)->para
    >para(path1, bottom)->sub1(right)->op1
    >para(path2, top)->op1
    >```



​	

因为关于流程图方面的代码有很多，我准备一条链接：[关于flow的用法官网](http://flowchart.js.org/)

## 十、总结

* 这是本人第一次写这么长的笔记，自己也是查了不少资料，写了一篇非常适合自己看的文档，相当于是笔记了，自己有忘记的时候可以返回来看一看。（悄悄告诉你们，这个笔记我写了好几天）
* 最后给大家分享一波：[markdown的中文文档](https://markdown-zh.readthedocs.io/)
