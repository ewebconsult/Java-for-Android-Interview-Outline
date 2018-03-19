# Java for Android
android-Required Interview Outline 欢迎Star，follow
# 操作系统

管理和控制计算机硬件与软件资源的计算机程序，是直接运行在“裸机”上的最基本的系统软件，任何其他软件都必须在操作系统的支持下才能运行。

美国SUN(Stanford University Network)公司，在中国大陆的正式中文名为“太阳计算机系统（中国）有限公司”。
1982年，SUN公司诞生于美国斯坦福大学校园，并于1986年上市，在NASDAQ（纳斯达克：是全美证券商协会自动报价系统）的标识为SUNW，2007年改为JAVA。
2009年4月20日19点40分，美国数据软件巨头甲骨文公司（Oracle）宣布以74亿美元收购SUN公司，从此Java也有“干爹”了，在这个拼爹的时代，Java的发展前景不容置疑。

## Java语言特性
简单、面向对象、安全、跨平台、多线程、健壮、分布式等

## 什么是计算机语言:
生活中的两个人的交流主要是方式无非是采用一种都能够识别的语言，那么也就是说该语言是他们之间传递信息的媒介。

那么什么是计算机语言呢？计算机语言是指用于人与计算机之间通讯的一种特殊语言，是人与计算机之间传递信息的媒介。

那计算机怎么能读懂我们给它发出的的信息呢？此时就需要编写一套由字符、数字所组成并按照某种语法格式的一串串计算机指令，而这些计算机指令就是计算机语言。
软件就是由若干条计算机指令所组成的。

计算机语言分类:

①　机器语言：直接用二进制指令表达，指令是用0和1组成的一串代码，它们有一定的位数，并分成若干段，各段的编码表示不同的含义。

②　汇编语言：使用一些特殊的符号来代替机器语言的二进制码(又称符号语言)，计算机不能直接识别，需要用一种软件将汇编语言翻译成机器语言，汇编语言依赖于硬件体系，开发难度大。

③　高级语言：使用一定格式的自然语言进行编写源代码，通过编译器将源代码翻译成计算机直接识别的机器语言，之后再由计算机执行，不直接操作硬件，把繁琐的翻译操作交给编译器完成。

我们将学习的Java就属于高级语言范畴。

什么是编程:

前面说了计算机语言就是用来实现人和计算机通讯的，那为什么人要和计算机通讯呢，其原因就是为了让计算机帮我们完成一些人为起来比较复杂的工作。
那计算机怎么知道我们要它解决的问题是什么，怎么知道解决问题的具体的步骤是什么呢？此时我们就得通过编程语言去告诉计算机去，做什么，怎么做。这种人和计算机之间交流的过程，我们称之为编程。

举例:计算机例子/分页的例子。


在计算机内，有符号数有3种表示法：原码、反码和补码,所有数据的运算都是采用补码进行的。

正数的原码，反码，补码都相同，负数稍微复杂。

操作5(101)和-5的二进制。

正数5的二进制：101
  原码=101，反码=101，补码=101；
---------------------------------------
原码:

就是二进制表示法，即最高位为符号位，“0”表示正，“1”表示负，其余位表示数值的大小。

反码:

计算250的各个进制值。
十进制和二进制之间转换:
十进制--->二进制:（11111010）
对于整数部分，用被除数反复除以2，除第一次外，每次除以2均取前一次商的整数部分作被除数并依次记下每次的余数。另外，所得到的商的最后一位余数是所求二进制数的最高位。
二进制--->十进制:
进制数第0位的权值是2的0次方，第1位的权值是2的1次方，第2位的权值是2的2次方……公式：第N位 * 2的N次方,结果再相加.
-------------------------------------------------------------------------------
十进制和八进制之间转换:
十进制--->八进制:
10进制数转换成8进制的方法，和转换为2进制的方法类似，唯一变化：除数由2变成8。
八进制--->十进制:
进制数第0位的权值为8的0次方，第1位权值为8的1次方，第2位权值为8的2次方
-------------------------------------------------------------------------------
十进制和十六进制之间转换:
十进制--->十六进制:
10进制数转换成16进制的方法，和转换为2进制的方法类似，唯一变化：除数由2变成16。
十六进制--->十进制:
第0位的权值为16的0次方，第1位的权值为16的1次方，第2位的权值为16的2次方……
-------------------------------------------------------------------------------
二进制和八进制之间转换:
二进制和十六进制之间转换:
八进制和十六进制之间转换:

平台(硬件+OS)相关性:

我们称能够支持程序运行的硬件或软件环境为平台。

不同的平台都有其特有的指令格式，也就是说Win支持的指令格式和Linux支持的指令格式是不一样的，
进而导致了Windows的可执行文件不能在Linux平台上运行，反之Linux的可执行文件也无法再Windows上运行，把这种情况称为平台相关性。

