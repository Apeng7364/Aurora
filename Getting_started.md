# 信安协会入门指引

## CTF 

### 相关站点 

CTF WIKI:
https://ctf-wiki.github.io/ctf-wiki/

### 入门平台

cgctf和攻防世界的新手区是面向萌新的CTF平台，题目非常简单。可以到这两个平台做题学习。

cgctf：https://cgctf.nuptsast.com/challenges
攻防世界：https://adworld.xctf.org.cn/task
中科大新生赛：https://hack2018.lug.ustc.edu.cn/
bugku：https://ctf.bugku.com/

## WEB

1. 首先，大略过一下最基础的语言语法HTML／CSS、JavaScript、PHP、SQL的基本知识（平均一个语言4小时足矣），要做到看到这些代码的时候不会畏惧，能看懂大部分，看到不懂的能通过google或者相关文档查懂。主要参考：<http://www.w3school.com.cn/> 、<http://www.runoob.com/>，这里不要求学很深，很浅很浅就行，后面边学边用掌握的会更快。
2. 现在，你初步了解了一些语言知识，接下来你就需要开始在实践中学习与巩固。
3. 当然就是实践了。这里，我建议你搭建一个个人的博客，初步了解这些语言的应用。在搭建博客的过程中，你需要学习对应的linux操作、Apache+PHP+Mysql环境的配置、域名解析、服务器端口配置等等。如何搭建博客，请自行google搜索。此外，你也可以编写一些好玩的网页来学习这些知识点。

如果你能完成如上所说的这些，尤其是第三点，那么恭喜你，你入门了，其实这些前期会遇到很多语言方面难免会遇到挫折，但是没关系，多百度多谷歌，多群里提问，我们都会及时给你解答，也可线下教学，直接到理工楼L3-1001。基本全天都有人。

接下来可以了解基本的HTTP协议相关知识

- 掌握HTTP请求：GET、POST、HEAD，能基本读懂一个HTTP数据包，了解GET、POST、HEAD的区别
- 能看懂HTTP响应包 404 403 200 500 302 301 …
- 了解Cookie、session、token，知道是什么东西，作用是什么，为什么需要这些东西
- 了解Referer、X-Forwarded-For等等的作用

学漏洞知识点之前，如果你了解了如上所说的一些东西，那么就可以学习下面的知识(进阶)啦，当然能学懂上面的知识可能需要大概3周左右的时间，多坚持，多提问。

1、sql注入

2、XSS攻击

3、文件上传漏洞

4、文件包含漏洞

5、命令执行漏洞

。。。

推荐一些学习站点：

<https://ctf-wiki.github.io/ctf-wiki/>

<https://xz.aliyun.com/>

<https://www.anquanke.com/>

<https://github.com/CHYbeta/Web-Security-Learning>

推荐一些题库：

<https://cgctf.nuptsast.com/login>

<https://www.jarvisoj.com/login>

推荐一些大牛的博客：

<https://chybeta.github.io/>

<https://www.jianshu.com/u/bf30f18c872c>

<https://skysec.top/>

<https://lorexxar.cn/>

。。。

推荐书籍：
《白帽子讲web安全》
《黑客攻防技术宝典·Web实战篇》

## 逆向工程

逆向工程，Reverse，缩写一般为Re。旨在不知晓源码的情况下对程序进行分析，获取其流程，组织，结构等。CTF中一般为注册机这种形式。

最好会C语言和汇编语言，不必系统的学习汇编，上来先一条一条查指令手册，等熟悉了再仔细学习。
需了解常见加密算法的实现，要做到快速识别，无需了解攻击过程。

### 推荐书籍

《汇编语言》（王爽）
这本比较老了，讲的8086汇编，但是讲的很好。

《加密与解密》（第四版）（看雪论坛）
看雪出的经典书籍，名叫加密与解密实际上是讲逆向。各方各面都有讲到，很全面。

《逆向工程核心原理》
主要是windows逆向，以OD为主要工具。讲的很好，面向零基础。

