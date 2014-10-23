hello-world
===========

本项目是为本人熟悉markdown语法所用，对游客无实际作用。  
语法参考自：  
[Markdown Cheat Sheet](http://www.afewords.com/blog/50d5b1813725170f8c69d2dd)  
[Markdown官方文档](http://daringfireball.net/projects/markdown/syntax)

My "cnblogs" blog:
[cnblogs-Freecode#](http://www.cnblogs.com/yym2013/)
***

##语法清单：

**用*加粗**   __用_加粗__
***

*斜体1*       _斜体2_  
***

--删除线1--  
ps:需插件
***

..下划线1..  
ps:需插件
***

[锚链接 - hello-world](#hello-world)
[锚链接 - 美女](#图片 )
***

###行内代码  
`using namespace std;`  
using namespace std;
***

###行内公式（ps:需插件）  
$a^2+b^2=c^2$  
a2+b2=c2
***

###行间公式（ps:需插件）  
$$\sum_{i=0}^n{i^2}$$  
∑i=0ni2
***

###图片  
![mypic](http://img1.gamersky.com/image2014/10/20141006wdy_1/05.jpg "福利")
***

###标题
#header 1 #
##header 2 ##
###header 3 ### 如果###后面带着字就会连带着#显示出来
####header 4
#####header 5
######header 6 最多显示到5,6和5就一样了
***

###无序列表  

+ 无序列表1  
+ 无序列表2  
+ 无序列表3  

***

+ 无序列表4  
+ 无序列表5  
+ 无序列表6  

***

* 无序列表7  
* 无序列表8  
* 无序列表9  

***

###有序列表  

1. 有序列表  
1. 有序列表  
1. 有序列表

***

1. 有序列表
2. 有序列表
3. 有序列表

***

###列表嵌套

1. 1 level list 1
  + 2 level list 1
    - 3 level list 1
    - 3 level list 2
    - 3 level list 3
  + 2 level list 2
    - 3 level list 1
    - 3 level list 2
    - 3 level list 3
1. 1 level list 2
  1. 2 level list 1
    1. 3 level list 1
    2. 3 level list 2
    3. 3 level list 3
  1. 2 level list 2
    1. 3 level list 1
    1. 3 level list 2
    1. 3 level list 3

***
###块引用  
下面是一首诗
>悯农  
>作者：李绅  
  >>春种一粒粟，秋收万颗子。四海无闲田，农夫犹饿死。  
  >>锄禾日当午，汗滴禾下土。谁知盘中餐，粒粒皆辛苦。
    >>>第一首诗一开头，就以“一粒粟”化为“万颗子”具体而形象地描绘了丰收，用“种”和“收”赞美了农民的劳动。第三句再推而广之，展现出四海之内，荒地变良田，这和前两句联起来，便构成了到处硕果累累，遍地“黄金”的生动景象。
>  
>

***
###代码块
```c++
#include <iostream>
using namespace std;
int main()
{
  cout<<"Hello world!"<<endl;
  return 0;
}
```

###水平线
***
* * *
- - -
---
***
###使用HTML - 表格 
<table border="0" cellpadding="3" cellspacing="1" width="100%" align="center" style="background-color: #b9d8f3;">
    <tr>
      <th>学号</th>
      <th>姓名</th>
      <th>班级</th>
    </tr>
    <tr>
      <td>1101</td>
      <td>王二</td>
      <td>101-1</td>
    </tr>
    <tr>
      <td>1223</td>
      <td>李三</td>
      <td>101-2</td>
    </tr>
    <tr>
      <td>1312</td>
      <td>刘四</td>
      <td>101-3</td>
    </tr>
</table>
