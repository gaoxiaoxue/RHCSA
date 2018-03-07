
## 计算机发展史
* 1.1946年第一台计算机,计算能力5000次每秒,操作系统发展缓慢(分时操作系统)

* 2.1965年 AT&T的Bell实验室，MIT和GE联合研发了多任务多用户多继承的操作系统 Multcs项目(由mult和cs(computer system)组成) 1969年取消

* 3.Ken Thompson(Bell实验室的) 开发space travel游戏自己用PDP-7(当时小型计算机)开发了一个系统Unics(由uni 和 cs组成)，用汇编语言写的(针对固定的硬件编写，可能在一个电脑上好使，移植性差)

* 4.1969年Ken Thompson和 Dennis Ritchie用B语言重新编写了Unics系统并更名为Unix(因为Unics与西班牙语厕所相同),B语言改编->C语言

* 5.1974年 加入新特性，变得完善

* 6.1977年 Sun公司创始人Bill Joy针对自己的机器修改Unix源码称为BSD(Berkeley Software Distribution),从此各大公司根据自己的架构以BSD系统为基础进行Unix系统的研发(商业版本)，从而产生不同版本的Unix操作系统(当时版权费用2万$～3万$/份)

* 7.1979年Bell实验室从AT&T独立出来，AT&T受美国法院垄断，Bell实验室收回Unix开放权(打官司打了10～15年)，当时系统10万$，引起商业纠纷，对Unix发展的一次重大打击

* 8.1975年Microsoft诞生，由比尔盖茨与保罗艾伦创办的跨国科技公司，主做技术，保罗艾伦的程序员朋友用六周时间写出了EDOS系统，5万美元被比尔盖茨买断了，之后自己继续研发了DOS系统，刚开始卖不出去，比尔盖茨的妈妈玛丽盖茨认识IBM董事会成员，比尔为IBM研发出了第一代计算机，微软DOS因此成为行业唯一标准（整机器5万美元包括系统），比尔盖茨提出了license卖一份系统给5$ DOS-> windows 1.0 2.0 3.0 3.1 ->windowsNT ->windows 95 98 windowsNT第一个真正图形化界面的操作系统

* 9.图形化操作 X window 起源于Xerox打印机的公司，出来就被冷藏(认为研究出来没人买打印机)

* 10.1976年Apple诞生，由史蒂夫乔布斯和雅克和罗韦恩创立，1000万$买下图形化操作X window Mac OS基于FreeBSD的

* 11.Novell公司（诺勒有限公司）在8090年代几乎垄断了整个网络市场，研究Netware系统，但是被微软公司的视窗软件window击败windowsNT系统

* 12.1983年，GUN诞生 GUN计划 GUN’s Not Unix,革奴宣言，不花钱一起研究操作系统

* 13.GUN内核跑在因特尔I386上非常卡，没有一个好的内核

* 14.1991年Linux Torvalds研究Minix的设计思想后基于gcc bash开发了针对I386的linux内核；

* 15.1993年Torvalds发布Linux-v1.0,并且Linux转向GPL;

* 16.1994年Linux的第一个商业发行版Slackware问世(同年RedHat Linux 发行版诞生)

* 17.1996年Torvalds发布Linux-v2.0,确定吉祥物企鹅

* 18.操作系统的组成：硬件 软件 内核

* 19.软件->shell->内核->硬件 即内核调用硬件，shell（壳）操作内核，软件调用shell

* 20.硬件：摩托罗拉(贵) 因特尔I386(小便宜)

* 21.软件：自由软件，代码对外开放，

* 23.开源GPL协定，即你只要有一行代码是我的开源的 你就必须把你写的都对外开放，GPLv1版本(非常严格) GPLv2版本，开源怎么赚钱：服务费二次开发定制 即开源不代表免费

* 24.GUN/LINUX RHEL7(RedHat Enterprise Linux)

### Linux版本介绍

1.官网：www.kernel.org

2.内核版本说明4.9.10 4主版本号 9次版本号 10修订版本（改了多少次bug）

3.在内核的主版本3之前，次版本号偶数为稳定版本，奇数为不稳定版本（测试版本）

4.Linux发行版本：

    debian(得编操作系统)非常重要的发行版本->Ubuntu(乌班图)衍生版本

    slackware发行版本

    RedHat发行版本（收费）->CentOs衍生版本(完全相同)

    Suse发行版本（收费）->openSuse

5.RHEL7(RedHat Enterprise Linux)企业版系列

6.RHEL与RedHat系列的区别：

redhat系列 6 7 8 9是完整版系列

之后拆分成两个系列

fedora系列（完整版的红帽系统）红帽不对它维护，直测试，一两个月更新一次，频率极高，有好的就丢到rhel中发行

RHEL系列（服务器版本）

7.RHEL 5 6 7 大约3～5年更新一次版本，区别很大

8.RHEL 5 使用oracle ；RHEL 6 7使用oracle 没有5稳定；Oracle linux就是RHEL 5

9.OpenStack项目(主流公司都投入大量资金到这个项目)

10.淘宝和微软都用的linux操作系统



