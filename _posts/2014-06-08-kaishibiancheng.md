---
layout: post
title: 我该怎样开始学习编程？
description: 关于编程入门的博文
share: true
category: technical 
tags: [编程, Python]
---

这是我去年写的一篇文章，搬到这里来，做了一些修改。

经常有人问我这个问题。干脆写篇日志好了。虽然我不是什么牛叉程序猿，不过可以把我自身的经历分享一下，还有我觉得好的资源。


##我为啥要学编程？
---
其实问这个问题的多半是那些课程里面没有编程的人，理工科的同学我们这里直接不讨论了。这篇文章面向的主要是**用的到编程，但是觉得自学有困难**的同学。

拿我自己来说，我原本是经济系的本科生，为了学金融工程所以开始学编程了。其实我周围还有很多这样的同学，身处财经类院校，不小心被金融工程吸引，那么编程就是一个必须逾越的障碍。

其实财经类的学科现在越来越数理化，会点编程是个优势，起码不要让它成为你的劣势，如果在学术这条不归路上走下去，总有一天你会发现旁边的人个个都会编程，你要是不会就只能悲剧了。

另外一个主要的群体就是学统计的同学。如果你自豪的说你会用EXCEL，Eviews，STATA，而且觉得已经完全够用的话，当然也没问题。不过就冲着**R**和**Matlab**画出来的图好看一些你也该学学，这个区别完全可以决定谁是某某教授的研究助手。还有一方面，即使你去工作也好，处理Excel数据有没有一种让你想死的感觉？假如你可以编个VBA程序来处理呢？

纯文科的同学可以说你唯一能用到的软件就是word,难道也要学编程？我倒是觉得word还没有记事本好用，word简直是这个世界上最令人发指的文本编辑软件。你上百度搜一下“word对不齐”就可以看到无数回答帖，如果你没有在word排版的时候想摔电脑，在word03,07，10的版本之间切换的时候感到蛋疼，那还真是不容易。起码你可以学学**markdown**。五分钟就学会了，这个网站上的所有文章都是用Markdown编辑的。

如果你对自己架设一个像这样的博客感兴趣，那网站架设方面可以先尝试学下HTML和CSS。

## 我该学什么语言？

既然问这个问题，我们说的语言一定不是某个工具软件语言，比如Mathematica，Matlab这样的语言，是依托于其软件本身，用于特殊用途的。还有VBA，我们也不打算谈。我们要谈一谈能让你写应用程序的语言，无论是桌面端的也好，云端的也好，我们要选择一门语言能够跨平台，然后有广泛应用的，这样你学习这门语言才值得。

为什么这么说呢？因为刚开始学习编程的时候成本是很高的，你要花大量的时间去实践，每个人在编程遇到的问题都不一样，没有任何人能够帮你，你不仅需要去阅读一本本讲解语言的书籍，还需要把语言特性都用测试代码试一遍，这样你才记住，最后还要去做一个实际的工程，你才可以说某门语言你入门了。听到这里不要怕，后面会讲怎么帮助你尽量轻松的完成这个过程。

我认为你应该学的语言应该相对来说易学，然后又有大量的使用者，还应该本身具有完整的架构才行。

1.  易学的语言能够让你最快的做出东西来，不然你可能在此之前热情就被消耗殆尽了。
2.   有大量的使用者意味着你的问题基本上肯定有人遇到过了，那么你可以去论坛或者各种小组里面发问，只要你够礼貌一般都有人能回答你的问题，使用者多同时意味着你以后能够找到很多现成的源码，不用什么都自己动手编，使用者多也意味着你迟早有一天会遇到这种语言写成的东西，不要到时候脑门上三根黑线 。
3.  所谓有完整架构就是这门语言让你能够接触到尽量多的语言特性和范式

很多细节你现在不用了解。这样的语言的好处就是**它通常有很多延伸的语言**，你在学习延伸语言的时候可以省很多力，而且这样的语言能给你打下很好的基础，这样你在学习一门新的语言的时候会很快，这是很重要的，这样在长期你可以节省很多很多学习成本。

