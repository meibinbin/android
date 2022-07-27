
# 四大组件

## Activity 相关</br>

- 启动模式以及使用场景?</br>
- onNewIntent()和onConfigurationChanged()</br>
- onSaveInstanceState()和onRestoreInstanceState()</br>
- Activity 到底是如何启动的</br>


### Fragment </br>
- Fragment 生命周期和 Activity 对比</br>
- Fragment 之间如何进行通信</br>
- Fragment的startActivityForResult</br>
- Fragment重叠问题</br>


## Service 相关</br>

- 进程保活</br>
- Service的运行线程（生命周期方法全部在主线程）</br>
- Service启动方式以及如何停止</br>
- ServiceConnection里面的回调方法运行在哪个线程？</br>


## BroadcastReceiver 相关</br>
- 注册方式，优先级</br>
- 广播类型，区别</br>
- 广播的使用场景，原理</br>


# Android特性

## Android View 绘制流程</br>
- 简述 View 绘制流程</br>
- onMeasure， onlayout， ondraw方法中需要注意的点</br>
- 如何进行自定义 View</br>
- view 重绘机制</br>


## Android  事件分发机制</br>
- onTouch和onTouchEvent区别，调用顺序</br>
- dispatchTouchEvent， onTouchEvent， onInterceptTouchEvent 方法顺序以及使用场景</br>
- 滑动冲突，如何解决</br>


## Android Window、Activity、DecorView以及ViewRoot</br>
[Window、Activity、DecorView以及ViewRoot之间的关系](https://www.jianshu.com/p/8766babc40e0)</br>

## Android 高级必备 ：AMS,WMS,PMS</br>
- AMS,WMS,PMS 创建过程</br>


# Android消息机制

## Handler 相关知识

- Handler Looper Message 关系是什么？</br>
- Messagequeue 的数据结构是什么？为什么要用这个数据结构？</br>
- 如何在子线程中创建 Handler?</br>
- Handler post 方法原理？</br>
- ThreadLocal 必备 </br>


## Binder 多进程 AIDL</br>
- 常见的 IPC 机制以及使用场景</br>
- 为什么安卓要用 binder 进行跨进程传输</br>
- 多进程带来的问题</br>


## AsyncTask相关</br>
- AsyncTask是串行还是并行执行？</br>


# 优化相关

## Android布局优化之ViewStub、include、merge</br>

- 什么情况下使用 ViewStub、include、merge？</br>
- 他们的原理是什么？</br>


## Android ANR </br>
- 为什么会发生 ANR？</br>
- 如何定位 ANR？</br>
- 如何避免 ANR？</br>


## Android 内存相关</br>

**注意：内存泄漏和内存溢出是 2 个概念**</br>

- 什么情况下会内存泄漏？</br>
- 如何防止内存泄漏？</br>


## Android 屏幕适配</br>
- 屏幕适配相关名词解析</br>
- 现在流行的屏幕适配方式</br>


## Android 缓存机制</br>
- LruCache使用极其原理</br>


## Android 性能优化</br>
- 如何进行 内存 cpu 耗电 的定位以及优化</br>
- 性能优化经常使用的方法</br>
- 如何避免 UI 卡顿</br>


## Android MVC、MVP、MVVM</br>
- 好几种我该选择哪个？优劣点</br>


## Android Gradle 知识</br>
[必须贴一下官方文档：配置构建](https://developer.android.com/studio/build?hl=zh-cn)</br>
[Gradle 提示与诀窍](https://developer.android.com/studio/build/gradle-tips?hl=zh-cn)</br>


# 源码理解
## RxJava</br>
- 使用过程，特点，原理解析</br>
[RxJava 名词以及如何使用](https://blog.piasy.com/2016/09/15/Understand-RxJava/index.html)</br>
[Rxjava 观察者模式原理解析](https://juejin.im/post/58dcc66444d904006dfd857a)</br>
[Rxjava订阅流程，线程切换，源码分析 系列](https://juejin.im/post/5a209c876fb9a0452577e830)</br>

## OKHTTP 和 Retrofit</br>
[OKHTTP完整解析](https://blog.csdn.net/lmj623565791/article/details/47911083)  --鸿洋出品</br>
[Retrofit使用流程，机制详解](https://blog.csdn.net/carson_ho/article/details/73732076)</br>
[从 HTTP 到 Retrofit](https://www.jianshu.com/p/45cb536be2f4)</br>
[Retrofit是如何工作的](https://www.jianshu.com/p/cb3a7413b448)</br>

## 最流行图片加载库： Glide</br>

[Android图片加载框架最全解析（一），Glide的基本用法](https://blog.csdn.net/guolin_blog/article/details/53759439)</br>
[Android图片加载框架最全解析（二），从源码的角度理解Glide的执行流程](https://blog.csdn.net/guolin_blog/article/details/53939176)</br>
[Android图片加载框架最全解析（三），深入探究Glide的缓存机制](http://blog.csdn.net/guolin_blog/article/details/54895665)</br>
[Android图片加载框架最全解析（四），玩转Glide的回调与监听](https://blog.csdn.net/guolin_blog/article/details/70215985)</br>
[Android图片加载框架最全解析（五），Glide强大的图片变换功能](http://blog.csdn.net/guolin_blog/article/details/71524668)</br>
[Android图片加载框架最全解析（六），探究Glide的自定义模块功能](http://blog.csdn.net/guolin_blog/article/details/78179422)</br>
[Android图片加载框架最全解析（七），实现带进度的Glide图片加载功能](http://blog.csdn.net/guolin_blog/article/details/78357251)</br>
[Android图片加载框架最全解析（八），带你全面了解Glide 4的用法](http://blog.csdn.net/guolin_blog/article/details/78582548)</br>


# Android框架
## 组件化与插件化</br>
- 业务大了代码多了会用到。</br>
- 为什么要用组件化？</br>
- 组件之间如何通信？</br>
- 组件之间如何跳转？</br>

## Flutter 与
- [Flutter原理](https://zhuanlan.zhihu.com/p/36861174)</br>


## 面试常问的点</br>
除了上面整理的安卓高级技术问题，还有一些面试官喜欢问的点：</br>
 - 你在项目中遇到最难得点是什么？如何解决的？</br>
 - 平时遇到问题了是如何解决的？比较好的回答： 官方文档一定要看，通过源码解决问题，然后才是搜索引擎以及和同事讨论</br>
 - 你最近做的 APP 是如何架构的？为什么要这样架构？</br>
 - 平时怎么进行技术进阶，如何学习？</br>
 - 你觉得自己处于什么技术水平？</br>
 - 你的技术优势是什么？</br>
 - 用过什么开源技术？它的原理是什么？看过它的源码么？ 这里建议看上面 Glide 相关</br>
 - 如何设计一个框架？能不能回答上直接判断你的技术等级</br>

</br>


