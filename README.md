生信的作用越来越大，想学的人越来越多，不管是为了以后发展，还是为了解决眼下的问题。但生信学习不是一朝一夕就可以完成的事情，也许你可以很短时间学会一个交互式软件的操作，却不能看完程序教学视频后就直接写程序。也许你可以跟着一个测序分析流程完成操作，但不懂得背后的原理，不知道什么参数需要修改，结果可以出来，却把握不住对还是错。

学习生信从来就不是一个简单的事，需要做好持久战的心理准备。

在学习时，我们都希望由浅入深的逐步深入，不断地练习和实践，这就是为什么我们需要一本书，因为书很系统。但生信发展的历史短于计算机编程的历史，如果想要一门程序设计的入门数据，每种语言都可以找到几本。但想要一个囊括生信的书，就有些难了。本身生信跨领域，需要多学科的知识，而其内部又有不少分子，都囊括了太大，包括的少又有些隔靴搔痒的感觉。

我们当时都是零基础下自学Linux,  自学Python，自学R，自学高通量测序；这些学习经历，之前都零星地记录在博客里。现在回头去看几年前自己记录的东西，觉得好简单，而当时却费了很大的力气。这些零星的随手记，当时也只是为了自己看，到现在确实只有自己能看得懂，不便惠及更多的人。

因此我们创建了生信宝典，希望从不同的角度传播知识。这个不同有三点含义，一是形式上的不同，摒弃之前主编们单人作战想写啥就写啥，而是有组织有计划的内容聚合，提供一系列的教程，由入门到提高。二是内容的不同，不去用网上现有教程的通用数据做例子，而是拿实际生物数据，讲述如何解释生信中普遍碰到的问题，讲述如何处理自己的数据。三是立足点不同。在写作时，我们回到了当年，在回忆中用整个阶段的学习去指导当初的那个小白，从那些会了的人觉得微不足道而不会的人又迈不过的坎入手，直击痛点。知识点的收录依据不是是否炫酷，是否难，而是是否必要。如果必要，再简单，也要提及；如果不必要，再炫酷，也暂不纳入。

通过大量的生信例子、关键的注释和浓缩的语句形成下面的一系列学习教程。每一篇内容都不多，可以当做小说阅读，也可以跟着去练，反复几遍，每读一次都会有不同的收获和体会。

### Linux 全介绍