废话这么多，我觉得我你应该学习的第一门语言应该是Python或者C。下面讲讲为什么，又怎么学。

## 开始学习编程
---


###Python
     
如果你没听过这门语言也算正常。我相信你耳朵里面充斥的是VB,C,C++还有JAVA。

但其实现在在国内Python现在也已经渐渐流行起来，豆瓣就是用Python搭建的，同时MIT的本科现在主要用的语言也是Python。Python功能非常强大，毫不夸张的说，Python可以同时完成C++，Matlab,R的工作，并且很容易跟其它语言衔接，最重要的是它**容易上手**。

Python也是我学的第一门语言，这门语言的好处就是它的代码基本相当于伪码，你只要会读英语基本都能读懂。

比如说： 

{% highlight Python%}

print "Hello,world!"

{% endhighlight%}

你不要跟我说你看不懂这句话,它做的就是它字面的意思：`打印“你好，世界”`

如果是C++呢？那是下面这个样子：

{% highlight C++ linenos%}
#include <iostream>
using namespace std;

int main(){
       
   cout<<"Hello,world!"<<endl;
   return 0;

}
{% endhighlight %}

有没有一种想死的感觉？都什么玩意儿？不就是打印一句话么？干嘛搞这么复杂？

你的这个问题程序猿已经想过无数次了，也就是这种思想下诞生了Python这样的语言。当然了，人性化是要以程序的运行效率作为代价的，而你现在完全不需要担心这个问题。

程序人性化有什么好处呢？它能使你更专注于你要解决的问题本身，而不是在这门语言的特性上浪费时间，慢慢的你会知道C++的那种处理方式是有道理的，但是作为一个初学者你显然不希望受到这方面的困扰。

程序人性化同时使得你能够更快的学习，这样你就会觉得语言本身是你的一个工具，而不是你的负担。
          
那么怎么学习呢?

没有比上一门课更省心的了，你遇到的问题老师都替你考虑好了，你只要跟着走就好了。刚才说了，MIT本科生学的就是Python，你为啥不能学？你要是英语好的话，我建议你想办法翻墙(只有看视频需要翻墙，因为是放在Youtube上，下载文档是没问题的)去MIT的公开课主页上这门<a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00sc-introduction-to-computer-science-and-programming-spring-2011/" target="_blank">Introduction to Computer Science and Programming</a>。这是2011年版本的，很适合自学，而且你学完之后可以写个很漂亮的科学计算程序了，紧接着你马上就能学会Matlab，Mathematica或者Maple，完全不开玩笑，只要查下语法熟悉下就好了。如果你英语不过关或者不愿意翻墙，可以去网易公开课找这门`计算机科学及编程导论`,是08年录的，所有课程相关的文档，尤其是代码在<a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/index.htm" target="_blank">这里</a>。这门课还有第三个版本，<a href="https://www.edx.org/course/mitx/mitx-6-00-1x-introduction-computer-1841" target="_blank">到edX来上</a>，在这个地方你我觉得跟实际上课基本没啥区别了，有问题直接发论坛，还有助教解答问题,不过需要配合EdX开课的时间。

其实我可以负责任的说，学完这门课，你已经可以算会编程了，剩下的路就要靠你自己走了。不过我还是给你点辅助材料：

<a href="http://book.douban.com/subject/10561367/" target="_blank">如果你想笑着学编程的话 看这本深入浅出Python</a>

<a href="http://book.douban.com/subject/5338024/" target="_blank">与孩子一起学编程（不要被书名骗了……）</a>

<a href="http://sebug.net/paper/python/" target="_blank">简明Python教程 快速入门 新手参考手册</a>

<a href="http://www.codecademy.com/zh/tracks/python" target="_blank">Codecademy 网络上的动态语言教学 一边学一边就编程 记得牢</a>

基本差不多了，之后当然还有可以推荐给你的东西，但是我觉得你现在不需要。


###C