-编辑操作-----------------------------------------------------------------------------------------------------------

CTRL+C--------复制              		CTRL+X--------剪切                 	 CTRL+V--------粘贴

CTRL+A--------全选      	        CTRL+Z--------撤销            		      CTRL+S--------保存 

---基本操作-----------------------------------------------------------------------------------------------------------

【Win】+D  显示桌面                  【Win】+R  打开“运行"               【Win】+L  屏幕锁定

【Win】+E  打开“我的电脑”          	【Win】+F  搜索文件                  【ALT】+TAB  AB项目切换

先使用 【Win】+R 打开“运行窗口",输入: 

calc—>启动计算器      						mspaint—>打开画图板			

notepad—>打开记事本   				cmd—>CMD命令提示符    				截图工具

---常用命令-----------------------------------------------------------------------------------------------------------

盘符之间的切换: 盘符:回车,如进入E盘,  E:回车

进入指定目录   :cd will :cd javase\day01

目录的回退     :cd.. 回到上一级目录:cd\ 回到盘符根目录
清屏           :cls

进制也就是进位制，是人们规定的一种进位方法。 对于任何一种进制---X进制，就表示某一位置上的数运算时是逢X进一位。 十进制是逢十进一，十六进制是逢十六进一，二进制就是逢二进一，以此类推，x进制就是逢x进位。
---------------------------------------------------------
二进制:由两个基本数字0，1组成，运算规律是逢二进一.计算机都使用二进制表示数据.
八进制:由0、1、2、3、4、5、6、7组成,运算规律是逢八进一.
十进制:由0，1，2、3、4、5、6、7、8、9组成.
十六进制:由0～9以及A，B，C，D，E，F组成.
--------------------------------------------------------
二进制数系统中，位简记为b,也称为比特，每个二进制数字0或1就是一个位(bit)。
位是数据存储的最小单位，其中8 bit 就称为一个字节（Byte）
1B（byte，字节）= 8 bit；
1KB（Kibibyte，千字节）=1024B= 2^10 B；
1MB（Mebibyte，兆字节，百万字节，简称“兆”）=1024KB= 2^20 B；
1GB（Gigabyte，吉字节，十亿字节，又称“千兆”）=1024MB= 2^30 B；
1TB（Terabyte，万亿字节，太字节）=1024GB= 2^40 B；
1PB（Petabyte，千万亿字节，拍字节）=1024TB= 2^50 B；


# 继承，封装，多态

## 什么是继承

继承是：子类得到父类所有的成员变量和方法，只支持单继承（即一个子类只能继承一个父类，1个父类可给多个子类继承，但接口可多继承），作用：提高代码的复用性，使得变化的系统有延续性。

## 什么是封装

封装是：封装了实现的细节，隐藏了对象的状态信息在内部，对外只提供接口和方法，进行交互，提高安全性，提高代码的复用性。

## 什么是多态

多态是：同一个类型的不同对象，对于同一个行为，具有多个不同表现形式，消除同一类型之间的耦合关系，使得对象具备多种表现形式。

# 基本类型
整数类型，浮点类型，字符类型，布尔类型，byte 1,short 2,int 4,long 8   floa 4t,double 8   char 2,boolean /

封装类：Byte , Short , Integer , Long , Float , Double , Char , Boolean

>Java的数据类型主要分为：基本数据类型，枚举类型和引用数据类型

## 面向过程(PO)：

一种较早的编程思想，顾名思义该思想是站在过程的角度思考问题，强调的就是功能行为,功能的执行过程,即先干啥,后干啥。而每一个功能我们都使用函数(类似于方法)把这些步骤一步一步实现，使用的时候依次调用函数就可以了。

### 说人话:
提倡和注重的:每一个功能都使用函数来完成,在使用某一个功能的时候,就挨着挨着调用函数即可.
案例：设计购物、做饭、吃饭，洗碗、以及写代码的程序。

>面向过程最大的问题在于**随着系统的膨胀**，面向过程将无法应付，最终导致系统的崩溃。为了解决这一种软件危机，我们提出面向对象思想。

## 面向对象(OO)：
一种基于面向过程的新的编程思想，顾名思义该思想是站在对象的角度思考问题，我们把多个功能合理的放到不同对象里，强调的是具备某些功能的对象。

具备某种功能的实体，称为对象.

## 深入浅出的排序算法-冒泡排序

> 什么是冒泡排序呢？

为什么这个排序要叫冒泡呢？为什么不叫其他名词呢？其实这个取名是根据排序算法的基本思路命名的，见名知意，冒泡排序，就是想泡泡在水里一样，在水里大的泡泡先浮出水面，就是大的先排出来，最小的最慢排出。

冒泡排序，是对排序的各个元素从头到尾依次进行相邻的大小比较，比如你是队长，在你的面前有一排人，你要将其进行排序，依次按照从小到大排序。

