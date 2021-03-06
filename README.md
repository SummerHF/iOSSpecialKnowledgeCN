# iOS专项学习 - 高质量文章收集

按iOS知识点分类收集的高质量文章。长期更新，欢迎关注！

## 线程/底层/Runtime

文章名称 | 简介 |
----|------|
[CoreFoundation Apple Source Browser](https://opensource.apple.com/tarballs/CF/) |  CoreFoundation源码浏览器  |
[Runloop - Apple文档](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/Multithreading/RunLoopManagement/RunLoopManagement.html#//apple_ref/doc/uid/10000057i-CH16-SW1) | Runloop(苹果官方文档)
[Concurrency Programming Guide - Apple文档](https://developer.apple.com/library/content/documentation/General/Conceptual/ConcurrencyProgrammingGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008091-CH1-SW1) | Concurrency Programming Guide - Apple文档
[Runloop - Apple文档翻译](http://blog.sina.com.cn/s/blog_4cd8dd130101ntiy.html) | Runloop苹果文档翻译
[Threading Programming Guide - Apple文档翻译](https://github.com/0oneo/iOSTranslation/blob/master/Apple/%E7%BF%BB%E8%AF%91%20Threading%20Programming%20Guide.md) | 翻译 Threading Programming Guide
[Method Swizzling](http://nshipster.com/method-swizzling/) | Method Swizzling
[Method Swizzling 和 AOP 实践](http://tech.glowing.com/cn/method-swizzling-aop/) | glowing团队
[Objective-C +load vs +initialize](http://blog.leichunfeng.com/blog/2015/05/02/objective-c-plus-load-vs-plus-initialize/) | Objective-C +load vs +initialize(作者雷纯锋)
[深入理解RunLoop](http://blog.ibireme.com/2015/05/18/runloop/) | 深入理解RunLoop（由YYKit作者分享）
[RunLoop 总结：RunLoop的应用场景（一）保证线程长久存活](http://www.jianshu.com/p/902741bcf707) | 偏实践
[RunLoop视频线下分享](http://v.youku.com/v_show/id_XODgxODkzODI0.html) | 作者孙源
[Controlling How NSThread and NSRunLoop Exit](http://shaheengandhi.com/controlling-thread-exit/) | Controlling How NSThread and NSRunLoop Exit
[已经有了__weak 为什么还要保留 __unsafe_unretained ？](https://www.zhihu.com/question/55831650) | 已经有了__weak 为什么还要保留 __unsafe_unretained ？
[iOS多线程编程Part 1/3 - NSThread & Run Loop](http://w11h22j33.iteye.com/blog/1998620) | iOS多线程编程Part 1/3 - NSThread & Run Loop
[iOS多线程编程Part 2/3 - NSOperation](http://w11h22j33.iteye.com/blog/1998624) | iOS多线程编程Part 2/3 - NSOperation
[iOS多线程编程Part 3/3 - GCD](http://w11h22j33.iteye.com/blog/1998626) | iOS多线程编程Part 3/3 - GCD
[Run repeating NSTimer with GCD?](https://stackoverflow.com/questions/10522928/run-repeating-nstimer-with-gcd) | Run repeating NSTimer with GCD?
[Method Swizzle 与 AOP](http://csbzhixing.github.io/2016/08/19/Method%20Swizzle%20%E4%B8%8E%20AOP/) | Method Swizzle 与 AOP
[重识 Objective-C Runtime - 看透 Type 与 Value](http://blog.sunnyxx.com/2016/08/13/reunderstanding-runtime-1/) | 作者孙源
[反编译分析并模拟实现methodSignatureForSelector方法](http://tutuge.me/2017/04/08/diy-methodSignatureForSelector/) | 作者：[三土哥](http://tutuge.me/2017/04/08/diy-methodSignatureForSelector/)
[Objective-C Automatic Reference Counting (ARC)](https://clang.llvm.org/docs/AutomaticReferenceCounting.html) | llvm.org
[线程安全之锁](https://wangdetong.github.io/2017/04/11/%E7%BA%BF%E7%A8%8B%E5%AE%89%E5%85%A8%E4%B9%8B%E9%94%81/) | WangDetong's Blog
[Objective-C +load vs +initialize](http://blog.leichunfeng.com/blog/2015/05/02/objective-c-plus-load-vs-plus-initialize/) | 雷纯锋的技术博客
[关于 @synchronized，这儿比你想知道的还要多](http://yulingtianxia.com/blog/2015/11/01/More-than-you-want-to-know-about-synchronized) | 关于 @synchronized，这儿比你想知道的还要多
[Blocking Queue in iOS](https://mobiarch.wordpress.com/2012/05/22/blocking-queue-in-ios/) | iOS仿Java的Blocking Queue
[Framework编程指南](https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPFrameworks/Frameworks.html) | Framework编程指南 - Apple文档
[Hook Objective-C Block with Libffi](http://yulingtianxia.com/blog/2018/02/28/Hook-Objective-C-Block-with-Libffi/) | Hook Objective-C Block实现
[iOS多线程到底不安全在哪里？](http://mrpeak.cn/blog/ios-thread-safety/)  | iOS多线程到底不安全在哪里？
[正确使用多线程同步锁@synchronized()](http://mrpeak.cn/blog/synchronized/) | 正确使用多线程同步锁@synchronized()
[CLANG技术分享系列一:编写你的第一个CLANG插件](http://kangwang1988.github.io/tech/2016/10/31/write-your-first-clang-plugin.html) | CLANG技术分享系列一:编写你的第一个CLANG插件
[使用 libffi 实现 AOP](https://juejin.im/post/5ae28acd6fb9a07ac55fdac0) | 使用 libffi 实现 AOP
[ios-assembly-tutorial](https://www.raywenderlich.com/37181/ios-assembly-tutorial) | iOS汇编教程 - Raywenderlick
[objc_msgSend_stret](http://sealiesoftware.com/blog/archive/2008/10/30/objc_explain_objc_msgSend_stret.html) | objc_msgSend详解
[Let's Build objc_msgSend](https://www.mikeash.com/pyblog/friday-qa-2012-11-16-lets-build-objc_msgsend.html) | Let's Build objc_msgSend
[汇编语言入门教程](http://www.ruanyifeng.com/blog/2018/01/assembly-language-primer.html) | 通俗易懂（阮一峰）
[Mach-O 可执行文件](https://objccn.io/issue-6-3/) | ObjC中国

#### Swift

文章名称 | 简介 |
----|------|
[Swift & the Objective-C Runtime](http://nshipster.com/swift-objc-runtime/) | Swift在Extension中添加属性
[A Simple Approach to Thread-Safe Networking in iOS Apps](https://robots.thoughtbot.com/a-simple-approach-to-thread-safe-networking-in-ios-apps?utm_campaign=iOS%252BDev%252BWeekly&amp;utm_medium=rss&amp;utm_source=iOS_Dev_Weekly_Issue_321) | A Simple Approach to Thread-Safe Networking in iOS Apps
[从零构建 Dispatch Queue](http://swift.gg/2017/09/07/friday-qa-2015-09-04-lets-build-dispatch_queue/) | 作者：Mike Ash

## 音视频/图文/动画

文章名称 | 简介 |
----|------|
[Core Animation Programming Guide](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreAnimation_guide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40004514-CH1-SW1) | Core Animation Programming Guide
[移动端图片格式调研](http://blog.ibireme.com/2015/11/02/mobile_image_benchmark/) |  移动端图片格式调研
[iOS 处理图片的一些小 Tip](http://blog.ibireme.com/2015/11/02/ios_image_tips/) | iOS 处理图片的一些小 Tip
[iOS 保持界面流畅的技巧](http://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/) | iOS 保持界面流畅的技巧
[颜色模型](http://blog.ibireme.com/2013/08/12/color-model/) | 颜色模型
[视音频数据处理入门：RGB、YUV像素数据处理](http://blog.csdn.net/leixiaohua1020/article/details/50534150) |  视音频数据处理入门系列文章第一篇 - 雷霄骅
[How to Play, Record, and Merge Videos in iOS and Swift](https://www.raywenderlich.com/94404/play-record-merge-videos-ios-swift) | Raywenderlich
[About AVFoundation](https://developer.apple.com/library/content/documentation/AudioVideo/Conceptual/AVFoundationPG/Articles/00_Introduction.html#//apple_ref/doc/uid/TP40010188-CH1-SW3) | Apple文档
[GPUImage](https://github.com/BradLarson/GPUImage) | GPUImage官网
[GPUImage](http://nshipster.com/gpuimage/) | nshipster.com
[iOS动画－－进阶（一）](http://www.macvpn.hk/version/c/phone_share/share.html?shareId=sov) | CatchZeng Blog
[iOS动画高级技术](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques) | AttackOnDobby
[ (译)OpenGL ES 2.x 教程(一)](http://bayonetta.github.io/ios/OpenGL_ES2.0_tutorial_1/) | Bayonetta
[最简单的基于FFmpeg的移动端例子：iOS HelloWorld](http://blog.csdn.net/leixiaohua1020/article/details/47071547) | 雷霄骅
[一些提高UI绘制性能的技巧](http://vizlabxt.github.io/blog/2013/07/12/custom-drawing/) | http://vizlabxt.github.io/
[iOS图形原理与离屏渲染](http://sonnewilling.com/blog/2016/10/19/iostu-xing-yuan-li-yu-chi-ping-xuan-ran/#fn:2) | http://sonnewilling.com/
[iOS富文本组件的实现—DTCoreText源码解析 数据篇](http://blog.cnbang.net/tech/2630/) | bang's blog
[iOS图片加载速度极限优化—FastImageCache解析](http://blog.cnbang.net/tech/2578/) | bang's blog
[Matrix Code Rain及对Core Graphics绘制的优化](https://zshowing.github.io/2016/10/09/Project-Matrix-Code-Rain/) | zshowing.github.io
[SDWebImage 使用小结与原理浅析](https://juejin.im/entry/57664cfb2e958a00697f0989) | SDWebImage 使用小结与原理浅 
[Metal programming guide - Apple文档](https://developer.apple.com/library/content/documentation/Miscellaneous/Conceptual/MetalProgrammingGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40014221-CH1-SW1) | Metal官方文档
[MetalImage](https://github.com/erickingxu/MetalImage) | 基于Metal写的一个图片处理框架
[从0打造一个GPUImage系列文章](https://zhuanlan.zhihu.com/zangqilong) | 叶孤城的iOS杂货铺
[基于 CADisplayLink 的 FPS 指示器详解](https://www.jianshu.com/p/86705c95c224) | iOS中基于CADisplayLink的FPS指示器详解
[Metal Shading Language](https://developer.apple.com/metal/Metal-Shading-Language-Specification.pdf) | Metal的着色器语言 - Apple官方文档
[【iOS开发】关于视频直播技术，你想要知道的都在这里了（一）采集](https://www.jianshu.com/p/ddb640ac4fec) | 七牛云发布，【iOS开发】关于视频直播技术系列
[视频工具箱和硬件加速](https://www.objccn.io/issue-23-3) | ObjC 中国- 视频工具箱和硬件加速
[iOS平台图片编解码入门教程（Image/IO篇）](http://dreampiggy.com/2017/10/30/iOS%E5%B9%B3%E5%8F%B0%E5%9B%BE%E7%89%87%E7%BC%96%E8%A7%A3%E7%A0%81%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B%EF%BC%88Image:IO%E7%AF%87%EF%BC%89/) | iOS平台图片编解码入门教程
[iOS平台图片编解码入门教程（第三方编解码篇）](http://dreampiggy.com/2017/10/30/iOS%E5%B9%B3%E5%8F%B0%E5%9B%BE%E7%89%87%E7%BC%96%E8%A7%A3%E7%A0%81%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B%EF%BC%88%E7%AC%AC%E4%B8%89%E6%96%B9%E7%BC%96%E8%A7%A3%E7%A0%81%E7%AF%87%EF%BC%89/) | iOS平台图片编解码入门教程（第三方编解码篇）
[TUTORIAL: IMAGE RESCALING](https://clouard.users.greyc.fr/Pantheon/experiments/rescaling/index-en.html) | 常见的图像重采样算法处理效果的对比
[关于webp图片格式初探](https://cloud.tencent.com/developer/article/1033988) | 关于webp图片格式初探

#### Swift

文章名称 | 简介 |
----|------|
[Material](https://github.com/CosmicMind/Material) | 很全的UI/UX框架

## 网络相关

文章名称 | 简介 |
----|------|
[NSURLProtocol 全攻略](http://tech.lede.com/2017/02/15/rd/iOS/iOS_NSURLProtocol/) | 网易乐得团队
[iOS应用架构谈 网络层设计方案](https://casatwy.com/iosying-yong-jia-gou-tan-wang-luo-ceng-she-ji-fang-an.html) | iOS应用架构谈 网络层设计方案 - casatwy
[AFNetworking2.0源码解析<一>](http://blog.cnbang.net/tech/2320/) | bang's blog
[AFNetworking源码解析](http://www.guiyongdong.com/2017/02/15/AFNetworking%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90/) | 贵大头
[iOS 网络请求专题](http://liuyanwei.jumppo.com/2016/05/09/iOS-networking-0.html) | 刘彦玮的技术博客
[TCP/IP 系列之包与流](http://mrpeak.cn/blog/tcp-packet-stream/) | TCP/IP 系列之包与流
[DNS劫持](http://sindrilin.com/2017/03/31/DNS%E5%8A%AB%E6%8C%81/) | DNS劫持
[IOS应用架构思考一（网络层）](https://blog.cnbluebox.com/blog/2015/05/07/architecture-ios-1/) | 刘坤
[自己动手写一个 iOS 网络请求库系列一 —— NSURLSession 初探](https://lvwenhan.com/ios/454.html) | 岁寒
[IP，TCP 和 HTTP](https://objccn.io/issue-10-6/) | ObjC中国
[iOS搭建Socket服务器的相关方法](https://ctinusdev.github.io/2017/08/13/BSDSocketServer/#more) | iOS搭建Socket服务器的相关方法

#### Swift

文章名称 | 简介 |
----|------|
[A Simple Approach to Thread-Safe Networking in iOS Apps](https://robots.thoughtbot.com/a-simple-approach-to-thread-safe-networking-in-ios-apps?utm_campaign=iOS%252BDev%252BWeekly&amp;utm_medium=rss&amp;utm_source=iOS_Dev_Weekly_Issue_321) | 网络中线程安全的简单方法

## 内存/数据/存储

文章名称 | 简介 |
----|------|
[持久化学习系列1](http://csbzhixing.github.io/2017/01/08/%E6%8C%81%E4%B9%85%E5%8C%96%E5%AD%A6%E4%B9%A0%E7%B3%BB%E5%88%971/) | 持久化学习系列1 - csbzhixing
[持久化学习系列2](http://csbzhixing.github.io/2017/01/10/%E6%8C%81%E4%B9%85%E5%8C%96%E5%AD%A6%E4%B9%A0%E7%B3%BB%E5%88%972/) | 持久化学习系列2 - csbzhixing
[C程序的内存管理](https://casatwy.com/ccheng-xu-de-nei-cun-guan-li.html) | casatwy.com
[APP 缓存数据线程安全问题探讨](http://blog.cnbang.net/tech/3262/) | bang's blog
[数据持久化](http://sindrilin.com/2015/09/11/%E6%95%B0%E6%8D%AE%E6%8C%81%E4%B9%85%E5%8C%96/) | SindriLin
[APP 缓存数据线程安全问题探讨](http://wereadteam.github.io/2016/11/22/DataCache/) | bang - wereadteam
[微信iOS SQLite源码优化实践](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286361&idx=1&sn=78bbcda7f41a14291ad71289e4821f71&scene=4#wechat_redirect) | 张三华
[SQLite线程模式探讨](http://wereadteam.github.io/2016/08/19/SQLite/) | zepo

#### Swift

文章名称 | 简介 |
----|------|
[Core Data Programming Guide](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreData/index.html#//apple_ref/doc/uid/TP40001075-CH2-SW1) | 官方文档
[Ultimate Guide to JSON Parsing With Swift 4](http://benscheirman.com/2017/06/ultimate-guide-to-json-parsing-with-swift-4/) | 讲解Swift4的Json解析，很详细。
[JSON Parsing in Swift 4](https://troz.net/2017/06/json-parsing-in-swift-4/) | Swift4 Json解析
[Building your own memory manager for C/C++ projects](https://www.ibm.com/developerworks/aix/tutorials/au-memorymanager/) | 教你如何写一个属于自己的Memory Manager
[C程序的内存管理](https://casatwy.com/ccheng-xu-de-nei-cun-guan-li.html) | 清晰易懂
[NSHashTable & NSMapTable](http://nshipster.com/nshashtable-and-nsmaptable/) | NSHashTable & NSMapTable

## 优化/质量/调试/设计模式

文章名称 | 简介 |
----|------|
[卡顿检测](http://sindrilin.com/2017/03/24/%E5%8D%A1%E9%A1%BF%E6%A3%80%E6%B5%8B/) | 卡顿检测 - SindriLin
[优秀日志实践准则](http://tech.lede.com/2017/06/30/rd/server/loggingHabit/) | 优秀日志实践准则 - 网易乐得团队
[iOS无埋点数据SDK实践之路](http://tech.lede.com/2017/02/23/rd/iOS/iOS%E6%97%A0%E5%9F%8B%E7%82%B9%E6%95%B0%E6%8D%AESDK%E5%AE%9E%E8%B7%B5%E4%B9%8B%E8%B7%AF/) | iOS无埋点数据SDK实践之路 - 网易乐得团队
[APP电量测试-三方工具篇](http://tech.lede.com/2017/02/08/qa/AppElecticTest/) | APP电量测试-三方工具篇 - 网易乐得团队
[iOS 保持界面流畅的技巧](http://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/) | iOS 保持界面流畅的技巧 - ibireme
[WebView性能、体验分析与优化](https://tech.meituan.com/WebViewPerf.html) | WebView性能、体验分析与优化 - 美团技术团队博客
[基于 KIF 的 iOS UI 自动化测试和持续集成](https://tech.meituan.com/iOS-UITest-KIF.html) | 基于 KIF 的 iOS UI 自动化测试和持续集成 - 美团技术团队博客
[What's New in LLVM 9](http://yulingtianxia.com/blog/2017/07/17/What-s-New-in-LLVM-2017/) | 作者玉令天下
[iOS微信小视频优化心得](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=207686973&idx=1&sn=1883a6c9fa0462dd5596b8890b6fccf6&3rd=MzA3MDU4NTYzMw==&scene=6#rd) | yanyang
[微信读书 iOS 性能优化总结](https://wereadteam.github.io/2016/05/03/WeRead-Performance/) | WeRead团队 - hypo
[使用 Instruments 做 iOS 程序性能调试](http://www.samirchen.com/use-instruments/) | SamirChen
[与调试器共舞 - LLDB 的华尔兹](https://objccn.io/issue-19-2/) | objccn.io
[LLDB调试命令初探](http://www.starfelix.com/blog/2014/03/17/lldbdiao-shi-ming-ling-chu-tan/) | starfelix.com
[当 NSDictionary 遇见 nil](http://tech.glowing.com/cn/how-we-made-nsdictionary-nil-safe/) | glowing团队
[微信iOS卡顿监控系统](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=207890859&idx=1&sn=e98dd604cdb854e7a5808d2072c29162&scene=4#wechat_redirect) | 微信 iOS 团队 - guoling
[UITableView Tips](https://github.com/vedon/iOS-tech/blob/master/UITableViewOpt/UITableView_Opt.md) | vedon
[perfect-smooth-scrolling-in-uitableviews](https://medium.com/ios-os-x-development/perfect-smooth-scrolling-in-uitableviews-fd609d5275a5) | Alexander Orlov
[解决常见的masksToBounds离屏渲染带来的性能损耗](https://github.com/liuzhiyi1992/MyshareBlogs/wiki/%E8%A7%A3%E5%86%B3%E5%B8%B8%E8%A7%81%E7%9A%84masksToBounds%E7%A6%BB%E5%B1%8F%E6%B8%B2%E6%9F%93%E5%B8%A6%E6%9D%A5%E7%9A%84%E6%80%A7%E8%83%BD%E6%8D%9F%E8%80%97) | 解决常见的masksToBounds离屏渲染带来的性能损耗
[实现 60fps 的网易云音乐首页](https://mp.weixin.qq.com/s?__biz=MzA4MzEwOTkyMQ==&mid=2667379069&idx=1&sn=376d9ef2261cf13e930406f1c35d3569&chksm=84f32833b384a1250ef66f76a8d050216fd3b0bd4ea99b55f4a609cf268c8169ac2889746245&mpshare=1&scene=1&srcid=0810MDXnroCGDhecWqlXazwE&key=05d58d453d781a66b453e3d41dd8d420839dd771948b07f8c8afe3482922901ad13e8c8ab46f48d0883e9b55d304f6ce272854ecc200f68557644581408036c8ee0c5154fbf413a007cd7617b0e086f6&ascene=0&uin=MjY1NTg0NzMyMQ%3D%3D&devicetype=iMac+MacBookPro11%2C4+OSX+OSX+10.12.5+build(16F73)&version=12020810&nettype=WIFI&fontScale=100&pass_ticket=OB4hdN6ImVq0WXd%2BDAJVSADk3OsXMiJH5VzZqXk%2F7meSbJNPMBTUB2z5%2Fct%2BuPmN) | 黄文臣
[iOS实时卡顿监控](http://www.tanhao.me/code/151113.html/) | 老谭笔记
[Instrument Time Profiler总结](http://www.jianshu.com/p/21d29be26479) | 船长_
[iOS 性能监控 SDK —— Wedjat（华狄特）开发过程的调研和整理](https://github.com/aozhimin/iOS-Monitor-Platform) | aozhimin
[移动 H5 首屏秒开优化方案探讨](http://blog.cnbang.net/tech/3477/) | bang's blog
[iOS crash log](http://blog.csdn.net/xiaofei125145/article/details/50408051) |  iOS crash log
[聊聊协议](http://sindrilin.com/2016/08/25/%E8%81%8A%E8%81%8A%E5%8D%8F%E8%AE%AE/) | 聊聊协议
[提升UITableView性能-复杂页面的优化](http://tutuge.me/2015/02/19/%E6%8F%90%E5%8D%87UITableView%E6%80%A7%E8%83%BD-%E5%A4%8D%E6%9D%82%E9%A1%B5%E9%9D%A2%E7%9A%84%E4%BC%98%E5%8C%96/) | 提升UITableView性能-复杂页面的优化
[Instruments tutorial Part 1 - profiling templates, deferred mode, launch instruments](http://www.spotlessicode.com/blog/posts/instruments-tutorial-part-1-profiling-templates-deferred-mode-launch-instruments) | spotlessicode.com
[避免滥用单例](https://objccn.io/issue-13-2/) | 单例是整个 Cocoa 中被广泛使用的核心设计模式之一。
[iOS微信内存监控](https://mp.weixin.qq.com/s/CiqMlEIp1Ir2EJSDGgMooQ) | iOS微信内存监控
[iOS 组件化 —— 路由设计思路分析](https://juejin.im/post/58b2aad6b123db0052cc9edd?utm_source=gold_browser_extension) | iOS 组件化相关
[iOS优化-包大小分析-linkMap](https://dishibolei.github.io/2017/08/17/ios-linkmap/) | iOS优化相关

#### Swift

文章名称 | 简介 |
----|------|
[Error Handling](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/ErrorHandling.html) | 官方文档
[关于 Swift Error 的分类](https://onevcat.com/2017/10/swift-error-category/) |  Swift Error 的分类
[A Beginner’s Guide to Protocols and Protocol Extensions in Swift](https://www.appcoda.com/protocols-in-swift/) | Swift的协议与协议扩展
[Swift Style Guide](https://github.com/linkedin/swift-style-guide) | Swift编码风格指引 - LinkedIn

## 功能/适配/界面相关

文章名称 | 简介 |
----|------|
[自制一款强大的 ActionSheet](http://yulingtianxia.com/blog/2016/07/18/TBActionSheet/) | [玉令天下](http://yulingtianxia.com/blog/2016/07/18/TBActionSheet/)
[UIAlertController in iOS8](http://yulingtianxia.com/blog/2014/09/29/uialertcontroller-in-ios8/) | [玉令天下](http://yulingtianxia.com/blog/2016/07/18/TBActionSheet/)
[有趣的Autolayout示例5-Masonry实现](http://tutuge.me/2017/03/12/autolayout-example-with-masonry5/) | [土土哥](http://tutuge.me/)
[你可能需要为你的APP适配iOS11](http://wetest.qq.com/lab/view/326.html) | wetest.qq
[开发者所需要知道的 iOS 11 SDK 新特性](https://onevcat.com/2017/06/ios-11-sdk/) | OneV's Den

## 安全/逆向

文章名称 | 简介 |
----|------|
[谈谈移动应用的安全性实践](http://tech.glowing.com/cn/tan-tan-yi-dong-ying-yong-de-an-quan-xing-shi-jian/) | 谈谈移动应用的安全性实践
[如何在逆向工程中 Hook 得更准 - 微信屏蔽好友&群消息实战](http://yulingtianxia.com/blog/2017/03/06/How-to-hook-the-correct-method-in-reverse-engineering/) | 如何在逆向工程中 Hook 得更准 - 微信屏蔽好友&群消息实战 - 玉令天下
[Make WeChat Great Again](http://yulingtianxia.com/blog/2017/02/28/Make-WeChat-Great-Again/) | Make WeChat Great Again - 玉令天下
[(iOS冰与火之歌系列，一步一步学ROP系列，安卓动态调试七种武器系列等)](https://github.com/zhengmin1989/MyArticles) | 很全
[【腾讯Bugly干货分享】移动App入侵与逆向破解技术－iOS篇](http://www.jueta.com/appdev/ios-20160708-53017.html) | 微信红包插件原理
[黑科技：把第三方 iOS 应用转成动态库](http://blog.imjun.net/posts/convert-iOS-app-to-dynamic-library/) | 把第三方 iOS 应用转成动态库
[iOS符号表恢复&逆向支付宝](http://blog.imjun.net/posts/restore-symbol-of-iOS-app/) | iOS符号表恢复&逆向支付宝

## 深度学习/人工智能

文章名称 | 简介 |
----|------|
[深度学习及AR在移动端打车场景下的应用](https://tech.meituan.com/cnn_ar_mobile_car_finding.html) | Core ML的应用 - 美团点评技术团队
[Google机器学习速成课程](https://developers.google.cn/machine-learning/crash-course/) | Google
[李宏毅 / 一天搞懂深度學習](https://www.slideshare.net/tw_dsconf/ss-62245351?qid=108adce3-2c3d-4758-a830-95d0a57e46bc&v=&b=&from_search=3) | 需翻墙
---

感谢阅读，如果对大家有帮助，请[github](https://github.com/youngliuxx)上follow和star，转载请注明出处。
