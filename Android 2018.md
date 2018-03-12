## 1.Activity的启动过程（不要回答生命周期） 
http://blog.csdn.net/luoshengyang/article/details/6689748

## 2.Activity的启动模式以及使用场景 
（1）manifest设置，（2）startActivity flag 
http://blog.csdn.net/CodeEmperor/article/details/50481726 
此处延伸：栈(First In Last Out)与队列(First In First Out)的区别

## 3.Service的两种启动方式 
（1）startService()，（2）bindService() 
http://www.jianshu.com/p/2fb6eb14fdec

## 4.Broadcast注册方式与区别 
（1）静态注册(minifest)，（2）动态注册 
http://www.jianshu.com/p/ea5e233d9f43 
此处延伸：什么情况下用动态注册

## 5.HttpClient与HttpUrlConnection的区别 
http://blog.csdn.net/guolin_blog/article/details/12452307 
此处延伸：Volley里用的哪种请求方式（2.3前HttpClient，2.3后HttpUrlConnection）

## 6.http与https的区别 
http://blog.csdn.net/whatday/article/details/38147103 
此处延伸：https的实现原理

## 7.http与https的区别 
http://blog.csdn.net/whatday/article/details/38147103 
此处延伸：https的实现原理

## 8.手写算法（选择冒泡必须要会） 
http://www.jianshu.com/p/ae97c3ceea8d

## 9.进程保活（不死进程） 
http://www.jianshu.com/p/63aafe3c12af 
此处延伸：进程的优先级是什么（下面这篇文章，都有说） 
https://segmentfault.com/a/1190000006251859

## 10.进程间通信的方式 
（1）AIDL，（2）广播，（3）Messenger 
AIDL : http://www.jianshu.com/p/ae97c3ceea8d 
Messenger : http://blog.csdn.net/lmj623565791/article/details/47017485 
此处延伸：简述Binder ， http://blog.csdn.net/luoshengyang/article/details/6618363/

## 11.加载大图 
PS：有家小公司（规模写假的，给骗过去了），直接把项目给我看，让我说实现原理。。 
最让我无语的一次面试，就一个点问的我底裤都快穿了，就差帮他们写代码了。。 
http://blog.csdn.net/lmj623565791/article/details/49300989

## 12.三级缓存（各大图片框架都可以扯到这上面来） 
（1）内存缓存，（2）本地缓存，（3）网络 
内存：http://blog.csdn.net/guolin_blog/article/details/9526203 
本地：http://blog.csdn.net/guolin_blog/article/details/28863651

## 13.MVP框架（必问） 
http://blog.csdn.net/lmj623565791/article/details/46596109 
此处延伸：手写mvp例子，与mvc之间的区别，mvp的优势

## 14.讲解一下Context 
http://blog.csdn.net/lmj623565791/article/details/40481055

## 15.JNI 
http://www.jianshu.com/p/aba734d5b5cd 
此处延伸：项目中使用JNI的地方，如：核心逻辑，密钥，加密逻辑

## 16.java虚拟机和Dalvik虚拟机的区别 
http://www.jianshu.com/p/923aebd31b65

## 17.线程sleep和wait有什么区别 
http://blog.csdn.net/liuzhenwen/article/details/4202967

## 18.View，ViewGroup事件分发 
http://blog.csdn.net/guolin_blog/article/details/9097463 
http://blog.csdn.net/guolin_blog/article/details/9153747

## 19.保存Activity状态 
onSaveInstanceState() 
http://blog.csdn.net/yuzhiboyi/article/details/7677026

## 20.WebView与js交互（调用哪些API） 
http://blog.csdn.net/cappuccinolau/article/details/8262821/

## 21.内存泄露检测，内存性能优化 
http://blog.csdn.net/guolin_blog/article/details/42238627 
这篇文章有四篇，很详细。 
此处延伸： 
（1）内存溢出（OOM）和内存泄露（对象无法被回收）的区别。 
（2）引起内存泄露的原因

## 22.布局优化 
http://blog.csdn.net/guolin_blog/article/details/43376527

## 23.自定义view和动画 
以下两个讲解都讲得很透彻，这部分面试官多数不会问很深，要么就给你一个效果让你讲原理。 
（1）http://www.gcssloop.com/customview/CustomViewIndex 
（2）http://blog.csdn.net/yanbober/article/details/50577855

## 24.设计模式（单例，工厂，观察者。作用，使用场景） 
一般说自己会的就ok，不要只记得名字就一轮嘴说出来，不然有你好受。 
http://blog.csdn.net/jason0539/article/details/23297037/ 
此处延伸：Double Check的写法被要求写出来。

## 25.String，Stringbuffer，Stringbuilder 区别 
http://blog.csdn.net/kingzone_2008/article/details/9220691

## 26.开源框架，为什么使用，与别的有什么区别 
这个问题基本必问。在自己简历上写什么框架，他就会问什么。 
如：Volley，面试官会问我Volley的实现原理，与okhttp和retrofit的区别。 
开源框架很多，我就选几个多数公司都会用的出来（框架都是针对业务和性能，所以不一定出名的框架就有人用） 
网络请求：Volley，okhttp，retrofit 
异步：RxJava，AsyncTask 
图片处理：Picasso，Glide 
消息传递：EventBus 
以上框架请自行查找，太多了就不贴出来了。

## 27.RecyclerView 
这个挺搞笑的。有另外一个同事也在找工作，面试官嫌他没用过RecyclerView直接pass掉。 
http://blog.csdn.net/lmj623565791/article/details/45059587
