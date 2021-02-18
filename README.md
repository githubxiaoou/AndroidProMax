# AndroidProMax
Android Pro Max you will find out!

---

# @[UI篇](https://blog.csdn.net/u014158743/article/details/113743396)（整理中）
## 第一章 UI核心
### 第一节 UI绘制流程
1.1.1 [UI绘制流程及原理](https://blog.csdn.net/u014158743/article/details/113753545)   
1.1.2 [UI绘制流程(测量，布局，绘制)](https://blog.csdn.net/u014158743/article/details/113753545)   
1.1.3 [UI卡顿原理分析及Vsync信号机制](https://blog.csdn.net/u014158743/article/details/113757320)
### 第二节 Paint/Cavans高级绘制
1.2.1 [Paint画笔的常用api简介、渲染器详解](https://blog.csdn.net/u014158743/article/details/113759295)   
1.2.2 [Paint-滤镜和XFERMODE](https://blog.csdn.net/u014158743/article/details/113762288)   
1.2.3 [Canvas的常用api简介——变换，状态保存，离屏缓冲](https://blog.csdn.net/u014158743/article/details/113781831)    
1.2.4 [Canvas实际案例操作——爆炸粒子，渐入动画效果](https://blog.csdn.net/u014158743/article/details/113782835)   
1.2.5 贝塞尔曲线与计算规则   
1.2.6 基于PathMeasure源码分析path测量问题   
### 第三节 事件传递机制
1.3.1 事件分发机制详解   
1.3.2 手写模拟事件分发
### 第四节 属性动画
1.4.1 源码层分析、自定义动画框架   
1.4.2 详解网易云音乐屏幕适配
## 第二章 屏幕适配
### 第一节 屏幕适配解决方案
2.1.1 自定义像素适配   
2.1.2 手写百分比布局适配   
2.1.3 修改系统density, densityDpi适配   
2.1.4 刘海屏适配   
2.1.5 网易云音乐用到的高级绘制与动画
## 第三章 项目实战
### 第一节 Material Design
3.1.1 Material Design交互设计   
3.1.2 自定义RecycleView   
3.1.3 Coordinatorlayout原理应用nestedscrolling组合完成下拉特效   
3.1.4 沉浸式设计，cardView源码分析和兼容原理   
### 第二节 自定义View
3.2.1 [自定义控件](https://blog.csdn.net/u014158743/article/details/113751778)   
3.2.2 手写RecyclerView(手写tem回收池)   
3.2.3 SVG矢量图形打造不规则的自定义控件   
3.2.4 阿里VLayout原理解密与PathMeasure高级使用   
3.2.5 网易云音乐的音乐播放界面如何实现(打碟界面)   
3.2.6 PathMeasure高阶动画特效(水波纹效果)   
# @[NDK篇](https://blog.csdn.net/u014158743/article/details/113842655)（整理中）
## 第一章C/C++基础篇
### 第一节 基础知识
1.1.1 函数   
1.1.2 Linux内存布局原理-01   
1.1.2 指针数组-02   
1.1.3 结构体-01   
1.1.3 共用体-02   
1.1.4 动态库   
### 第二节 C++基础进阶
1.2.1 类的构造-01   
1.2.1 单例对象，操作符重载-02   
1.2.2 继承多态，虚函数-01   
1.2.2 类模板，函数模板-02   
1.2.3 类型转换，异常处理   
1.2.4 容器  
1.2.5 命名空间  
## 第二章 编译原理与语法详解
### 第一节 makefile语法详解
2.1.1 静态库与动态库原理，编译流程详解   
2.1.2 makefile走读与语法基础   
2.1.3 Android.mk基础   
### 第二节 shell语法详解
2.2.1 变量的定义到使用   
2.2.2 语法(循环+文件读写)01   
2.2.2 语法详解(if语句)02   
2.2.2 语法(运算符详解03   
2.2.2 语法(重定向)04   
2.2.3 方法参数传递机制详解   
2.2.4 Shel脚本编写与执行编译ffmpeg库
### 第三节 Cmake详解
2.3.1 CMake语法详解   
2.3.2 CMakelist.txt文件详解  
## 第三章 项目实战
3.0.0 visualstudio环境搭建   
3.0.1 opencv环境搭建
### 第一节 一线互联网企业核心技术
3.1.1 阿里云andfix热修复   
3.1.2 sophix原理分析、利用系统源码打造gif图播放(上)   
3.1.3 利用系统源码打造gif图播放(下)
### 第二节 网易视频云剖析
3.2.0 FFmpeg命令详解   
3.2.1 android studio搭建音视频开发环境(集成FFmpeg)  
3.2.2 视频解码及同步处理-01 (视频渲染)   
3.2.2 视频解码及同步处理-02  
3.2.2 音频解码  
3.2.3 音视频编码原理详解  
3.2.4 网易云信直播推流与增量更新(5.27直播)  
3.2.5 云信实战项目(直播推流) (一)  
3.2.5 云信实战项目(直播推流) (二)  
3.2.5 音频推流   
3.2.7 音视频同步与音频播放(一)   
3.2.7 音视频同步与音频播放(二)   
### 第三节 人脸美化实战
3.3.1 人脸磨皮算法与美白、人脸动态贴纸  
3.3.2 大眼瘦脸(图像局部缩放，平移，人脸关键点检测)  
3.3.3 视频特效处理、视频与音频合成原理分析以及手写实现   
### 第四节 opencv图像识别
3.4.1 opencv原理详解     
3.4.2 android studio cmake配置opencv开发环境  
3.4.3 android与人工智能(一)  
3.4.4 OpenGL与OpenCV共同打造大眼滤镜  
3.4.5 人脸美化实战  
### 第五节 网易云信技术
3.5.1 WebRTC导读   
3.5.2 点对点通信原理(实现内网间直接通信)
## 第四章 补充课程
### 第一节 WebRTC视频会议
4.1.0 webRTC服务器搭建  
4.1.1 手写webRTC视频会议系统01  
4.1.2 视频会议系统之内网穿透02  
4.1.3 webRTC之视频会议原理03  
4.1.4 webRTC视频会议聊天-socket链接04  
4.1.5 webRTC视频会议聊天-socket服务通信05  
4.1.6 webRTC会议室通话peerConnectionFactory06  
4.1.7 webRTC视频会议聊天连接初始化07  
4.1.8 webRTC视频会议聊天摄像头预览08  
4.1.9 webRTC视频会议聊天建立本地连接09  
4.1.10 webRTC视频会议聊天-ICEcandidate交换10  
4.1.11 webRTC视频会议聊天界面完善  
4.1.12 webRTC视频会议聊天-UI接口解耦  
### 第二节 直播美颜
4.2.1 直播美颜实现
### 第三节 人工智能
4.3.1 人工智能简介  
4.3.2 人工智能鉴黄师消失
# @[架构师篇](https://blog.csdn.net/u014158743/article/details/113842932)（整理中）
## 第一章 架构师入门
### 第一节 UML建模
1.1.0 PowerDesigner安装   
1.1.1 正向工程与逆向工程在UML图中的应用   
1.1.2 关系(依赖，泛化，关联，实现)画法   
1.1.3 AOP面向切面架构设计   
1.1.4 集中式登录架构设计
### 第二节 设计模式
1.2.1 [**MVC架构设计与三层模型**](https://blog.csdn.net/u014158743/article/details/105648184)   
1.2.2 MVP思想精髓与解耦   
1.2.3 MVP思想实现项目基础框架搭建   
1.2.4 [**更节省的设计模式之MVVM实现数据双向绑定**](https://blog.csdn.net/u014158743/article/details/105462190)   
1.2.5 [**MVVM与DataBinding**](https://blog.csdn.net/u014158743/article/details/105472418) 
### 第三节 无死角分析Android系统源码
1.3.1.1 Handler Message源码分析及手写实现01  
1.3.1.2 Handler Message源码分析及手写实现02  
1.3.1.3 Handler Message源码分析及手写实现03  
1.3.2.1 Binder核心原理(一)  
1.3.2.2 Binder核心原理(二)  
1.3.2.3 Binder架构设计  
1.3.3.1 PMS源码分析  
1.3.3.2 APK安装原理  
1.3.4.1 ActivityManagerService架构设计-01  
1.3.4.2 ActivityManagerService架构设计-02  
1.3.5 App启动流程源码解析
## 第二章 架构师晋级
### 第一节 换肤核心技术
2.1.1 手写动态换肤框架及高可扩展性换肤应用
2.1.2 网易云音乐动态换肤
### 第二节 组件化框架设计
2.2.1 组件化gradle语法  
2.2.2 组件化项目详细部署  
2.2.3 组件化模块间交互  
2.2.4 组件化APT介绍与使用  
2.2.5 组件化APT高级用法JavaPoet  
2.2.6 组件化路由架构设计  
2.2.7 组件化APT生成路由Group和Path类文件  
2.2.8 组件化APT生成路由动态参数类文件  
2.2.9 组件化在网易云课堂中的实践  
### 第三节 插件化框架设计
2.3.1 手写占位式插件化框架Activity通信  
2.3.2 手写占位式插件化框架-Service通信  
2.3.3 手写占位式插件化框架-动态广播的使用  
2.3.4 手写占位式插件化框架-APK解析原理系统源码分析  
2.3.5.1 Hook从入门到熟练  
2.3.5.2 Hook系统源码实现权限管理架构  
2.3.6 手写Hook式插件化框架安卓类加载源码分析  
2.3.7 手写Hook式插件化框架-APP与插件融为一体  
2.3.8 手写LoadedAPK式插件化框架ActivityThread源码分析  
2.3.9 手写LoadedAPK式插件化框架-自定义LoadedAPK  
2.3.10 手写LoadedApk式插件化框架之绕过getPackageInfo检测  
2.3.11 手写Hook式插件化之Android系统9.0详解  
## 第三章 架构师锤炼实操
### 第一节 Android事件总线框架设计
3.1.1 EventBus3.0-介绍与正确使用  
3.1.2 EventBus3.0-反射原理讲解  
3.1.3 手写实现EventBus  
3.1.4 FastJson序列化与反序列化
### 第二节 数据库框架设计
3.2.1 数据库创建  
3.2.2 数据库查询、修改及删除  
3.2.3 数据库分库   
3.2.4 数据库升级
### 第三节 OKHttp网络访问框架设计
3.3.1 OIS七层模型介绍TCPIP模型介绍HTTP协议模式介绍  
3.3.2 OKHttp主线流程的源码阅读  
3.3.3 OKHttp源码阅读之线程池详解  
3.3.4.1 OKHttp源码阅读之建造者模式01  
3.3.4.2 OKHttp源码阅读之责任链模式02  
3.3.5 OKHttp手写实现之整体框架搭建  
3.3.6 OKHttp手写实现之Socket请求与响应(一)  
3.3.6 OKHttp手写实现之Socket请求与响应(二)  
3.3.7 OKHttp总结与优化  
3.3.8 手写OKHTTP连接池  
### 第四节 Glide图片加载框架设计
3.4.1 Glide手写实现之资源封装  
3.4.2 Glide手写实现之活动缓存  
3.4.3 Glide手写实现之内存缓存  
3.4.4 Glide手写实现之磁盘缓存  
3.4.5 Glide手写实现之生命周期  
3.4.6 Glide手写实现之加载图片  
3.4.7 手写Glide图片加载框架
### 第五节 RxJava2响应式编程框架设计
3.5.1 RxJava概念与观察者模式  
3.5.2 RxJava上游与下游  
3.5.3 RxJava创建型操作符  
3.5.4 RxJava变换型操作符  
3.5.5 RxJava过滤型操作符  
3.5.6 RxJava条件型操作符  
3.5.7 RxJava合并型操作符  
3.5.8 RxJava异常处理操作符  
3.5.9 RxJava线程切换实战  
3.5.10 RxJava背压模式  
3.5.11 RxJava之Flowable讲解  
3.5.12 RxJava配合Retroft  
3.5.13 RxJava泛型高级进阶  
3.5.14 RxJava手写create操作符  
3.5.15 RxJava手写create之读写模式  
3.5.16 Rxjava手写just操作符  
3.5.17 RxJava手写map操作符  
3.5.18 RxJava手写map与create流程详解  
3.5.19 RxJava无死角回顾  
3.5.20 手写RxJava线程切换
### 第六节 IOC框架设计
3.6.1 ButterKnife详解与原理分析  
3.6.2 Java文件结构化文本详解  
3.6.3 手写Butterknife实现无性能损耗的编译时框架  
3.6.4 Dagger2介绍与使用  
3.6.5 手写运行时注入布局  
3.6.6 手写运行时注入控件  
3.6.7 手写运行时注入事件  
3.6.8 手写运行时注入兼容Android事件  
3.6.9 APT实现手写Dagger2注入式框架  
### 第七节 架构师必备技能
3.7.1 手写Android全版本编译时权限申请框架  
3.7.2 大型网易云音乐安卓项目的架构搭建学习  
3.7.2 大型网易云音乐安卓项目的架构搭建学习(下)
### 第八节 Jetpack
3.8.1 JetPack  
3.8.2 JetPat-Lifecycle  
3.8.3 JetPack-liveData  
3.8.4 JetPack-ViewModel  
3.8.5 综合案例  
3.8.6 JetPack-Kotlin的学习  
3.8.7 JetPack-Room数据库的学习  
3.8.8 JetPack Room数据库结合仓库  
3.8.9 ViewBinding 与 DataBinding高级  
3.8.10 自定义的LiveData
## 第四章 动态切肤 迭代课程
4.1.1 换肤基本功之最新源码与AndroidX源码解读  
4.1.2 02皮肤包本质与加载外界皮肤包(基于安卓10.0源码)  
4.1.3 QQ换肤源码实战上(基于安卓9.0源码)  
4.1.4 QQ换肤源码实战中(基于安卓9.0源码)  
4.1.5 QQ换肤源码实战下(基于安卓9.0源码)  
4.1.6 可扩展类型换肤库的学习1(基于安卓9.0源码)  
4.1.7 可扩展类型换肤库的学习2(基于安卓9.0源码)  
4.1.8 可扩展类型换肤库的学习3(基于安卓9.0源码)
## 第五章 AMS迭代课程
5.1.1 7.1版本的AMS应用实战  
5.1.2 7.1版本的AMS应用实战续集(高版本篇)  
5.1.3 9.0版本的AMS应用实战  
5.1.4 全兼容版本的AMS实战  
5.1.5 AMS理论知识大集合  
5.1.6 AMS源码分析
## 第六章 PackageManagerService增补视频
6.1.1 PMS安装流程  
6.1.2 PMS构造区域分析(9.0源码)  
6.1.3 PMS源码模拟调用   
6.1.4 PMS之Intent对接  
6.1.5 PMS之SystemService学习  
6.1.6 PMS之SystemServer启动流程
# @[性能优化篇](https://blog.csdn.net/u014158743/article/details/113843013)（整理中）
## 第一章 多维度分析性能优化
1.1.1 app启动  
1.1.2 [**黑白屏解决方案**](https://blog.csdn.net/u014158743/article/details/112429138)   
1.1.3 代码优化  
1.2.1 Ul渲染流程及优化  
1.3.1 Java虚拟机/垃圾回收机制/内存泄漏  
1.3.2 内存优化(泄漏，抖动)，bitmap内存管理  
1.3.3 手写微博巨图加载解决方案  
1.3.4 哈夫曼算法打造无损压缩技术  
1.3.5 Android系统耗电统计与分析
## 第二章 高级应用安全技术
2.1.1 防反编译利器技术框架  
2.1.2 https防抓包机制  
2.1.3 DEX加固与反编译  
2.1.4 APP网络传输安全(上)  
2.1.4 APP网络传输安全(下)  
2.1.5 网易易盾的防反编译，加固等技术的实现
## 第三章 性能优化
3.1.1 热修复  
3.2.1 APK瘦身  
3.2.2 protocol buffer
## 第四章 迭代更新
4.1.1 启动优化  
4.1.2 布局优化  
4.1.3 内存优化  
4.1.4 线程优化  
4.1.5 网络优化  
4.1.6 电量优化 
# @[Flutter篇](https://blog.csdn.net/u014158743/article/details/113843294)（整理中）
## 第一章 Flutter入门基础
1.1.1 dart基础语法  
1.1.2 dart语法深入(上)  
1.1.2 dart语法深入(下)
## 第二章 控件与交互
2.1.1 环境搭建  
2.1.2 基础组件  
2.1.3 布局组件  
2.1.4 列表组件  
2.1.5 路由  
2.1.6 动画  
2.1.7 手势  
2.1.8 平台集成
## 第三章 Flutter项目实战
3.1.1 持久化处理  
3.1.2 网络请求  
3.1.3 基于云信实时音视频封装插件  
3.1.4 基于插件产品实践
## 第四章 公开课回放视频
4.1.1 Flutter实战封装Plugin-基于网易云信音视频SDK
## 第五章 flutter实战
5.1.1 Flutter实战(上)  
5.1.2 Flutter实战(下)
# 商业化项目（整理中）
1.1.1 网易云音乐高级U实战分享  
1.1.2 网易云信IM的前世今生  
1.1.3 网易易盾Android安全分享  
1.1.4 中国大学MOOC组件化编程实践  
1.1.5 网易云信Android实时音视频实践分享  
1.1.6 android字节码插桩


---
本文正文部分主要归纳自《网易微专业》

#### 本系列完整知识点目录请到我的[**Github**](https://github.com/githubxiaoou/AndroidProMax)查看

佛系整理，敬请期待！全系列的整理工作截至2022年三月底前完成。