怎么理解最大的值被排除，你是队长，你对面前的一群人看不惯，进行排序，从左到右开始，第一个和第二个进行比较，大的那个就被挑出来，与第三个进行比较，接下来就是依次按照这个方法比较，就能把那个最大的值，最高的给挑出来不是，这就是第一轮的比较。

接下来，最大的就不用跟他比较了，上面所述，在排序时，你面前的人，是不能乱动的，一旦比较哪个大，两者就换位，如果第一比第二个小，就是第二个大时，两者不用换位，第二个就与第三个进行比较。

依照这个方法，两两比较，大的都被排到了最后，那么一旦排完，是不是都依照从小到大，（从低到高）的顺序在你面前排好了。
```
//第一轮
for(int index=0;index < arr.length-1; index++）{
//相邻两个比较
 if(arr[index] > arr[index+1]){
   int temp = arr[index];
   arr[index] = arr[index+1];
   arr[index+1] = temp;
 }
}

print(arr);

for(int index=0;index < arr.length-2;index++){
//这里arr.length-2,为什么比上一次多减了1呢？
//因为第一轮，把最大的排出来了，就不用比较了，少了一个人
 if(arr[index] > arr[index+1]){
   int temp = arr[index];
   arr[index] = arr[index+1];
   arr[index+1] = temp;
 }
}

print(arr);

for(int index=0;index < arr.length-3;index++){
 if(arr[index]>arr[index+1]){
   int temp = arr[index];
   arr[index] = arr[index+1];
   arr[index+1] = temp;
 }
}

print(arr);
```

### 优化

```
for(int num=1;num<arr.length;num++){

 for(int index=0;index<arr.length-num;index++){

   if(arr[index]>arr[index+1]){
     int temp = arr[index];
     arr[index] = arr[index+1];
     arr[index+1] = temp;
   }
 }
}
```

## 重点Android

首先你得学习通信技术，大部分都要和后台接口交互，通信技术有okhttp ，解析后台数据有fastjson，流行的通信技术，其次就是界面UI，Android灵活就在界面，界面的功能有很多，之前简书或则掘金上面的第三方界面，就是人家自己写好的自定义View，技术成熟时，你也可以开发自定义View。

### 交互数据的一个通信技术，okhttp

这个交互会用到你跟数据库联系，或则从网上下载数据

比平常用http通信简单很多

比如后台数据库有用户数据和信息，你要把数据获取下来放在你的界面上，就必须通过http请求下载并解析数据

第三方库，你只要下载到你源代码lib中引用一下，就可以用这些特效控件了

http://www.jianshu.com/p/658b56bec80f 

EventBus(事件处理)，xUtils(网络，图片，ORM)

下载百度地图  baidumapapi.jar和libBMapApiEngine.so放libs/armeabi
http://dev.baidu.com/wiki/static/imap/files/BaiduMapApi Lib Android 1.0.zip
申请API Key
地址: http://dev.baidu.com/wiki/static/impap/key

## 体会

想想自己期望中的团队和同事具备哪些特质，然后让自己向着这些方面努力；
聪明，钻研，潜力，韧性
重视基础，重视基础，重视基础！
对技术的热情和热爱（真心感兴趣才能更可能走得更远），乐观&韧性（不管做什么都必然会有挫折，有成功和失败，坚持才是答案，哈哈），认知和思考的能力（是否形成了自己的认知体系，能层层剥茧找到事物的本质），勤奋（加班不是勤奋，思考上的懒惰才是真正的懒惰）。

> 1. 不知道就说不知道，不要绕和试图遮掩，大家都是做技术的，技术上的事，做没做过，会不会，一目了然。如果不懂装懂，绕来绕去，会让人觉得未来跟你合作会很累；2. 对知识型问题，就是那种知道就是知道不知道就是不知道的问题（比如中国有多少个省级行政区），直接说不知道就好了。但对于认知型、问题解决型之类的问题，一定要根据自己已有的知识和经验给出自己的思考和解决方案

## 重要的是这些：
(1) 如果你处理过，那你对细节是否了解，是否形成自己的一套方法论，是否总结了问题分类和常见解法跳出解决问题迈向避免问题等等，这能从侧面反映你的认知能力和钻研能力；
(2) 如果你没处理过，你能否根据已有的经验和知识给出不错的解决思路（侧面反映你的思考能力和举一反三的能力，以及解决新问题的能力）
(3) 另外，有一些不明确的点一定要和面试官确认，比如，现象的一些细节，线上环境的配置等等，不要做主观假设,这其实也是很重要的方面，如果你解决问题都是靠猜和主观假设，很难让人放心.

## 按照学Java基础5天，看一本书5天。10天Java基础就可以学完。看一个APP视频教程10天，谷歌官网看一遍2个月。行动，现在都上班了

未完待续！！！