下面的我没看过，不好评价。。。
《Reverse Engineering for Beginners》(电子书：https://beginners.re/)（中文版为《逆向工程权威指南》）
《Android应用安全防护和逆向分析》
《Android软件安全与逆向分析》

### 常用工具

IDA Pro
极其强大的反汇编/反编译/调试工具，二进制选手必须会用，优秀的二进制选手能把IDA运用到出神入化的地步。有关IDA的使用能讲好多好多。
吾爱破解论坛爱盘下载。

x64dbg
Windows平台优秀的开源反汇编器及调试器，可以看作Olly dbg的升级版，基本包含OD的全部功能，且一直在更新
官网下载。

gdb
Linux的调试器，没有GUI。pwn选手必须掌握的技能。也可以使用IDA的远程调试功能调试linx程序。
一般的Linux自带，没有的话apt安装。

Jeb
apk反编译工具，功能强大。

jadx
开源的apk反编译工具，轻量级

其他
dnSpy，xspy，CFF explorer等各类专用工具，需要靠做题中积累。

### 论坛与站点

汇编语言指令学习：https://www.cnblogs.com/del/category/121079.html
这一系列文章细致的讲解了win32汇编，遇到不认识的指令可到这里查询（当然直接翻intel指令手册是最准确的）

吾爱破解：知名破解论坛，注册有限制，需要10元注册或等开放。吾爱的爱盘内有大量常用工具，以及逆向专用虚拟机，可按需学习与使用。
https://www.52pojie.cn/

看雪论坛：知名逆向论坛
https://bbs.pediy.com/

安全客、先知等各类安全论坛，上面有各种大佬发的文章。

## PWN

pwn，及pwn to own，在黑客俚语中由own演变而来。通过逆向分析二进制程序，发现其可能存在的漏洞，并进行利用，从而达到信息泄露、权限获取等目的。

需要掌握汇编语言、基础逆向方法。
入门推荐到CTF wiki的pwn板块学习，上面有及其详细的pwn教程，各类漏洞点及利用。

CTF一般为linux环境下的pwn，要熟悉linux的使用。
IDA Pro 强大的反编译工具，有了它就能轻松审计漏洞了。
gdb为做pwn题时调试必备的工具，网上有非常多关于gdb的教程。
pwndbg——gdb插件：https://github.com/pwndbg/pwndbg
pwntools为专门用来做pwn题的工具，所以要学习python与pwntools。

其余学习教程：
一步一步学ROP系列：
http://wooyun.jozxing.cc/static/drops/tips-6597.html
http://wooyun.jozxing.cc/static/drops/papers-7551.html
http://wooyun.jozxing.cc/static/drops/binary-10638.html
http://wooyun.jozxing.cc/static/drops/papers-11390.html
堆基础学习:
[glibc内存管理ptmalloc源代码分析.pdf](https://paper.seebug.org/papers/Archive/refs/heap/glibc%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86ptmalloc%E6%BA%90%E4%BB%A3%E7%A0%81%E5%88%86%E6%9E%90.pdf)
[linux内核源码](https://code.woboq.org/)(建议直接看malloc free源码)
[堆基础(英文blog)](https://heap-exploitation.dhavalkapil.com)
推荐书籍：
《深入理解计算机系统（原书第3版）》
《程序员的自我修养—链接、装载与库》

## 密码学

密码学需要较强的数学基础。ctf wiki也是入门不错的选择。
了解各种密码的实现过程，相关的攻击方法。
各种密码推荐直接到英文维基学习，讲的十分详细，一般也会有源代码。
上来学习密码学可以抄脚本，不用太关心其数学原理。等深入了解后再详细研究。

古典密码——脑洞大开的密码：[链接](https://hackfun.org/2017/02/22/CTF%E4%B8%AD%E9%82%A3%E4%BA%9B%E8%84%91%E6%B4%9E%E5%A4%A7%E5%BC%80%E7%9A%84%E7%BC%96%E7%A0%81%E5%92%8C%E5%8A%A0%E5%AF%86/)

RSA基础攻击：https://xz.aliyun.com/t/2446#toc-32
RSA进阶攻击：https://github.com/mimoo/RSA-and-LLL-attacks

一堆密码学的题目：https://cryptopals.com/

推荐书籍：
[《深入浅出密码学——常用加密技术原理与应用》](https://github.com/yuankeyang/python/blob/master/%E3%80%8A%E6%B7%B1%E5%85%A5%E6%B5%85%E5%87%BA%E5%AF%86%E7%A0%81%E5%AD%A6%E2%80%94%E2%80%94%E5%B8%B8%E7%94%A8%E5%8A%A0%E5%AF%86%E6%8A%80%E6%9C%AF%E5%8E%9F%E7%90%86%E4%B8%8E%E5%BA%94%E7%94%A8%E3%80%8B.pdf)
《密码编码学与网络安全——原理与实践（第七版》
《图解密码技术》
《应用密码学：协议、算法与C源程序》

## 杂项

杂项，简称Misc。杂项的内容很多很广，需要选手有较大的知识面以及快速学习新鲜事物的能力。
一般包括取证，隐写分析，编码转换，信息收集，流量分析等。有时密码学中的古典密码也被放到杂项里去。其中取证与隐写是misc最重要的一块。需要选手掌握各种花式隐写套路，需有较强的脚本功底，会用各类隐写工具。

隐写
https://www.jianshu.com/p/02fdd5edd9fc
流量分析
《Wireshark网络分析就这么简单》
ctf-wiki:
https://ctf-wiki.github.io/ctf-wiki/misc/introduction-zh/

## 总结

CTF可能门槛比较高，但是入门之后你会发现其乐趣
在学习过程中遇到挫折不要轻易放弃，建议先谷歌查找相关资料，实在查不到再求助他人。
关于如何提问，建议阅读这篇文章：https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md
有任何问题可以到群里联系协会成员。