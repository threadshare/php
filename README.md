# php修行之路

## 目录


- [学习步骤](#学习步骤)
- [官方文档](#官方文档)
- [社区](#社区)
- [工具](#工具)
- [书籍](#书籍)
- [视频教程](#视频教程)
- [学习网站](#学习网站)
- [博客](#博客)
- [知识图谱](#知识图谱)

## 加群交流

微信群"PHP开发交流群"

由于微信群的限制，超过 100 人就不能扫码加群。所以可以先关注我公众号，然后发送 `PHP开发`，按照提示一步一步加群。

![PHP开发交流区群](http://img.blog.csdn.net/20161229104305784?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMjg4MzIxMzU=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

因为下面的视频教程大多数在我的云盘上存着，而且公开分享有可能获取不到，遇到这种情况也可以加群，进群之后我重新给你发链接，同时在这边及时更新。

## 学习步骤

### 第一阶段

1. 首先对HTML+CSS有一个基础的了解，做出一个简单的页面，感受一下网页开发的乐趣。（HTML+CSS）
2. 接着简单的学习一下JavaScript，了解网页的动态交互效果是怎么做出来的。（JavaScript）
3. 学习一点Linux基础课程，因为大多数的web站点都是部署在Linux服务器上的，所以你需要了解一下简单的Linux操作。（Linux基础）
4. 当你对这些都有一点基础的了解之后，这时候开始学习PHP语法的效果可能会更好。所以就开始你的PHP学习之路吧！（PHP语法）
5. 可能经过之前的了解，你知道大多数的PHP站点都是需要数据库的，这里我们一般说PHP和MySQL会更配哦！那么我的建议是MySQL确实是一个不错的选择。（MySQL数据库了解）
6. 当你有了这些基础知识之后，你已经可以创造一些简单的小玩意了！哦！这时候你可能会问我该在哪里跑我的程序呢？有了问题就要解决么！毕竟我们程序员的主要职责就是debug了。所以开始搭建你的LAMP环境吧！（注意：我这里说的是LAMP环境，可能大部分人用的是Windows系统，毕竟这也算是中国国情了么！而且确实在Windows上搭建WAMP环境对于不习惯使用命令行的人来说确实会方便不少，但是对于你以后在公司工作来说，这却不是一个很好的选择！是的，没错！公司90%以上使用的都是Linux系统。当你在学习刚开始的时候就用LAMP环境，这样你就能更好的适应公司的环境，毕竟Linux系统的命令行操作的命令那么杂，如果你不经常使用，过不了几天你学过的那些Linux基础就忘光了。之后还得增加学习成本来重新学习LAMP环境，那么一开始就使用它，何乐而不为呢？   -- 这里可能和前几个学习步骤有点冲突，毕竟当你翻开第一本PHP语法书的时候，他基本上讲的就是环境搭建，所以我这个步骤可能有点靠后了，这个就根据你个人的学习习惯来调整就好。如果你喜欢准备的万无一失在开始你的编程之旅，那么我按照这个学习顺序走就可以了！当然如果你之前已经了解过一点相关知识，那么别犹豫，直接搭建好环境开干！）
7. 要是你按照这个顺序已经学到这里了，那么现在开始做一个界面精美的留言本吧！一个留言本基本上就都考核了你的基础知识了。你可以用你学到的HTML+CSS，JavaScript做一个好看又有动态交互的界面。再用PHP语法来连接数据库，编写逻辑，操作数据。这些就考验了你对PHP语法的简单运用！然后你要是按照我第六条建议搭建的是LAMP环境，那么你在建表的时候就不免用到切换用户，进入目录，创建目录等等一系列Linux命令，当然了，对于新手来说，我的建议是在命令行下建表，这样更加有利于你对sql语句的学习。

### 第二阶段

到了第二阶段，可能对于热爱学习的你来说，已经不仅仅满足于做一个简单的留言本了！毕竟这对于现代的我们来说这可能已经是上个世纪的东西了，谁稀罕？  而且你可能这个时候已经慢慢的认识到了，现在已经是面向对象的世界了。俗话说“万事万物皆对象”，要是还用原生脚本来编写的话，虽然我得承认他们的速度是最快的，但是在这个需求多变的世界中，需求的改变时时刻刻都在发生，当然如果你的产品经理人不错的话，他可能会提前给你确定好大部分的需求，这样你改动的时候可能会少一点。可惜天不遂人愿，他们大多被叫做产品狗，意思你自己体会去吧。这样你如果用原生写出来的项目，只要有一点点的变动，你可以自己试试，看看会不会把你整的喊爸爸。
这样，为了我们自己的身体健康，我们就需要有一种高度封装的代码，耦合性极低，大家谁都不影响谁，你让我改动这一块，我就仅仅需要动这一块就好了。而且你想用我这一个功能，随便用，你只要按照我给你的那个属性直接用就行！谁让我们牛逼了。看到这儿，你是不是对这个神奇的东西有了很大的期待啊？没错，这个神奇的东西就是我们上面说的面向对象的思想。相信我，当你真正掌握了面向对象的思想，你就会感受到人间自有真情在。

 - 上面大体的说了一下面向对象的好处，现在我们就来学习一下吧！这个时候就应该学学PHP的进阶内容了，关于PHP的面向对象编程，我们需要了解命名空间，类，继承，接口，类自动加载等等（PHP面向对象编程）。这个面向对象的思想是最难转化的，可能你已经习惯了面向过程编程，感觉逻辑就是应该按照你的思路来走，刚刚上手面向对象编程，你可能会觉得很变扭。但是，相信我，在前期你可能需要强迫一下自己，当你真正熟悉了oop之后你可能就再也离不开他了。

 - 上面说完了PHP的面向对象编程，那么我们就该思考一个问题了。我的逻辑编码已经有那么一点点登堂入室的感觉了，但是发现在连接数据库的时候还是使用的是原来的连接方式感觉好变扭啊，而且万一哪天我心情不好，想换个数据库玩玩，那我还得把这段连接代码删除，找到专门连接其他数据库的连接方式。有没有一些一劳永逸的方法呢？别担心，已经有大神为我们解决了。下面我们就说说进阶的第二个话题-数据库。在这里我介绍两个oop方式的数据库扩展（PDO，mysqli）。PDO已经实现了通过对象封装让我们用一段代码可以随意切换数据库，做到了想换就换，心随我动。而mysqli是MySQL的进阶版本，现在官方推荐的是这个。（PDO，mysqli）

 - 当然这是说的我们后端的进阶，那么可能有的同学就说了，写前端的JavaScript也好费劲，调用一个简单的id就需要写那么一长串代码，好费劲啊！别担心，这就是我要给你们介绍的JavaScript的进阶jQuery，他对原生的dom进行了封装，让你用更少的代码来完成更多的事儿，同时他又是看着那么简洁，优雅。毕竟我们可是高贵的程序猿，可不是民工。追求的是艺术和科技的结合。（jQuery）

第二阶段是改变你的思维方式，让你换个思路去看世界。思想变过来了，我们不妨用我们这一阶段学到的东西，来吧你的之前做的留言本，全都换成面向对象编程。这样你可能就感受到它的魅力了。

### 第三阶段

当你完成了上面两个阶段，如果你是一步一个脚印的来走的话。我相信的摩天大楼就在你的眼前。那还等什么，赶快建起高楼，走上人生巅峰，迎娶白富美吧！但是，要是我们还是像之前那样打地基一步一个脚印的去盖的话，那这摩天大楼何时才能完工呢？这个时候我们就需要站在巨人的肩膀上来实现了。我们只需要把摩天大楼装修的漂漂亮亮的就好，至于搭建脚手架这种事让巨人去帮你做吧。所以第三阶段我们就需要学习如何使用框架了。毕竟前人栽树后人乘凉，我们只需要拿来用就好。这里我介绍几个当前PHP主流的框架，也是我经常使用的这几个（Laravel，Yii，Thinkphp）。
 - Laravel是以PHP最优雅的框架来著称的，它运用了很多先进的思想，优雅的设计。在你使用它的时候你会感觉你在打造的是一个艺术品。不过又有点就会有缺点，因为他先进的思想，优雅的设计导致他相比较其他框架来说反应有点慢，毕竟贵族永远都是那么慢条斯理。
 
 - Yii就想一个朝气蓬勃的青年，他快捷，高效，安全，当你使用它的时候你会感觉非常顺手。
 
 - Thinkphp是国内的一个框架，他是我认识的第一个框架，他非常的简洁，给了你极大地便利，当你想要使用它的时候，你可以把它捡起来，不需要的话，随手扔掉就好。但是他有一个我不能忍受的缺点就是他有一些函数的命名仅仅使用一个字母来命名，虽然简洁，就我本身而言我感觉极其不友好。
 上面就是我介绍的几个框架，俗话说：一法通百法通，当你能深刻的理解一个框架的时候，在上手其他框架的时候，仅仅是表达方式上的不同。
 
 下面我们介绍几个前端框架，让我们写界面也能写的更加优雅：（bootstrap，Vue，angular.js）
 
 - bootstrap这个框架可以说是后端程序员的福音，对于一个讨厌写界面，而且写出的界面毫无美感的你来说。bootstrap里面的栅格系统，会让你只关心你的逻辑实现，至于界面的话很简单的就能搭建出一个简洁优雅的界面来。
 
 - Vue 这可以说是一个跟得上潮流的框架，它的MVVM模式，数据绑定的思想都可以让你更加方便的来调用后台数据，而且他及其小巧，更加方便你的定制。现在好多公司都在在它的基础上来搭建内部脚手架。所以学习他，绝对是一个不错的投资。
 
 - angular.js 相信程序猿没有听过Google的应该很少吧。没错他就是Google开源出来的一个框架，相信质量是一定有保障的。而且他火热的社区氛围，也保障了它的生命力。他也用了MVC的模式，可以实现双向数据绑定。这么多的优点，难道你就不心动么？
 
 
 ### 第四阶段
 
 对于已经走完以上几个阶段的人最容易出现的问题就是PHP好简单啊！PHP在手，天下我有的感觉。感觉再也没有了当年学习的热情，尤其是你还做过一些零零散散的项目，更是觉得在PHP上有更大的进步空间。我当年也是这样，感觉谁都很菜，自以为已经深谙PHP之道了。有这种感觉很正常，毕竟PHP非常简单，甚至最难的数据结构都已经有大神给你封装成函数，随便掉用即可。但是PHP简单，可是web开发可是博大精深啊。在这个阶段，你就需要往更深层次来走了，虽然还没达到研究PHP内部实现的程度，但是下面我说的这些知识已经够你专研一阵子了。
 
  - 首先从上个阶段你对框架的运用，你已经理解到MVC模式的思想了么？这个时候就是需要你去了解的了。（MVC）
  
  - 看着大神给你搭好的脚手架，你现在光是会用，难道对他们神奇的封装一点都不好奇么？为什么这样调用，你就能实现你想要的功能？所以是时候自己尽自己最大的努力搭建一个你自己的脚手架了，即使你自己将来不用，但是如果你自己写一遍的话，你就能对框架的宏观搭建有一个更深的了解。（搭建自己的框架）
  
  - 同样的话对前端框架也是有用的，当然如果你是主攻后端的话，我的建议是那你只要简单了解一下内部思想就好了。毕竟编程编的是思想，所不定他的思想是对你有用的，那么你可能就会搭建出一个更好的框架，变成传说中的大神。
  
  - 你在第三阶段的时候有没有感觉，有时候你解决某个逻辑的时候想到了一个特别好的解决方法，为此你还高兴不已。但是我要告诉你，在此之前可能对于一个资深工程师来说这就是一个简单的设计模式，已经被用了好多年。所以这个阶段我推荐你去看一下设计模式的书，在之前大神们已经给出了23中设计模式。他们都是思想的精华，值得你仔细研读。（设计模式）
  
  - 还有你之前可能只是简单的传值，但是你却不知道他们内部是怎么做到的，也有可能你知道，但是却不是很清楚。所以在这个阶段我推荐你看看HTTP协议，TCP/IP原理，Apache服务器内部配置，Auth协议。这些已经涉及到了一些内部原理，他可能枯燥无味，但是这些知识绝对是你成神路上必不可少的东西。（HTTP，TCP/IP，Apache，Auth协议）
  
  
 达到上面这些程度的，可以说你已经很厉害了，带领一个小团队基本不成问题。但是如果我想成为业内的大神该怎么办呢？这个时候你就需要往更深的程度发展了，比如说服务器，PHP原理什么的，因为我自己也在摸索，所以对于更高的程度也。。。。。



## 官方文档

- [PHP手册](https://secure.php.net/manual/zh/index.php)
- [JavaScript 参考文档](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference)
- [HTML教程](http://w3school.com.cn/html/index.asp)
- [css3教程](http://www.w3school.com.cn/css3/)
- [css教程](http://www.w3school.com.cn/css/)
- [mysql教程](http://www.runoob.com/mysql/mysql-tutorial.html)
- [MySQL PDO教程](http://www.runoob.com/php/php-pdo.html)
- [MySQLi 函数](http://www.w3school.com.cn/php/php_ref_mysqli.asp)
- [jQuery API 中文文档](http://www.jquery123.com/)
- [Vue.js教程](https://vuejs.org.cn/guide/)
- [AngularJS](http://www.apjs.net/)
- [Yii文档](http://www.yiichina.com/doc)
- [Laravel5.1教程](http://www.golaravel.com/laravel/docs/5.1/)
- [ThinkPhp手册](http://doc.thinkphp.cn/manual/)

## 社区
- [StackOverflow](http://stackoverflow.com/)
- [SegmentFault](https://segmentfault.com/)
- [github](https://github.com/)
- [Yii](http://www.yiichina.com/)
- [Vue中文社区](http://www.vue-js.com/)
- [angular中文社区](http://angularjs.cn/)
- [bootstrap](http://www.bootcss.com/)
- [Laravel社区](https://laravel-china.org/)



## 工具
- [PHPstorm](https://www.jetbrains.com/phpstorm/)
- [Sublime](https://www.sublimetext.com/3)
- [Notepad++](https://notepad-plus-plus.org/download/v7.2.2.html)
- [SQLyog](https://www.webyog.com/product/sqlyog)
- [centos 6.5 nginx安装与配置](https://gist.github.com/ifels/c8cfdfe249e27ffa9ba1)
- [CentOS上使用yum安装Apache](http://www.splaybow.com/post/centos-yum-apache.html) 
- [CentOS6.4下Mysql数据库的安装与配置](http://www.cnblogs.com/xiaoluo501395377/archive/2013/04/07/3003278.html)
- [Composer](http://www.phpcomposer.com/)
- [npm中文文档](https://chenyiqiao.gitbooks.io/documentation_for_npm/content/)


## 书籍

- [Bootstrap用户手册：设计响应式网站](http://pan.baidu.com/s/1i5si3xN)
- [PHP-Debug-Manual-public](http://pan.baidu.com/s/1jIc7uo2)
- [Computer Science Made Simple Learn How Hardware And Software Work](http://pan.baidu.com/s/1bpzMjMJ)
- [大话设计模式](http://pan.baidu.com/s/1hrCndoK)
- [yii2forbeginners](http://pan.baidu.com/s/1o8Rki5W)
- [HTTP权威指南](http://pan.baidu.com/s/1gf7fAnT)
- [TCP/IP三卷经典](http://pan.baidu.com/s/1o7KOpjO)

## 视频教程

下面这些视频是我在学习过程中看过的，感觉讲的比较清晰的，根据学习的难易程度依次往下排序的：

### 第一阶段

1. [HTML视频](http://pan.baidu.com/s/1dE6T3IL)
2. [CSS视频](http://pan.baidu.com/s/1mhYz11I)
3. [JavaScript视频](http://pan.baidu.com/s/1c1DHcHy)
4. [php快速入门](https://pan.baidu.com/s/1PgvDt9yfDtpRAwonxMKBG) 提取码: yraj
5. ~~[php基础巩固](http://pan.baidu.com/s/1pLnm4Wj)视频太老了 不适合现在学习了  可以看书或者之有合适的再分享出来~~  
6. ~~[PHP深入理解](http://pan.baidu.com/s/1dEFaXkH)视频太老了 不适合现在学习了  可以看书或者之有合适的再分享出来~~  
7. [Linux入门](http://pan.baidu.com/s/1boJiPXH)
8. [MySQL入门](http://pan.baidu.com/s/1kV7Dx59)
9. [Apache简介](http://pan.baidu.com/s/1hrJE8TY)
10. [LAMP经典入门](http://pan.baidu.com/s/1bp1ifE3)

### 第二阶段

1. [PDO详解](http://pan.baidu.com/s/1skQNL2d)
2. [jQuery](http://pan.baidu.com/s/1miqa188)
3. [HTML5视频](http://pan.baidu.com/s/1nvGwQa1)
4. [CSS3视频](http://pan.baidu.com/s/1hsjxaYC)
5. [php面向对象编程](http://www.imooc.com/learn/184)

### 第三阶段

这一部分的框架学习，我感觉直接进入实战，然后结合官方文档效果比较好，相反要是结合一些基础视频反而显得有点儿啰嗦！适合自己就好。（这一部分视频是我从网上收集来的，可能会涉及到侵权问题导致分享失败，如果特别需要可以加我微信之后和我说一下-zzc960316）

1. [zend framework](http://pan.baidu.com/s/1boCxpmB)
2. [Yii2.0全力出击打造完整电商平台](http://pan.baidu.com/s/1o7JAHjc)
3. [前端到后台ThinkPHP开发整站](http://pan.baidu.com/s/1kVFTrMZ)
4. [知乎实战laravel](http://pan.baidu.com/s/1dFgnE9r)
5. [6小时jQuery开发小应用无密码](http://pan.baidu.com/s/1b2yhg6)
6. [vue实战](http://pan.baidu.com/s/1nuHAQyl)
7. [从零开始打造自己的PHP框架](http://www.imooc.com/learn/696)

### 第四阶段

我感觉这一阶段更适合读书，读一些讲解原理的书，而且也没有什么太好的视频。
1. [OAuth2.0协议](http://www.imooc.com/learn/557)
2. [mysql优化](http://pan.baidu.com/s/1jHM0FjC)
3. [数据结构与算法1](http://pan.baidu.com/s/1b0nXvS)
4. [数据结构与算法2](http://pan.baidu.com/s/1pL2fDaj)


## 学习网站
1. [慕课网](http://www.imooc.com/course/list?c=php)   可以让你及时了解最新的技术，也有一些小的知识点讲解的非常不错。
2. [计蒜客](https://www.jisuanke.com/)   这里的课程大多数是cs，偏向理论，非常不错，但是收费。
3. [实验楼](https://www.shiyanlou.com/)   你可以在这里及时编码，知识讲的也不错，可以来看看。

## 博客

博客这个会随时更新，遇到比较好的就会放上来。

1. [张智超的博客](http://blog.csdn.net/qq_28832135)
2. [刘伟技术博客](http://blog.csdn.net/lovelion/article/details/17517213) 这个设计模式讲的不错
3. [鸟哥的博客](http://www.laruence.com/)  这是大神的博客，值得关注
4. [张宴de博客](http://zyan.cc/category/15/)

## 知识图谱

我会添加一些比较好的知识图谱，持续更新。。。

 - [php开发图谱](http://lib.csdn.net/qq_28832135/chart/php开发)  这是我在CSDN创建的一个知识图谱，因为受邀知识库的特邀编辑，我每天会审核一些PHP的博文，如果比较好的话，在我审核后，我会顺手加到我的个人图谱中，有兴趣的可以关注一下。







