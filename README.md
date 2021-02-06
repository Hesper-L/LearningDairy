# LearningDairy
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

Day4
## Matlab

### 一 | 3类语句

#### 01 | if 语句

```matlab
clear
clc
%已知A，求B
A=6;
if A>5
    B=1;
elseif A>0
    B=2;
else
    B=3;
end
```

我们使用if语句判断B到底应该等于几？

![img](https://pic4.zhimg.com/v2-f4e55f3ac97e1273473d60d30676289b_b.jpg)

<hr/>

#### 02 | for语句

```matlab
clear
clc
% 求1到10的和
T=0;
for i=1:10
    T=T+i;
end
```

我们使用for语句再次求1到10的和。

![img](https://pic1.zhimg.com/v2-252fe4043d39b33e18f30ac754ae23f4_b.jpg)

<hr/>

#### 03 | while语句

```matlab
clear
clc
% 求1到10的和
T=0;
i=1;
while i<=10
    T=T+i;
    i=i+1;
end
```

我们使用while语句再次求1到10的和。

![img](https://pic3.zhimg.com/v2-e7945bb1a31cf412ff6d801d88f51c46_b.jpg)

<hr/>

### 二 | 6类函数

#### 01 | zeros、ones

```matlab
clear
clc
%测试 zeros、ones
A=zeros(3,4);
B=ones(3,4);
```

我们使用zeros函数创建3行4列的零矩阵，使用ones函数创建3行4列的1矩阵。

![img](https://pic2.zhimg.com/v2-1adf8234318cd95c4acbaedb13b16dc9_b.jpg)

![img](https://pic4.zhimg.com/v2-65a42a13d3ca0df18110f29c8333457b_b.jpg)

<hr/>

#### 02 | size、length

```matlab
clear
clc
%测试 zeros、ones、size、length
A=zeros(3,4);
B=ones(3,4);
[C,D]=size(A);
E=[5 3 2 4];
F=length(E);
```

我们使用size函数求矩阵A的行数和列数，使用length函数求数组E的长度。

![img](https://pic3.zhimg.com/v2-74945ec47c2edb8a0a6681c6ae9e8b16_b.jpg)

<hr/>

#### 03 | max、min

```matlab
clear
clc
%测试 max、min、isempty
E=[5 3 2 4];
[maxValue,maxIndex]=max(E);
[minValue,minIndex]=min(E);
```

我们使用max、min函数来求数组E中的最大值和最小值以及，最大值和最小值所在数组中的位置。数组E的最大值是5，在E中的第1个位置；数组E的最小值是2，在E中的第3个位置。

![img](https://pic1.zhimg.com/v2-8a20432ebab610108a4fe00214ceed64_b.jpg)

<hr/>

#### 04 | isempty

```matlab
clear
clc
%测试 isempty
X=[1,2;3,4];
Y=isempty(X);
```

我们使用isempty函数来判断矩阵X是否为空，如果为空，则Y=1，如果不为空，则Y=0。

![img](https://pic2.zhimg.com/v2-192317dec709f6c21da7f8b51a4790c5_b.jpg)

<hr/>

#### 05 | unique

```matlab
clear
clc
%测试unique
A=[9 9 8 7 6 7 6 8 1 1 0];
[B,C]=unique(A);
```

我们使用unique函数来删除数组中的重复元素，并将元素从小到大进行排序。B表示删除重复元素后从小到大元素的排列顺序，C表示B中每个元素在数组A中第一次出现的位置。

![img](https://pic4.zhimg.com/v2-6ffbeadb85b6a98d8f649f7c28a083e7_b.jpg)

<hr/>

#### 06 | cell

```matlab
clear
clc
%测试cell
A1=[1,2,3];
A2=[4,5,6,7];
A3=[8,9,10,11,12];
A=cell(3,1);
A{1,1}=A1;
A{2,1}=A2;
A{3,1}=A3;
```

我们使用cell函数创建元胞数组，用来储存不同长度的数组。

![img](https://pic2.zhimg.com/v2-a88c0016b77f1920bef2d72a79049ccd_b.jpg)

<hr/>

### 三 | 2类语法

#### 01 | 提取矩阵中某些元素

```matlab
clear
clc
%提取矩阵中某些元素
A=[1,2,3,4,5;
   6,7,8,9,10;
   11,12,13,14,15;
   16,17,18,19,20];
row1=A(1,:);
col1=A(:,1);
B=A(2:3,3:4);
```

row1表示提取矩阵A的第一行，col1表示提取矩阵A的第一列，矩阵B表示提取矩阵A的第2至3行，且第3至4列的元素。

![img](https://pic3.zhimg.com/v2-1322e13dc0b04b922679adb7f98a44fa_b.jpg)

<hr/>

#### 02 | 删除数组中某些元素

```matlab
clear
clc
%删除数组中某些元素
A=[1,2,3,4,5,6,6,6,7];
A(A==6)=[];
```

我们使用A(A==6)=[]将矩阵A中的元素6全部删除掉。

![img](https://pic2.zhimg.com/v2-fde040388994c1ed67e1b6d946d08d25_b.jpg)

## K-means算法简述

1. K-means算法，也称为K-平均或者K-均值，一般作为掌握聚类算法的第一个算法。
2. 这里的K为常数，需事先设定，通俗地说该算法是将没有标注的 M 个样本通过迭代的方式聚集成K个簇。
3. 在对样本进行聚集的过程往往是以样本之间的距离作为指标来划分。

- 简单Demo说明
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20190311222042700.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM4NTAyNzc=,size_16,color_FFFFFF,t_70)
  如上图以 K 为2，样本集为M 来描述KMean算法，算法执行步骤如下：

1. 选取K个点做为初始聚集的簇心（也可选择非样本点）;
2. 分别计算每个样本点到 K个簇核心的距离（这里的距离一般取欧氏距离或余弦距离），找到离该点最近的簇核心，将它归属到对应的簇；
3. 所有点都归属到簇之后， M个点就分为了 K个簇。之后重新计算每个簇的重心（平均距离中心），将其定为新的“簇核心”；
4. 反复迭代 2 - 3 步骤，直到达到某个中止条件。

- 注：常用的中止条件有迭代次数、最小平方误差MSE、簇中心点变化率；

由上述Demo可知，对于KMean算法来说有三个比较重要的因素要考虑,分别如下所述；

## K-means算法思考

1. **K值的选择**： k 值对最终结果的影响至关重要，而它却必须要预先给定。给定合适的 k 值，需要先验知识，凭空估计很困难，或者可能导致效果很差。
2. **异常点的存在**：K-means算法在迭代的过程中使用所有点的均值作为新的质点(中心点)，如果簇中存在异常点，将导致均值偏差比较严重。 比如一个簇中有2、4、6、8、100五个数据，那么新的质点为24，显然这个质点离绝大多数点都比较远；在当前情况下，使用中位数6可能比使用均值的想法更好，使用中位数的聚类方式叫做K-Mediods聚类(K中值聚类)。
3. **初值敏感**：K-means算法是初值敏感的，选择不同的初始值可能导致不同的簇划分规则。为了避免这种敏感性导致的最终结果异常性，可以采用初始化多套初始节点构造不同的分类规则，然后选择最优的构造规则。针对这点后面因此衍生了：二分K-Means算法、K-Means++算法、K-Means||算法、Canopy算法等。

## 常用的几种距离计算方法

通常情况下，在聚类算法中，样本的属性主要由其在特征空间中的相对距离来表示。
这就使得距离这个概念，对于聚类非常重要。以下是几种最常见的距离计算方法。

- **欧式距离（又称 2-norm 距离）**
  在欧几里德空间中，点 x=(x1,…,xn) 和 y=(y1,…,yn) 之间的欧氏距离为：
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20190311222437491.png)
  在欧几里德度量下，两点之间线段最短。
- **余弦距离（又称余弦相似性）**
  两个向量间的余弦值可以通过使用欧几里德点积公式求出：
  a⋅b=∥a∥∥b∥cosθ
  所以：
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20190311222534510.png)
  也就是说，给定两个属性向量 A 和 B，其余弦距离（也可以理解为两向量夹角的余弦）由点积和向量长度给出，如下所示：
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20190311222609696.png)
  这里的 Ai 和 Bi 分别代表向量 A 和 B 的各分量。
- **曼哈顿距离（Manhattan Distance, 又称 1-norm 距离）**
  曼哈顿距离的定义，来自于计算在规划为方型建筑区块的城市（如曼哈顿）中行车的最短路径。
  假设一个城市是完备的块状划分，从一点到达另一点必须要按照之间所隔着的区块的边缘走，没有其他捷径（如下图）：
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20190311222835442.jpeg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM4NTAyNzc=,size_16,color_FFFFFF,t_70)
  因此，曼哈顿距离就是：在直角坐标系中，两点所形成的线段对 x 和 y 轴投影的长度总和。
  从点 (x1,y1) 到点 (x2,y2)，曼哈顿距离为：
  |x1−x2|+|y1−y2|

## KMeans类的主要参数有：

1. n_clusters: 即k值，一般需要多试一些值以获得较好的聚类效果。k值好坏的评估标准在下面会讲。
2. max_iter： 最大的迭代次数，一般如果是凸数据集的话可以不管这个值，如果数据集不是凸的，可能很难收敛，此时可以指定最大的迭代次数让算法可以及时退出循环。
3. n_init：用不同的初始化质心运行算法的次数。由于K-Means是结果受初始值影响的局部最优的迭代算法，因此需要多跑几次以选择一个较好的聚类效果，默认是10，一般不需要改。如果你的k值较大，则可以适当增大这个值。
4. init： 即初始值选择的方式，可以为完全随机选择’random’,优化过的’k-means++’或者自己指定初始化的k个质心。一般建议使用默认的’k-means++’。
5. algorithm：有“auto”, “full” or “elkan”三种选择。”full”就是我们传统的K-Means算法， “elkan”是elkan K-Means算法。默认的”auto”则会根据数据值是否是稀疏的，来决定如何选择”full”和“elkan”。一般数据是稠密的，那么就是 “elkan”，否则就是”full”。一般来说建议直接用默认的”auto”
6. random_state:表示产生随机数的方法。默认情况下的缺省值为None，此时的随机数产生器是np.random所使用的RandomState实例。

## KMean 简单编码样例

```
import matplotlib.pyplot as plt
from sklearn.datasets import make_blobs  # 导入产生模拟数据的方法
from sklearn.cluster import KMeans

# 1. 产生模拟数据
k = 5
X, Y = make_blobs(n_samples=1000, n_features=2, centers=k, random_state=1)

# 2. 模型构建
km = KMeans(n_clusters=k, init='k-means++', max_iter=30)
km.fit(X)

# 获取簇心
centroids = km.cluster_centers_
# 获取归集后的样本所属簇对应值
y_kmean = km.predict(X)

# 呈现未归集前的数据
plt.scatter(X[:, 0], X[:, 1], s=50)
plt.yticks(())
plt.show()

plt.scatter(X[:, 0], X[:, 1], c=y_kmean, s=50, cmap='viridis')
plt.scatter(centroids[:, 0], centroids[:, 1], c='black', s=100, alpha=0.5)
plt.show()
```

代码运行结果：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190311222950318.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM4NTAyNzc=,size_16,color_FFFFFF,t_70)
归集后的数据图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190311223034234.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM4NTAyNzc=,size_16,color_FFFFFF,t_70)

## KMean算法的算法优缺点与适用场景

**优点：**

- 理解容易，聚类效果不错；
- 处理大数据集的时候，该算法可以保证较好的伸缩性和高效率；
- 当簇近似高斯分布的时候，效果非常不错。

**缺点：**

- K值是用户给定的，在进行数据处理前，K值是未知的，给定合适的 k 值，需要先验知识，凭空估计很困难，或者可能导致效果很差。
- 对初始簇中心点是敏感的。
- 不适合发现非凸形状的簇或者大小差别较大的簇。
- 特殊值(离群值或称为异常值)对模型的影响比较大。

论文
万维网（WWW）缺乏一个全面的网站目录。我们通过现代科技的机器学习等技术以网站主页的页面作为一个入口点，作为一个锚链接到各大网站。

由于人工很难将所有网站的数据整合在一起，所以通过访问界面将活跃网站2.5％的域名放置在那，供人们点击使用。而为了更方便简单的使用，在文章中作者尝试使用朴素贝叶斯机器学习算法，根据网站主页的内容对网站进行分类。

然而，web与传统的文本分类在一些地方是不一样的，又增添了额外的困难。web之间存在相互关联的特性，可以利用这些点，不同层次结构进行分类。

实验设置中提出：收集分类为不同类别的网站主页，获取数据集，清除各类样式表、脚本、HTML；对这些分类测试...


# LINUX操作系统

## 简介

Linux是一套免费使用和自由传播的类Unix操作系统，是一个基于POSIX和UNIX的多用户、多任务、支持多线程和多CPU的操作系统。它能运行主要的UNIX工具软件、应用程序和网络协议。它支持32位和64位硬件。Linux继承了Unix以网络为核心的设计思想，是一个性能稳定的多用户网络操作系统。 Linux操作系统诞生于1991 年10 月5 日（这是第一次正式向外公布时间）。Linux存在着许多不同的Linux版本，但它们都使用了Linux内核。Linux可安装在各种计算机硬件设备中，比如手机、平板电脑、路由器、视频游戏控制台、台式计算机、大型机和超级计算机。 严格来讲，Linux这个词本身只表示Linux内核，但实际上人们已经习惯了用Linux来形容整个基于Linux内核，并且使用GNU 工程各种工具和数据库的操作系统。



**一、Linux的目录结构**

**![img](https://pic1.zhimg.com/v2-87fc82d4d9d3df7829ac3bbe6de9e77c_b.jpg)/的下级目录**

- bin (binaries)存放二进制可执行文件
- sbin (super user binaries)存放二进制可执行文件，只有root才能访问
- etc (etcetera)存放系统配置文件
- usr (unix shared resources)用于存放共享的系统资源
- home 存放用户文件的根目录
- root 超级用户目录
- dev (devices)用于存放设备文件
- lib (library)存放跟文件系统中的程序运行所需要的共享库及内核模块
- mnt (mount)系统管理员安装临时文件系统的安装点
- boot 存放用于系统引导时使用的各种文件
- tmp (temporary)用于存放各种临时文件
- var (variable)用于存放运行时需要改变数据的文件

**二、Linux常用命令**

命令格式：命令 -选项 参数 （选项和参数可以为空）

```java
如：ls -la /usr
```

**2.1 操作文件及目录**

**![img](https://pic2.zhimg.com/v2-322c5e223eb6aff6970de5d809b29779_b.jpg)**

**2.2 系统常用命令**

**![img](https://pic3.zhimg.com/v2-e3d4510b9aa4bb783ca76636cba40e6e_b.jpg)**

**2.3 压缩解压缩**

**![img](https://pic3.zhimg.com/v2-661dea1db28f5366528c395e73ee17d6_b.jpg)**

**2.4 文件权限操作**

- linux文件权限的描述格式解读

![img](https://pic4.zhimg.com/v2-c91aff3fb083de498373ffd54c2a4ff7_b.jpg)

- r 可读权限，w可写权限，x可执行权限（也可以用二进制表示 111 110 100 --> 764）
- 第1位：文件类型（d 目录，- 普通文件，l 链接文件）
- 第2-4位：所属用户权限，用u（user）表示
- 第5-7位：所属组权限，用g（group）表示
- 第8-10位：其他用户权限，用o（other）表示
- 第2-10位：表示所有的权限，用a（all）表示

![img](https://pic4.zhimg.com/v2-a1ec85dcdabf4c14479305ed3ea26bcb_b.jpg)

**三、Linux系统常用快捷键及符号命令**

![img](https://pic4.zhimg.com/v2-8fbf60cf35b464101b26b050b5ddec4b_b.jpg)

**四、vim编辑器**

vi / vim是Linux上最常用的文本编辑器而且功能非常强大。只有命令，没有菜单，下图表示vi命令的各种模式的切换图。

![img](https://pic1.zhimg.com/v2-7596dd13d463df4ff05002d870727ab4_b.jpg)

**4.1 修改文本**

![img](https://pic2.zhimg.com/v2-22a7767d65ee9169133955f5159412d5_b.jpg)

**4.2 定位命令**

![img](https://pic3.zhimg.com/v2-a6ddc4c658c72dbee47fde3f64d2566e_b.jpg)

**4.3 替换和取消命令**

![img](https://pic2.zhimg.com/v2-c69afed2153d7e53b8766faa8ada6139_b.jpg)

**4.4 删除命令**

![img](https://pic3.zhimg.com/v2-9e90befe5c0f1abd4f6c72e9bbf97c2e_b.jpg)

**4.5 常用快捷键**

![img](https://pic3.zhimg.com/v2-959f561c6a6e4cda55e48a422bcc6002_b.jpg)


# 数据库的相关概念：

## 数据-data：

1.描述事物的符号

2.多种表现形式：文本，图形，音频，视频.



## 数据库-Database,DB

1.粮库，车库

2.存放数据的仓库在计算机中，按照一定的格式存放，可为用户共享.



## 数据库管理系统-Database Management System,DBAS

1.在数据库管理系统基础上，使用数据库管理系统的语法，开发直接面对最终用户的应用程序

2.学生管理系统，人事管理系统，图书管理系统.



## 数据库管理员-Database Administrator,DBA

1.数据库管理系统的操作者.



最终用户：

数据库应用系统的使用者.



## 数据库管理系统(DBMS)

1.DataBase Management System, 简称 DBMS, 用于科学的组织

和存储数据, 高效快捷的管理和维护数据.



## 数据库系统-Database System,DBS

1.数据库+数据库管理系统+数据库应用系统+数据库管理员+最终用户.



## 数据库法的发展阶段：

1.网状数据库.

2.层次数据库.

3.关系数据库.



## 关系数据库：

采用关系（二维表）结构储存与管理数据.

采用结构化查询（SQL）作为客户端程数据库服务器沟通的桥梁.

目前主流的数据库技术.



## 对象数据库：

把面向对象的方法和数据库技术结合起来可以使数据库系统的分析，设计最大程序与人们对客观世界的认识相一致.

![img](https://pic2.zhimg.com/v2-16866f5fb68d33a8116782dc08a9e791_b.jpg)

## NOSQL数据库：

Not Only SQL数据库泛指非关系数据库，如：Readis，MongoDB

2.关系数据库在超大规模和高并发的web2.0纯动态网站已经显得力不从心，暴露了很多难以克服的问题.

NOSQL数据库的产生就是为了解决大规模数据集合多重数据种类带来的挑战，尤其是大数据应用难题.



## 如何使用SQL plus连接Oracle：

1.在开始菜单中,找到oracle11g-应用程序开发-SQL PLUS.双击SQL PLUS.

2.弹出的SQL Plus框中,输入数据库实例的用户名和密码,按enter键.

3.如果oracle服务器中装有多个数据库实例,则在用户名处输入:用户名/密码@数据库名称.如果数据库服务器不在本机上,还需要加上数据库服务器的地址:用户名/密码@IP地址/数据库名称.

4.方法二:在开始-运行,输入cmd.弹出的黑色框中输入:sqlplus 用户名/密码@IP地址/数据库名称.



## 如何使用命令连接Pracle SQL Plus：

1.直接打开SQL Plus登录，需要用户名和密码

​    开始->程序->Oracle->应用程序开发->sqlplus

　　我的电脑是“开始”->“Oracle - OraDb11g_home1”->“应用程序开发”->“SQL Plus”

　　数据库安装完成后，有两个系统级的用户：

　　　　system    　默认密码:tiger

　　　　sys          　默认密码:tiger

2.进入cmd命令窗口，不使用用户名和密码

　　（1）登录sqlplus/nolog

　　（2）连接数据库：connect /as sysdba

　　（3）修改用户密码(例：修改sys用户密码为123）：alter user sys identified by 123;

注意有分号的地方不能省略，不然还会在输入后自动出现个“2”等待你继续输入。



![img](https://pic2.zhimg.com/v2-363f5497e1880becaa8cf12d6e2d4fbd_b.jpg)

# SQL语言基础 C

## 什么是SQL语言：

1.结构化查询语言（Structured Query Language）

2.SQL是最重要的关系数据库操作语言，是所有关系数据库管理系统的标准语言.

3.许多数据库厂商在使用SQL的同时，都对SQL进行了扩展，比如ORACLE的PL/SQL语言，MSSQL-Server的T-SQL语言.

4.SQL语言是一种非过程化语言，只需要提出“做什么”，而不需要指明“怎么做”.



## SQL可以做什么：

1.数据库数据的增删改查操作(CRUD)

2.数据库对象的创建，修改和删除操作.

3.用户权限/角色的授予和取消.

4.事务控制.



## SQL语言的分类：

DQL（数据查询语言）（要点）

1.selet



DML（数据操作语言）（要点）

.insert,update,dalete



DDL（数据定义语言）

.create,alter,drop

用于操作数据库对象



DCL(数据控制语言)

用于操作用户权限

.grant,revoke



TCL(事物控制语言)

用于管理事务

.SAVEPOINT,ROLLBACK,SET TRANSACTION,COMMIT

2.数据操作语言针对表中的数据，而数据定义语言针对数据库对象（表，索引，视图，触发器，存储过程，函数，表空间等）



select子句：

select * from tab;

查询所有表格-->*号的意思是表示所有的列，它是一个通配符./

## Select子句的作用，主要如下：

选择列表指出所查询列，它可以是一组列名列表、星号、表达式、变量，包括局部变量和全局变量等构成。

1、选择所有列

示例：显示test_table表中所有列的数据：SELECT * FROM test_table

2、选择部分列并指定它们的显示次序

查询结果集合中数据的排列顺序与选择列表中所指定的列名排列顺序相同。

3、更改列标题

在选择列表中，可重新指定列标题。

定义格式为：列标题=列名 列名 列标题，如果指定的列标题不是标准的标识符格式时，应使用引号定界符

例如，下列语句使用汉字显示列标题：SELECT 昵称=nickname，电子邮件=email FROM testtable

4、删除重复行

SELECT语句中使用ALL或DISTINCT选项来显示表中符合条件的所有行或删除其中重复的数据行，默认为ALL。

使用DISTINCT选项时，对于所有重复的数据行在SELECT返回的结果集合中只保留一行。

5、限制返回的行数

使用TOP n [PERCENT]选项限制返回的数据行数，TOP n说明返回n行，而TOP n PERCENT时，说明n是表示一百分数，指定返回的行数等于总行数的百分之几。

注：TOP命令仅针对SQL Server系列数据库，并不支持Oracle数据库。



字符串连接符：||.

Oracle当中，单引号用来表示字符串.

如查询：所有员工的姓名，职业，薪资，以姓名：xxx,职位：xxx，薪资：xxx的形式显示.

select '姓名：'||ename||',职业:'||job||',薪资:'||sal info form emp;



order by子句：用于排序



Distinct在SQL语句中的作用：

DISTINCT 这个关键词的意思是用于返回唯一不同的值。

在表中，可能会包含重复值。这并不成问题，不过，有时您也许希望仅仅列出不同（distinct）的值。SELECT DISTINCT 表示查询结果中，去掉了重复的行；Distinct表示去掉重复的行。

sql语句中使用DISTINCT的注意事项：

如果指定了 SELECT DISTINCT，那么 ORDER BY 子句中的项就必须出现在选择列表中，否则会出现错误。

比如SQL语句：SELECT DISTINCT Company FROM Orders order by Company ASC是可以正常执行的。

但是如果SQL语句是：SELECT DISTINCT Company FROM Orders order by Num ASC是不能正确执行的，在ASP中会提示“ORDER BY 子句与 (Num) DISTINCT 冲突”错误。

SQL语句修改成：SELECT DISTINCT Company,Num FROM Orders order by Num ASC可以正常执行


