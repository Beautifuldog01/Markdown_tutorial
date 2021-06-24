# Markdown Syntax Tutorial  

## 说明

1. 自截止修改本文最后时间2021年6月24日起，markdown语法规则可能会随着时间的推移发生变化，最新的语法规则以<https://github.com/DavidAnson/markdownlint/blob/v0.23.1/doc/Rules.md>为准。  
2. 命令标点应在英文标点的环境下输入  
3. 本文使用的软件Typora为开源软件,可在<https://www.typora.io/>下载对应的版本。

## 段落格式  

在编写的文字后加入两个空格(<kbd>space</kbd>+<kbd>space</kbd>)表示开启下一段落（具体视觉效果为空出一行）
等效于直接空出一行  
这里给出菜鸟教程[^RUNOOB.COM]上的截图演示:  
![段落格式](https://github.com/Beautifuldog01/Markdown_tutorial/blob/main/Tutorial/Markdown/Pics/%E6%AE%B5%E8%90%BD%E6%A0%BC%E5%BC%8F.PNG)

## 代码块的插入  

先输入三个<kbd>\`</kbd>+(代码语言) 表示代码块的开始,  
接着按<kbd>enter</kbd>在下一行中开始输入代码,  
最后再输入三个<kbd>`</kbd>表示代码块的结束

```markdown
···python
···
```

依次按<kbd>ctrl</kbd>+<kbd>enter</kbd>从代码块中跳出到笔记的下一行  

实际效果:  

```python
print("Hello world!")
```

## 标题的写法  

```markdown
# 'title name'一级标题
## 'title name'二级标题
### 'title name'三级标题
#### 'title name'四级标题
##### 'title name'五级标题
###### 'title name'六级标题
```

在typora中按<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>1</kbd>打开大纲视角

## 字体样式  

```markdown
加粗:
**加粗**
斜体:
*斜体*
***粗斜体***
粗斜体
代码高亮显示:
==代码高亮显示==
删除线:
~~删除线~~
下划线:
</u>下划线</u>
脚注:
[^要注明的文本]
```

实际效果:  
**加粗**  
*斜体*  
***粗斜体***  
==代码高亮显示==  
~~删除线~~  
</u>下划线</u>  
[^要注明的文本]

## 分割线  

建立分割线的方法有很多，具体为以下五种:  

```markdown
***(推荐使用这种分割线写法)
* * *
*****
- - -
----------  
```

实际效果:  
***

## 区块层级  

```markdown
>author:beautifuldog01
>>author:beautifuldog01
>>>author:beautifuldog01
```

可通过逐次按<kbd>Ctrl</kbd>+<kbd>[</kbd>离开区块层级

实际效果:  
>author:beautifuldog01
>>author:beautifuldog01
>>
>>>author:beautifuldog01

## 列表  

无序列表  

```markdown
* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项

- 第一项
- 第二项
- 第三项
```

实际效果:

* 第一项
* 第二项
* 第三项

* 第一项
* 第二项
* 第三项

* 第一项
* 第二项
* 第三项

有序列表  

```markdown
1. 第一项
2. 第二项
3. 第三项
```

实际效果:

1. 第一项
2. 第二项
3. 第三项

### 列表嵌套  

```markdown
1. 第一项:
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项:
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素
```

实际效果:

1. 第一项:
    * 第一项嵌套的第一个元素
    * 第一项嵌套的第二个元素
2. 第二项:
    * 第二项嵌套的第一个元素
    * 第二项嵌套的第二个元素

## 插入图片

在Typora中，你可以直接将图片拖入其中,  
也可以用代码的方式手动添加，具体如下:  

```markdown
![alt 标题](图片的文件地址)
![alt 标题](图片的文件地址 "可选标题")
```

实际效果:  
![alt typora](https://github.com/Beautifuldog01/Markdown_tutorial/blob/main/Tutorial/Markdown/Pics/typora.PNG)

## 表格

在markdown中,用<kbd>|</kbd>分隔不同的单元格,用<kbd>-</kbd>分隔表头和其他行,具体写法如下:

```markdown
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
```

实际效果:
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

### 对齐方式

-: 表示内容和标题栏居右对齐  
:-: 表示内容和标题栏居中对齐  
:- 表示内容和标题栏居左对齐  

实际效果:  
| 左对齐 | 居中对齐 | 右对齐 |
| :-----| :----: | ----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

## 扩展

markdown作为优秀的轻量级标记语言,支持html元素、LaTeX和TeX格式的数学公式，以及可以绘制流程图、时序图(顺序图)、甘特图等等。
更多的扩展知识可以访问  
<https://developer.mozilla.org/zh-CN/docs/Web/HTML>  
<https://www.latex-project.org/help/>  
关于更多关于软件Typora的使用可以访问CSDN社区作者Simba1949的文章:  
<https://blog.csdn.net/SIMBA1949/article/details/79001226>  
