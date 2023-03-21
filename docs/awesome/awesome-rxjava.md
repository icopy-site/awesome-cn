<div class="github-widget" data-repo="eleventigers/awesome-rxjava"></div>
## Awesome RxJava [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="http://reactivex.io/assets/Rx_Logo_S.png" align="right" width="100">](http://reactivex.io/)

&gt; 有用的资源 [RxJava](https://github.com/ReactiveX/RxJava)

*灵感来自 [awesome](https://github.com/sindresorhus/awesome) 列出事情.*

## Bindings

* [RxAndroid](https://github.com/ReactiveX/RxAndroid) - RxJava 的 Android 特定绑定.
* [RxBinding](https://github.com/JakeWharton/RxBinding) - 来自平台和支持库的 Android UI 小部件的 RxJava 绑定 API.
* [rx-preferences](https://github.com/f2prateek/rx-preferences) - 适用于 Android 的反应式“SharedPreferences”.
* [RxPermissions](https://github.com/tbruyelle/RxPermissions) - 由 RxJava 提供支持的 Android M 运行时权限.
* [Android-ReactiveLocation](https://github.com/mcharmas/Android-ReactiveLocation) - 将 Google Play Service API 包装在出色的 RxJava Observables 中的小型库将样板文件减少到最少.
* [ReactiveNetwork](https://github.com/pwittchen/ReactiveNetwork) - Android 库使用 RxJava Observables 监听网络连接状态和 WiFi 信号强度的变化.
* [ReactiveSensors](https://github.com/pwittchen/ReactiveSensors) - 使用 RxJava Observables 监控硬件传感器的 Android 库.
* [RxPalette](https://github.com/hzsweers/RxPalette) - Android 上 Palette 库的 RxJava 绑定.
* [rxjava-jdbc](https://github.com/davidmoten/rxjava-jdbc) - 使用 jdbc 和 RxJava Observables 的数据库调用的高效执行和功能组合.
* [rxjava-file](https://github.com/davidmoten/rxjava-file) - 文件的 RxJava observables，包括 NIO 事件.
* [RxTuples](https://github.com/pakoito/RxTuples) - 与 RxJava 一起使用的简单元组.
* [RxAnimationBinding](https://github.com/blipinsk/RxAnimationBinding) - 用于 Android 动画的 RxJava 绑定 API.

## Utilities
* [RxJavaAsyncUtil](https://github.com/ReactiveX/RxJavaAsyncUtil) - RxJava 的异步实用程序.
* [RxJavaJoins](https://github.com/ReactiveX/RxJavaJoins) - 加入 RxJava 的运算符.
* [RxJavaMath](https://github.com/ReactiveX/RxJavaMath) - RxJava 的数学运算符.
* [RxJavaString](https://github.com/ReactiveX/RxJavaString) - 
RxJava 的字符串和字节运算符.
* [RxJavaComputationExpressions](https://github.com/ReactiveX/RxJavaComputationExpressions) - RxJava 的计算表达式.
* [rxjava-extras](https://github.com/davidmoten/rxjava-extras) - 与 RxJava 一起使用的实用程序.
* [RxActions](https://github.com/pakoito/RxActions) - 与 RxJava 一起使用的简单 ActionN 组合.
* [RxRelay](https://github.com/JakeWharton/RxRelay) - 既是 Observable 又是 Action1 的 RxJava 类型.
* [Frodo](https://github.com/android10/frodo) - 用于记录 RxJava 可观察对象和订阅者的 Android 库.
* [RxPartialApplication](https://github.com/pakoito/RxPartialApplication) - RxJava 上 FuncN 和 ActionN 的简单部分应用.
* [RxCurrying](https://github.com/pakoito/RxCurrying) - 在 RxJava 上对 FuncN 和 ActionN 进行简单套用.
* [RxEither](https://github.com/eleventigers/rxeither) - RxJava 的任一类型.
* [RxReplayingShare](https://github.com/JakeWharton/RxReplayingShare) - 结合了 replay(1)、publish() 和 refCount() 运算符的 RxJava 转换器.
* [RxFunctions](https://github.com/pakoito/RxFunctions) - 与 RxJava 一起使用的高级函数组合.
* [rxlint](https://bitbucket.org/littlerobots/rxlint) - 用于 RxJava 代码的 Android lint 规则.
* [RxComprehensions](https://github.com/pakoito/RxComprehensions) - 通过抽象链式 flatMaps、concatMaps 和 switchMaps 减少 RxJava 中的样板文件.

## Testing
* [assertj-rx](https://github.com/ribot/assertj-rx) - RxJava Observables 的 AssertJ 断言.
* [rxpresso](https://github.com/novoda/rxpresso) - 使用 RxJava 对 Android 应用程序进行简单的 Espresso UI 测试.

## Guides

* [RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples) - 通过示例学习适用于 Android 的 RxJava.
* [Intro-To-RxJava](https://github.com/Froussios/Intro-To-RxJava) - 关于 RxJava 的详尽教程.

## Articles

* [Rx glitches aren't actually a problem](http://staltz.com/rx-glitches-arent-actually-a-problem.html)  - 故障是 Observables 发出的临时不一致.  André Staltz 分析了为什么这不是真正的问题.
* [RxJava's repeatWhen and retryWhen, explained](http://blog.danlew.net/2016/01/25/rxjavas-repeatwhen-and-retrywhen-explained/)  - `repeatWhen` 和 `retryWhen` 乍一看相当令人费解.  Dan Lew 深入解释了运算符.
* [RxJava - The Problem with Subjects](http://tomstechnicalblog.blogspot.co.uk/2016/03/rxjava-problem-with-subjects.html) - Thomas Nield 解释了为什么 `Subject` 不是灵丹妙药.

## Tools

* [RxMarbles](http://rxmarbles.com/) - Rx Observables 的交互式图表.

## Community

* [Google Group](http://groups.google.com/d/forum/rxjava)
* [StackOverflow](http://stackoverflow.com/search?q=rx-java)
* [`@RxJava` on Twitter](http://twitter.com/RxJava)
* [`ReactiveX/RxJava` on Gitter](https://gitter.im/ReactiveX/RxJava)
* [GitHub Issues](https://github.com/ReactiveX/RxJava/issues)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Jokubas Dargis](http://jokubasdargis.net/) 已放弃该作品的所有版权和相关或邻接权.