学C的好处多多啊。

你们学校要是有计算机系（别说没有，我不信！），他们不教C就是开玩笑。很多学校主要教的是JAVA，不过这个一般是对其他系的，你去上计算机系的课，他们要是不教你C那他们坑爹了……

C其实是一门很精干的语言，包含的内容并不多，不过它却确实能让你学到很多东西。有人说，C是一门很性感的语言，多一分嫌多，少一分嫌少（你以为是超短裙啊？）其实还是说到了要点了的。C不支持面向对象，不过却有其他类似的解决方法，这也是国内学生提到数据结构这门课就头大的原因，如果有面向对象，数据结构可以简单很多，扯远了，你就记住有些问题用C来解决不是最好的方法。
 
学C，你就可以迅速的拓展到它的延伸语言去，比如说C++,C#,PHP,JAVA,Objective C(可以用来编iphone程序)等等，这些都是主流语言，你学完C可以减少后面的学习成本,对于以C++为最终目标的人，C可以让你接触到很多底层的东西，这样你后面对C++的理解也更深。

C的运行效率很高，基本上操作系统都是用C写的，事实上C最初被设计出来就是用在UNIX操作系统上当操作语言的，Linux上也可以，不过现在你还用不到，你就记住很有用就是了。

还有C是一门做了很多年唯一的主流语言的语言，所以这世界上有太多太多用C写成的代码，你可以找到大量的源码，而且你的问题一定有人知道答案。

怎么学C呢？

第一个方法，也是最直接的，直接去学校选一门C的课吧，不管坑爹不坑爹，起码你能摸到老师的真人……

然后你英语好的话可以去这里看视频，不需要翻墙，不过没有字幕哈 <a href="http://www.wibit.net/" target="_blank">WiBit.net</a> (最近国内好像不太好连了)

不仅有C，还有C++，JAVA,C#,Objective C。其实是一个很连贯的课程系列，还有专门的计算机导论和面向对象理论的课程，而且这里的课程没有用到任何IDE，而是直接在Windows上调出cmd来用gcc直接编译，这样足够底层，利于你后面学习，也便于你集中精神在编程本身，而不是用哪个编译器上面，当然了，够装逼……

另外，其实C语言的创始人(缅怀)已经给我们留下了很好的教学材料,直接看这本书吧：

<a href="http://book.douban.com/subject/1139336/" target="_blank">C Programming Language</a>

这本书只有258页！这么薄的书却讲了那么多内容！实在太划算了。闭关一周就读完了，还包括敲完代码，所有习题答案网上一搜就有，哎，必备佳品。

然后我觉得你已经入门了。

等你学完C，你就可以去学你喜欢的语言了，C++也好，JAVA也好，Objective C也好。


##再来点资源
---
有木有一种拿来玩的语言呢？有的：<a href="http://scratch.mit.edu/" target="_blank">Scratch</a>

这是MIT发明的给孩子拿来玩的编程语言，但是什么都不缺，可以先从这个入手。绝对没有嘲笑你智商的意思，我觉得这个语言挺好的，马上就能做出一个动画来有木有。

还有<a href="http://www.coursera.org" target="_blank">Coursera</a>

这里有的是编程课，而且都跟edX一样是有作业考试还有论坛和助教的（只听不做也没关系，没成绩而已，有成绩的有个结业证）
       
还有CodeCademy： <a href="http://www.codecademy.com" target="_blank">http://www.codecademy.com</a>

这个主要是针对建站的，我觉得挺好，每天玩一玩，慢慢的就会编程了，毕竟网站建设需要会的东西太多了

最后是Udacity: <a href="https://www.udacity.com/" target="_blank">https://www.udacity.com/</a>

这就是把完整的编程课程搬到网上去了，需要翻墙。免费的，而且灵活度比Coursera还要大一些，我还没上过这里的课所以感受不多，不过都是大牛讲课。主要是课程的内容光从名字来看还不太清楚会教些什么，你需要做点研究。


我觉得就是这些了。

**Have fun !**