* [免费Linux系统和生信宝典原创学习教程](https://mp.weixin.qq.com/s/rXjQfyEX2FnuW9HTM_Uc8Q)
* [PATH和path，傻傻分不清](https://mp.weixin.qq.com/s/AMx4y8FSiWYdrntkFnKlmg)
* [Linux - 总目录](http://mp.weixin.qq.com/s/hEYU80fPf1eD5OWL3fO4Bg)
* [Linux - 文件和目录](http://mp.weixin.qq.com/s/yKP1Kboji9N4p2Sl1Ovj0Q)
* [Linux - 文件操作](http://mp.weixin.qq.com/s/4bYMzJclf_xHpqdrlbvAdA)
* [Linux - 文件内容操作](http://mp.weixin.qq.com/s/QFgINAYcQA9kYYSA28wK-Q)
* [Linux - 环境变量和可执行属性](http://mp.weixin.qq.com/s/poFpNHQgHDr0qr2wqfVNdw)
* [Linux - 管道、标准输入输出](http://mp.weixin.qq.com/s/zL9Mw_2ig48gHrIjKM0CMw)
* [Linux - 命令运行监测和软件安装](http://mp.weixin.qq.com/s/TNU7X2mhfVVffaJ7NRBuNA)
* [Linux - 常见错误和快捷操作](http://mp.weixin.qq.com/s/cDIN4_R4nETEB5irmIGFAQ)
* [Linux - 文件列太多，很难识别想要的信息在哪列；别焦急，看这里。](http://mp.weixin.qq.com/s/1QaroFE7AH1pREuq-k2YAw)
* [Linux - 文件排序和FASTA文件操作](http://mp.weixin.qq.com/s/R1OHRhZoDJuAdyVdJr2xHg)
* [Linux - 应用Docker安装软件](http://mp.weixin.qq.com/s/HLHiWMLaWtB7SOJe_jP3mA)
* [Linux - Conda软件安装方法](http://mp.weixin.qq.com/s/A4_j8ZbyprMr1TT_wgisQQ)
* [Linux - 服务器数据定期同步和备份方式](http://mp.weixin.qq.com/s/c2cspK5b4sQScWYMBtG63g)
* [Linux - VIM的强大文本处理方法](https://mp.weixin.qq.com/s/4lUiZ60-aXLilRk9--iQhA)
* [Linux - 查看服务器配置信息](http://mp.weixin.qq.com/s/xq0JfkHJJeHQk1acjOAJUQ)
* [Linux - SED操作，awk的姊妹篇](http://mp.weixin.qq.com/s/cywkIeRbhkYTZvkwTeIVSA)
* [Linux - 常用和不太常用的实用awk命令](http://mp.weixin.qq.com/s/8wD14FXt7fLDo1BjJyT0ew)
* [Linux - 那些查找命令](http://mp.weixin.qq.com/s/xWwj04h4W6yEqQLOfuQ8qA)
* [Linux - 原来你是这样的软连接](https://mp.weixin.qq.com/s/q3ic5WSfLdAnqIhFQX-bUQ)
* [Bash概论 - Linux系列教程补充篇](http://mp.weixin.qq.com/s/lWNp_6W_jLiogmtlk9nO2A)
* [Nature Method：Bioconda解决生物软件安装的烦恼](https://mp.weixin.qq.com/s/VeexRyguwozqrMaOeeMF7Q)
* [Linux下文件内容更新了文件夹时间戳却没变？](https://mp.weixin.qq.com/s/Qqmliz5E_cXBF8y8CUyPeQ)
* [如何获取目标基因的转录因子（上）——Biomart下载基因和motif位置信息](https://mp.weixin.qq.com/s/ZUlVq6IVEqZb0KTPCFCkiw)
* [如何获取目标基因的转录因子（下）——Linux命令获取目标基因TF](https://mp.weixin.qq.com/s/XjefeIpMHJCN0Crh-GfVDQ)
* [生信人写程序1. Perl语言模板及配置](https://mp.weixin.qq.com/s/SlTnNQ1K1EEIIif0FmWj8w)
* [生信人写程序2. Editplus添加Perl, Shell, R, markdown模板和语法高亮](https://mp.weixin.qq.com/s/8Dibze-qvEmKjgnLfjKTeg)
* [手把手教你生信分析平台搭建](https://mp.weixin.qq.com/s/6BPvNOw854pkdJCklelGWQ)
* [Windows轻松实现linux shell环境：gitforwindows](https://mp.weixin.qq.com/s/KtM4c4o4iLfD4ZkEnMi1pg)
* [开启win10内置Linux子程序](http://mp.weixin.qq.com/s/d8V6P74-wDM864wbvp1tNw)
* [Docker的基本使用-Ubuntu18.04](https://mp.weixin.qq.com/s/GFukUTZNj2Ym4aPh4ZvC7Q)
* [Linux命令screen—终端切换，工作环境保存，画面同步，防断网](https://mp.weixin.qq.com/s?__biz=MzUzMjA4Njc1MA==&mid=2247485554&idx=1&sn=66d9c0bbcb813f2db453eba3171cb351&scene=21#wechat_redirect)
* [Bioconda软件安装神器：多版本并存、环境复制、环境导出](https://mp.weixin.qq.com/s/ofWPmUIz3fJS64dAwa1mbg)
* [收藏(附中奖信息) | 15 个你非了解不可的 Linux 特殊字符，妈妈再也不用担心我看不懂这些符号了！](https://mp.weixin.qq.com/s/oyuMgALk6J5MPfWfLyJ4tA)
* [有了这些，文件批量重命名还需要求助其它工具吗？](https://mp.weixin.qq.com/s/hyiGxm0jx6xEc90nHLN4dQ)
* [软件安装不上，可能是网速慢！Conda/R/pip/brew等国内镜像大全拿走不谢~~](https://mp.weixin.qq.com/s/eIw-k6RcR5KQFbrNmBsWBw)
* [耗时很长的程序忘加nohup就运行了怎么办？](https://mp.weixin.qq.com/s/kt_e-DCq7xBfh9tTCJinZQ)

![](http://www.ehbio.com/ehbio_resource/Linux_course.png)

视频课程地址：<https://ke.qq.com/course/288048?tuin=20cd7788>


