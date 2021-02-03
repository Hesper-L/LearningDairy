# LearningDairy
前端三要素
HTML(结构）：超文本标记语言（Hyper Text Markup Language）,决定网页的结构和内容
CSS（表现）：层叠样式表（Cascading Style Sheets）,设定网页的表现样式
JavaScript（行为）：是一种弱类型脚本语言，其源代码不需要经过编译，而是由浏览器解释运行，用于控制网页的行为
Day1 
typora-(ctrl+,进入偏好设置)-通用-开启调试模式-可以在空白界面鼠标右键-检查元素-调取网页代码
typora-a-(ctrl+,进入偏好设置)-外观-打开主题文件夹-切换不同主题的颜色（检查元素-写CSS代码color；默认是GitHub CSS）【typora可以自定义CSS，可以编写Html】
typora-markdown拓展语法-内联、上下标、高亮、图表【重启typora生效】
[最常用的Git命令]
1.克隆代码-http地址（git clone https://github.com/Hesper-L/dev-tester.git) & -git地址(git clone git@github.com:Hesper-L/dev-tester.git)
2.拉取代码-git pull
3.切换分支-git checkout branch_name
4.查看工作区状态-git status
5.查看过往提交记录-git log
6.提交到暂存区-git add
7.提交到本地仓库-git commit -m"这里是提交注释"
8.提交到远程仓库-git push
[GitHub搜索技巧]
1.按项目名称（name）查找-in:name dev-tester
2.按项目描述（description）查找-in：description 测试开发面试资源
3.按README描述查找-in：readme python面试题
4.设置星星数（stars）查询范围-stars：>1000
5.设置fork数（fork）查询范围-fork：>500
6.按项目语言筛选-language：java
7.按项目作者查找-user：Hesper-L
8.按项目大小查找-size：>=500
9.组合查找-in:name 测试开发 in:description 面试题 in：readme python stars:>50
[GitHub下载加速]
1.绑定Hosts(加速不明显)； 2.借助Gitee下载代码
下载项目-文件夹-readme文件-git add可以把文件从工作区（文件夹属于工作区）提交到暂存区【仓库到GitHub】-git status可以看到状态改变-通过git commit到本地仓库-接着git push-刷新页面-编辑内容更新
 <!-- DOCTYPE:告诉浏览器，我们要使用什么规范 -->
 <! DOCTYPE html>
 
 <!-- head标签代表网页头部-->
 <head>
     <!--meta描述性标签，它用来描述我们网站的一些信息-->
     <!--meta一般用来做SEO-->
     <meta charset="UTF-8">
     <meta name="keywords" content="Hesper-L">
     <meta name="description" content="这是一个学习笔记的记录地方">
  
     <!-- title网页标题 -->
     <title>我的第一个网页</title>
</head>

<!-- body 标签代表网页主题 -->
<body>
  
<!--标题标签-->
<h1>一级标签</h1>
<h2>二级标签</h2>
<h3>三级标签</h3>
<h4>四级标签</h4>
<h5>五级标签</h5>

<!--段落标签-->
<p>两只老虎          两只老虎</p>
<p>跑得快             跑得快</p>
<p>一只没有耳朵      一直没有尾巴</p>
<p>真奇怪            真奇怪</p>

<!--水平线标签-->
<hr/>

<!--换行标签-->
两只老虎          两只老虎<br/>
跑得快             跑得快<br/>

<!-- 粗体，斜体-->
<h1>字体样式标签</h1>

粗体 ：<strong>i love you</strong>
斜体 ：<em>i love you</em>

<br/>
<!--特殊符号-->
空格 &nbsp；
<br/>
&gt;   ＞
<br/>
&lt;   ＜
&copy;版权所有Hesper-L

<!--
特殊符号记忆方式

&   ；（查百度，首字母联想）

-->
  
</body>
</html>

Day2
<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8">
     <title>Title</title>
  
     <!--script标签内，写Javascript代码-->
     <!--<script>-->
         <!--alert('hello,world');-->
     <!--</script>-->
     
     
      <!--外部引入-->
      <!--注意：script标签必须成对出现-->
      <script src="js/qj.js"></script>
      
      
      <!--不用显示定义type，也默认就是javascript-->
      <script type="text/javascript">
      
     </script>
     
</head>
</html>

Day3
# LearningDairy

### 前端三要素

HTML(结构）：超文本标记语言（Hyper Text Markup Language）,决定网页的结构和内容；

CSS（表现）：层叠样式表（Cascading Style Sheets）,设定网页的表现样式；

JavaScript（行为）：是一种弱类型脚本语言，其源代码不需要经过编译，而是由浏览器解释运行，用于控制网页的行为。

#### 常用Git命令

1.克隆代码

http地址（git clone https://github.com/Hesper-L/dev-tester.git) 

git地址(git clone git@github.com:Hesper-L/dev-tester.git)

2.拉取代码-git pull

3.切换分支-git checkout branch_name

4.查看工作区状态-git status

5.查看过往提交记录-git log

6.提交到暂存区-git add

7.提交到本地仓库-git commit -m"这里是提交注释"

8.提交到远程仓库-git push

GitHub搜索技巧

1.按项目名称（name）查找-in:name dev-tester

2.按项目描述（description）查找-in：description 测试开发面试资源

3.按README描述查找-in：readme python面试题

4.设置星星数（stars）查询范围-stars：>1000

5.设置fork数（fork）查询范围-fork：>500

6.按项目语言筛选-language：java

7.按项目作者查找-user：Hesper-L

8.按项目大小查找-size：>=500

9.组合查找-in:name 测试开发 in:description 面试题 in：readme python stars:>50

#### Github下载加速

1.绑定Hosts(加速不明显)； 

2.借助Gitee下载代码

#### Github基本操作

download-file-readme-git add-git status-git commit-git push-renovate-content renew

## HTML

<!-- DOCTYPE:告诉浏览器，我们要使用什么规范 -->
 <! DOCTYPE html>

 <!-- head标签代表网页头部-->

 <head>
     <!--meta描述性标签，它用来描述我们网站的一些信息-->
     <!--meta一般用来做SEO-->
     <meta charset="UTF-8">
     <meta name="keywords" content="Hesper-L">
     <meta name="description" content="这是一个学习笔记的记录地方">


```html
 <!-- title网页标题 -->
 <title>我的第一个网页</title>
```

</head>

<!-- body 标签代表网页主题 -->
<body>

<!--标题标签-->

<h1>一级标签</h1>
<h2>二级标签</h2>
<h3>三级标签</h3>
<h4>四级标签</h4>
<h5>五级标签</h5>

<!--段落标签-->

<p>两只老虎          两只老虎</p>
<p>跑得快             跑得快</p>
<p>一只没有耳朵      一直没有尾巴</p>
<p>真奇怪            真奇怪</p>

<!--水平线标签-->

<hr/>

<!--换行标签-->
两只老虎          两只老虎<br/>
跑得快             跑得快<br/>

<!-- 粗体，斜体-->

<h1>字体样式标签</h1>

粗体 ：<strong>i love you</strong>
斜体 ：<em>i love you</em>

<br/>
<!--特殊符号-->
空格 &nbsp；
<br/>
&gt;   
<br/>
&lt;   
&copy;版权所有Hesper-L

<!--
特殊符号记忆方式

&   ；（查百度，首字母联想）

-->

</body>
</html>

## 数学

#### 行列式

在数学中，是一个函数，其定义域为det的矩阵A，取值为一个标量，写作det(A)或 | A | 。无论是在线性代数、多项式理论，还是在微积分学中（比如说换元积分法中），行列式作为基本的数学工具，都有着重要的应用。

#### 向量

在数学中，向量（也称为欧几里得向量、几何向量、矢量），指具有大小（magnitude）和方向的量。它可以形象化地表示为带箭头的线段。箭头所指：代表向量的方向；线段长度：代表向量的大小。与向量对应的量叫做数量（物理学中称标量），数量（或标量）只有大小，没有方向。

向量的记法：印刷体记作黑体（粗体）的字母（如**a**、**b**、**u**、**v**），书写时在字母顶上加一小箭头“→”。 [1] 如果给定向量的起点（A）和终点（B），可将向量记作AB（并于顶上加→）。在空间直角坐标系中，也能把向量以数对形式表示，例如xOy平面中(2,3)是一向量。

在物理学和工程学中，几何向量更常被称为矢量。许多物理量都是矢量，比如一个物体的位移，球撞向墙而对其施加的力等等。与之相对的是标量，即只有大小而没有方向的量。一些与向量有关的定义亦与物理概念有密切的联系，例如向量势对应于物理中的势能。

几何向量的概念在线性代数中经由抽象化，得到更一般的向量概念。此处向量定义为向量空间的元素，要注意这些抽象意义上的向量不一定以数对表示，大小和方向的概念亦不一定适用。因此，平日阅读时需按照语境来区分文中所说的"向量"是哪一种概念。不过，依然可以找出一个向量空间的基来设置坐标系，也可以透过选取恰当的定义，在向量空间上介定范数和内积，这允许我们把抽象意义上的向量类比为具体的几何向量。

#### 矩阵

在数学中，矩阵（Matrix）是一个按照长方阵列排列的复数或实数集合 ，最早来自于方程组的系数及常数所构成的方阵。这一概念由19世纪英国数学家凯利首先提出。

矩阵是高等代数学中的常见工具，也常见于统计分析等应用数学学科中。  在物理学中，矩阵于电路学、力学、光学和量子物理中都有应用；计算机科学中，三维动画制作也需要用到矩阵。 矩阵的运算是数值分析领域的重要问题。将矩阵分解为简单矩阵的组合可以在理论和实际应用上简化矩阵的运算。对一些应用广泛而形式特殊的矩阵，例如稀疏矩阵和准对角矩阵，有特定的快速运算算法。关于矩阵相关理论的发展和应用，请参考《矩阵理论》。在天体物理、量子力学等领域，也会出现无穷维的矩阵，是矩阵的一种推广。

数值分析的主要分支致力于开发矩阵计算的有效算法，这是一个已持续几个世纪以来的课题，是一个不断扩大的研究领域。 矩阵分解方法简化了理论和实际的计算。 针对特定矩阵结构（如稀疏矩阵和近角矩阵）定制的算法在有限元方法和其他计算中加快了计算。 无限矩阵发生在行星理论和原子理论中。 无限矩阵的一个简单例子是代表一个函数的泰勒级数的导数算子的矩阵。

#### 矩阵的基本运算

矩阵的基本运算包括矩阵的加法，减法，数乘，转置，共轭和共轭转置 。

1.加法 矩阵的加法满足下列运算律(A,B,C都是同型矩阵): 应该注意的是只有同型矩阵之间才可以进行加法

2.数乘 矩阵的数乘满足以下运算律: 矩阵的加减法和矩阵的数乘合称矩阵的线性运算

3.转置 把矩阵A的行和列互相交换所产生的矩阵称为A的转置矩阵

4.共轭 矩阵的共轭定义为: 一个2×2复数矩阵的共轭(实部不变,虚部取负)

5.共轭转置 

#### 矩阵的逆

设***A\***是一个n阶矩阵，若存在另一个n阶矩阵***B\***，使得： ***AB\***=***BA\***=***E\*** ，则称方阵A可逆，并称方阵B是A的逆矩阵

#### 线性方程组

##### 简介

线性方程组是各个方程关于未知量均为一次的方程组(例如2元1次方程组）。对线性方程组的研究，中国比欧洲至少早1500年，记载在公元初《九章算术》方程章中。

线性方程组有广泛应用，熟知的线性规划问题即讨论对解有一定约束条件的线性方程组问题。

##### 定义

xj表未知量，aij称系数，bi称常数项。

称为系数矩阵和增广矩阵。若x1=c1，x2=c2，…，xn=cn代入所给方程各式均成立，则称（c1，c2，…，cn）为一个解。若c1，c2，…，cn不全为0，则称（c1，c2，…，cn）为非零解。若常数项均为0，则称为齐次线性方程组，它总有零解（0，0，…，0）。两个方程组，若它们的未知量个数相同且解集相等，则称为同解方程组。线性方程组主要讨论的问题是：

①一个方程组何时有解。

②有解方程组解的个数。

③对有解方程组求解，并决定解的结构。这几个问题均得到完满解决：所给方程组有解，则秩(A）=秩（增广矩阵）；若秩(A）=秩=r，则r=n时，有唯一解；r<n时，有无穷多解；可用消元法求解。

当非齐次线性方程组有解时，解唯一的充要条件是对应的齐次线性方程组只有零解；解无穷多的充要条件是对应齐次线性方程组有非零解。但反之当非齐次线性方程组的导出组仅有零解和有非零解时，不一定原方程组有唯一解或无穷解，事实上，此时方程组不一定有 ，即不一定有解。

克莱姆法则（见行列式）给出了一类特殊线性方程组解的公式。n个未知量的任一齐次方程组的解集均构成n维空间的一个子空间。

##### 解法

①克莱姆法则。用克莱姆法则求解方程组 有两个前提，一是方程的个数要等于未知量的个数，二是系数矩阵的行列式要不等于零。用克莱姆法则求解方程组实际上相当于用逆矩阵的方法求解线性方程组，它建立线性方程组的解与其系数和常数间的关系，但由于求解时要计算n+1个n阶行列式，其工作量常常很大，所以克莱姆法则常用于理论证明，很少用于具体求解。

②矩阵消元法.将线性方程组的增广矩阵通过行的初等变换化为行简化阶梯形矩阵 ，则以行简化阶梯形矩阵为增广矩阵的线性方程组与原方程组同解。当方程组有解时，将其中单位列向量对应的未知量取为非自由未知量，其余的未知量取为自由未知量，即可找出线性方程组的解。

关于未知量是一次的方程组，其一般形式为

[![⑴](https://bkimg.cdn.bcebos.com/pic/9a504fc2d5628535be9dcb5f90ef76c6a7ef634a?x-bce-process=image/resize,m_lfit,w_250,h_250,limit_1)](https://baike.baidu.com/pic/线性方程组/5904308/0/bd7042606fe872918db10dab?fr=lemma&ct=single)⑴

式中*x*1，*x*2，…，*x*n代表未知量，*α*ij(1≤*i*≤m,1≤*j*≤*n*)称为方程⑴的系数，*b*i(1≤*i*≤m）称为常数项。系数和常数项都是任意的复数或某一个域的元素。

当常数项*b*1，*b*2，…，*b*n都等于零时，则方程组⑴称为齐次线性方程组。

方程组⑴的系数所构成的m行*n*列矩阵

[![线性方程组](https://bkimg.cdn.bcebos.com/pic/b90e7bec54e736d17a6a95769b504fc2d5626956?x-bce-process=image/resize,m_lfit,w_220,h_220,limit_1)](https://baike.baidu.com/pic/线性方程组/5904308/0/95afee1f6f6d01bbe0fe0bb7?fr=lemma&ct=single)线性方程组

称为方程组⑴的系数矩阵。在*A*中添加由常数项组成的列而得到一个m行*n*+1列矩阵

[![线性方程组](https://bkimg.cdn.bcebos.com/pic/c75c10385343fbf28556bf5db07eca8065388f51?x-bce-process=image/resize,m_lfit,w_220,h_220,limit_1)](https://baike.baidu.com/pic/线性方程组/5904308/0/adee30dd948b50978d1029b2?fr=lemma&ct=single)线性方程组

称为方程组⑴的增广矩阵。

如果在方程组⑴中，以一组复数或域*F*的元素с1,с2，…，сn代替未知量*x*1，*x*2，…，*x*n，每一个方程的两端相等，那么с1，с2，…，сn称为方程组⑴的一个解。

关于线性方程组，有以下主要结果。

①线性方程组⑴有解的充分必要条件是，系数矩阵*A*与增广矩阵都有相同的秩。

②在*A*与都有相同的秩*r*>0的情形下，*A*有一个*r*阶子式*D*不等于零，设

[![线性方程组](https://bkimg.cdn.bcebos.com/pic/b3fb43166d224f4a2dee6a6d09f790529822d15c?x-bce-process=image/resize,m_lfit,w_220,h_220,limit_1)](https://baike.baidu.com/pic/线性方程组/5904308/0/1b0d4f0fd4b3fb646059f3bd?fr=lemma&ct=single)线性方程组

于是方程组⑴与仅含有前*r*个方程的方程组同解。可将前*r*个方程改写为

[![⑵](https://bkimg.cdn.bcebos.com/pic/6a600c338744ebf805007d41d9f9d72a6059a75e?x-bce-process=image/resize,m_lfit,w_250,h_250,limit_1)](https://baike.baidu.com/pic/线性方程组/5904308/0/e8112b2ad9103c765343c1bf?fr=lemma&ct=single)⑵

方程组⑵的一般解公式为　*x*1=*D*1/*D*,*x*2=*D*2/*D*，…，*x*r=*D*r/*D*，　⑶

式中*D*j(*j*=1,2，…，*r*）是把*D*的第*j*列换成方程组⑵的右端的列所得到的一个*r*阶行列式，即

[![线性方程组](https://bkimg.cdn.bcebos.com/pic/2e2eb9389b504fc28c2da97be5dde71190ef6d59?x-bce-process=image/resize,m_lfit,w_250,h_250,limit_1)](https://baike.baidu.com/pic/线性方程组/5904308/0/e1bf8725e57e702e34a80fba?fr=lemma&ct=single)线性方程组

因而*x*1,*x*2，…，*x*r可由其余的未知量*x*r+1,*x*r+2，…，*x*n线性表出，*x*r+1，*x*r+2，…，*x*n称为自由未知量。

当*r*<*n*时，则任意给自由未知量的一组值，由⑶可求出*x*1，*x*2，…，*x*r的值即方程组⑴的一个解，此时方程组⑴的解不只一个。当*r*=*n*时，则方程组⑵不含自由未知量，由⑶给出方程组⑴的惟一解。当m=*n*=*r*时，公式⑶称为克莱姆规则。

线性方程组是最简单也是最重要的一类代数方程组。大量的科学技术问题，最终往往归结为解线性方程组，因此线性方程组的数值解法在计算科学中占有重要地位。

#### 线性回归

##### 基本含义

在统计学中，线性回归（Linear Regression）是利用称为线性回归方程的最小平方函数对一个或多个自变量和因变量之间关系进行建模的一种回归分析。这种函数是一个或多个称为回归系数的模型参数的线性组合。只有一个自变量的情况称为简单回归，大于一个自变量情况的叫做多元回归。（这反过来又应当由多个相关的因变量预测的多元线性回归区别，而不是一个单一的标量变量。）

在线性回归中，数据使用线性预测函数来建模，并且未知的模型参数也是通过数据来估计。这些模型被叫做线性模型。最常用的线性回归建模是给定X值的y的条件均值是X的仿射函数。不太一般的情况，线性回归模型可以是一个中位数或一些其他的给定X的条件下y的条件分布的分位数作为X的线性函数表示。像所有形式的回归分析一样，线性回归也把焦点放在给定X值的y的条件概率分布，而不是X和y的联合概率分布（多元分析领域）。

线性回归是回归分析中第一种经过严格研究并在实际应用中广泛使用的类型。这是因为线性依赖于其未知参数的模型比非线性依赖于其未知参数的模型更容易拟合，而且产生的估计的统计特性也更容易确定。

线性回归模型经常用最小二乘逼近来拟合，但他们也可能用别的方法来拟合，比如用最小化“拟合缺陷”在一些其他规范里（比如最小绝对误差回归），或者在桥回归中最小化最小二乘损失函数的惩罚.相反,最小二乘逼近可以用来拟合那些非线性的模型.因此，尽管“最小二乘法”和“线性模型”是紧密相连的，但他们是不能划等号的。

##### 拟合方程

###### 最小二乘法

一般来说，线性回归都可以通过最小二乘法求出其方程，可以计算出对于y=bx+a的直线。 

一般地，影响y的因素往往不止一个，假设有x1，x2，...，xk，k个因素，通常可考虑如下的线性关系式：

![img](https://bkimg.cdn.bcebos.com/formula/f654a9b87f182877dad9701c3ba8b1e7.svg)

对y与x1，x2，...，xk同时作n次独立观察得n组观测值（xt1，xt2，...，xtk），t=1,2,...,n（n>k+1），它们满足关系式：

![img](https://bkimg.cdn.bcebos.com/formula/712cb93c70e4c8492a2e79b8aa30c22c.svg)

其中，

![img](https://bkimg.cdn.bcebos.com/formula/0faf6292ed5d47548cc52b9a4bcfe842.svg)

 互不相关均是与

![img](https://bkimg.cdn.bcebos.com/formula/959ad200f9fb074d206b223d046b88ba.svg)

 同分布的随机变量。 [3] 为了用矩阵表示上式，令：

[![img](https://bkimg.cdn.bcebos.com/pic/8644ebf81a4c510fd42697356059252dd42aa53a?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/线性回归/8190345/0/c71d0e385e9cbbedb311c75b?fr=lemma&ct=single)

[![img](https://bkimg.cdn.bcebos.com/pic/8644ebf81a4c510fd42697356059252dd42aa53a?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/线性回归/8190345/0/c71d0e385e9cbbedb311c75b?fr=lemma&ct=single)

[![img](https://bkimg.cdn.bcebos.com/pic/8644ebf81a4c510fd42697356059252dd42aa53a?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/线性回归/8190345/0/c71d0e385e9cbbedb311c75b?fr=lemma&ct=single)

[![img](https://bkimg.cdn.bcebos.com/pic/8644ebf81a4c510fd42697356059252dd42aa53a?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/线性回归/8190345/0/c71d0e385e9cbbedb311c75b?fr=lemma&ct=single)

于是有

![img](https://bkimg.cdn.bcebos.com/formula/5887ea28221d3ae296159b4876585978.svg)

，使用最小二乘法得到

![img](https://bkimg.cdn.bcebos.com/formula/ea027d6202a985007785bbb2f1642553.svg)

 的解

![img](https://bkimg.cdn.bcebos.com/formula/ae60b716dfd1455e5366e95939243e76.svg)

。 [3] 其中，

![img](https://bkimg.cdn.bcebos.com/formula/2c13cde0651bbf7ba42036b1a66ca2d7.svg)

称为

![img](https://bkimg.cdn.bcebos.com/formula/9f7d1d2e6f98698b18cf0939756901ac.svg)

的伪逆。

###### 回归系数

一般地，要求这个值大于5%。对大部分的行为研究者来讲，最重要的是回归系数。年龄增加1个单位，文档的质量就下降 -.1020986个单位，表明年长的人对文档质量的评价会更低。这个变量相应的t值是 -2.10，绝对值大于2，p值也<0.05，所以是显著的。结论是，年长的人对文档质量的评价会更低，这个影响是显著的。相反，领域知识越丰富的人，对文档的质量评估会更高，但是这个影响不是显著的。这种对回归系数的理解就是使用回归分析进行假设检验的过程。

##### 回归方程误差

###### 离差平方和

![img](https://bkimg.cdn.bcebos.com/formula/cf21fec9f7853f59b94d3ad7ef728e24.svg)

 ，

![img](https://bkimg.cdn.bcebos.com/formula/2b6d70a8bd1476e7bf9d7dbeba145f0c.svg)

 ，

![img](https://bkimg.cdn.bcebos.com/formula/69c7b5001f156cd0953e15be0b68a6dd.svg)

其中

![img](https://bkimg.cdn.bcebos.com/formula/65e01e7642774d77cdf67412fce49a4e.svg)

 ，代表y的平方和；r 是相关系数，代表变异被回归直线解释的比例；

![img](https://bkimg.cdn.bcebos.com/formula/1080b39405c35883c23598980339f1b7.svg)

 就是不能被回归直线解释的变异，即SSE。

根据回归系数与直线斜率的关系，可以得到等价形式： ，其中b为直线斜率

###### 利用预测值

![img](https://bkimg.cdn.bcebos.com/formula/714a353ba4fe2a61705fa73885bb0515.svg)

 其中

![img](https://bkimg.cdn.bcebos.com/formula/146f9e193fd6c03340cc469aa752b5ff.svg)

是实际测量值，

![img](https://bkimg.cdn.bcebos.com/formula/8dd399d098508ab4e0734233c6df000a.svg)

是根据直线方程算出来的预测值。

##### 不确定度

###### 斜率b

法1：用

![img](https://bkimg.cdn.bcebos.com/formula/29ecac7d98ef7b8b7d4399a961ff7b42.svg)

![img](https://bkimg.cdn.bcebos.com/formula/41024347aba46f4d5b6bcbef9c7e5e37.svg)

法2：把斜率b带入

![img](https://bkimg.cdn.bcebos.com/formula/1ca230f30aa6c4bd2bb21aefe16e0aba.svg)

###### 截距a

![img](https://bkimg.cdn.bcebos.com/formula/be259598d7ef8dc7ec0a7708ab66ce2a.svg)

##### 应用

###### 数学

线性回归有很多实际用途。分为以下两大类：

1. 如果目标是预测或者映射，线性回归可以用来对观测数据集的和X的值拟合出一个预测模型。当完成这样一个模型以后，对于一个新增的X值，在没有给定与它相配对的y的情况下，可以用这个拟合过的模型预测出一个y值。
2. 给定一个变量y和一些变量X1,...,Xp，这些变量有可能与y相关，线性回归分析可以用来量化y与Xj之间相关性的强度，评估出与y不相关的Xj，并识别出哪些Xj的子集包含了关于y的冗余信息。

###### 趋势线

一条趋势线代表着时间序列数据的长期走势。它告诉我们一组特定数据（如GDP、石油价格和股票价格）是否在一段时期内增长或下降。虽然我们可以用肉眼观察数据点在坐标系的位置大体画出趋势线，更恰当的方法是利用线性回归计算出趋势线的位置和斜率。
