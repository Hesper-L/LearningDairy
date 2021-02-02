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
