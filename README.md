

这是慕课网官方实战课【[Flutter从入门到进阶-实战携程网App](https://coding.imooc.com/class/321.html)】的项目源码，课件，文档。

>课程会不定期更新，建议大家多关注下仓库首页的变更记录以便获得最新的更新内容哦



## 更新日志

### 2022-11-26：更新flutter_staggered_grid_view
-   flutter_staggered_grid_view: ^0.6.2 

### 2022-05-21：支持Flutter 3.x
- Flutter 3.x 支持
- compileSdkVersion & targetSdkVersion 升级
- `android:name="io.flutter.app.FlutterApplication"` to `android:name="${applicationName}"`
- gradle-5.6.2 to gradle-6.1.1
- kotlin_version = "1.3.72" to ext.kotlin_version = '1.6.10'
- dart 代码和空安全优化
- flutter_splash_screen: ^0.3.0 to flutter_splash_screen: ^1.0.0+6

### 2021-11-21：更新基础知识十六讲

- flutter_base_demo 适配Flutter 2.5.3；
- flutter_base_demo support null safety；
- image_picker 与 url_launcher upgrade；

### 2021-10-30：Flutter升级适配空安全以及适配最新百度SDK

- Flutter升级适配v2.5.x；
- 代码适配空安全；
- 百度SDK升级适配最新版本

### 2020-6-7：Flutter升级适配v1.17.0及以上版本

- Flutter升级适配v1.17.0及以上版本；
- 旅拍页面优化防止抖动，以及添加图片淡入效果；

### 2020-2-19：文档教程更新，下面是具体更新的内容👇

- 更新《Flutter快速上手指南》文档教程

### 2020-1-16：代码更新，下面是具体更新的内容

- 主项目升级适配最新版Flutter
- 主要更新如下：
	- `MainActivity.java`更新注册AsrPlugin的方式，解决新版SDK 中registrarFor不存在的问题
	- Android 工程适配targetSdkVersion 29
	- 搜索输入框样式优化

### 2019-12-30：代码&资料更新
* 更新适配Flutter >=v1.12.x
* 更新混合开发部分的源码和辅导文档
	* [源码](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_hybrid)
	* 文档：
		* [Flutter与Android混合开发实战 辅导资料-持续更新](https://coding.imooc.com/learn/questiondetail/150166.html)
		* [Flutter与Android通信开发指南](http://coding.imooc.com/learn/questiondetail/135975.html)

## 概述

- 课程接口文档查看[doc](https://git.imooc.com/coding-321/flutter_trip/src/master/doc);
- 课程中所用到的demo查看[demo](https://git.imooc.com/coding-321/flutter_trip/src/master/demo);
- [各章节源码和课件查看指南](https://git.imooc.com/coding-321/flutter_trip#%E5%90%84%E7%AB%A0%E8%8A%82%E6%BA%90%E7%A0%81%E5%92%8C%E8%BE%85%E5%AF%BC%E6%96%87%E6%A1%A3%E6%9F%A5%E7%9C%8B%E6%8C%87%E5%8D%97)
- [Flutter必备Dart基础课件](https://git.imooc.com/coding-321/flutter_trip/src/master/doc/Flutter%e5%bf%85%e5%a4%87Dart%e5%9f%ba%e7%a1%80%e8%af%be%e4%bb%b6.md)


## 课程辅导答疑

[http://coding.imooc.com/learn/qa/321.html](http://coding.imooc.com/learn/qa/321.html)

## 如何运行？

1. 安装和配置Flutter开发环境(如已经配置过可跳过)，可参考课程[Flutter入门：开发工具准备与开发环境搭建](https://coding.imooc.com/class/321.html)一章的讲解。
2. 在项目根目录运行`flutter run`或用装有Flutter和Dart插件的IDE运行；
3. Ok,有问题可以在[课程讨论区](https://coding.imooc.com/class/321.html)提issue哦;

## 各章节源码和辅导文档查看指南

>为方便同学们学习，课程为大家提供了课件和各章节的源码，请通过以下方式查看：

- [实战部分各章节源码查看方法-点击查看](https://git.imooc.com/coding-321/flutter_trip/src/master/doc/如何查看各章节的源码.md)
	- [可通过git查看这部分章节的源码](https://git.imooc.com/coding-321/flutter_trip/src/master/doc/如何查看各章节的源码.md)
- 基础部分的文档和源码
    - Flutter学习经验：Flutter快速上手指南
		- [Android开发者如何快速上手Flutter开发](https://coding.imooc.com/learn/questiondetail/168176.html)
		- [iOS开发者如何快速上手Flutter开发](https://coding.imooc.com/learn/questiondetail/168177.html)
		- [React Native开发者如何快速上手Flutter开发](https://coding.imooc.com/learn/questiondetail/168181.html)
		- [前端开发者如何快速上手Flutter开发](https://coding.imooc.com/learn/questiondetail/168183.html)
	- Flutter入门：开发工具准备与开发环境搭建
		- [Flutter开发环境搭建（Mac）](http://www.imooc.com/article/284328)
		- [Flutter开发环境搭建（Windows）](https://www.devio.org/2019/04/07/development-environment-windows/)
	- Flutter必备Dart基础：Dart快速入门
		- [Dart知识体系](https://coding.imooc.com/learn/questiondetail/134658.html)
		- [Flutter之Dart常用数据类型](https://coding.imooc.com/learn/questiondetail/134659.html)
		- [带你揭开Flutter中的面向对象](https://coding.imooc.com/learn/questiondetail/134661.html)
		- [带你解锁Flutter中常用的Dart方法类型](https://coding.imooc.com/learn/questiondetail/134662.html)
		- [带你了解Dart泛型在Flutter中的应用](https://coding.imooc.com/learn/questiondetail/134663.html)
		- [有哪些可以用在Flutter上的编程技巧？](https://coding.imooc.com/learn/questiondetail/134664.html)
	- Flutter入门：基础知识十六讲
        - [如何使用Flutter包和插件？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [StatelessWidget与基础组件](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [StatefulWidget与基础组件](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [如何进行Flutter布局开发？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
            - [本节脑图](https://coding.imooc.com/learn/questiondetail/151900.html)
        - [如何创建和使用Flutter的路由与导航？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [如何检测用户手势以及处理点击事件？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [如何导入和使用Flutter的资源文件？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [如何打开第三方应用？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [如何修改Flutter应用的主题？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [如何自定义字体？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [Flutter 页面生命周期实战指南](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [如何获取Flutter应用的生命周期？](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
        - [实战尝鲜】拍照APP开发-图片获取与图片展示](https://git.imooc.com/coding-321/flutter_trip/src/master/demo/flutter_base_demo)
	- Flutter入门：Flutter必备基础
		- [图片控件开发详解](https://coding.imooc.com/learn/questiondetail/134875.html)
		- [动画Animation开发指南](https://git.imooc.com/coding-321/flutter_trip/src/master/doc/动画Animation开发指南.md)
	- Flutter进阶提升：网络编程与数据存储技术
		- [基于Http实现网络操作](https://coding.imooc.com/learn/questiondetail/134644.html)
		- [异步：Future与FutureBuilder实用技巧](https://coding.imooc.com/learn/questiondetail/134645.html)
		- [JSON解析与复杂模型转换实用技巧](https://coding.imooc.com/learn/questiondetail/134649.html)
		- [基于shared_preferences的本地存储操作](https://coding.imooc.com/learn/questiondetail/134650.html)
	- Flutter进阶提升：玩转列表组件
		- [基于ListView实现水平和垂直方式滚动的列表](https://coding.imooc.com/learn/questiondetail/134653.html)
		- [基于ExpansionTile实现可展开的列表](https://coding.imooc.com/learn/questiondetail/134654.html)
		- [基于GridView实现网格布局](https://coding.imooc.com/learn/questiondetail/134655.html)
		- [高级功能列表下拉刷新与上拉加载更多功能实现](https://coding.imooc.com/learn/questiondetail/134656.html)
	- Flutter进阶提升：Flutter混合开发
        - [Flutter与Android混合开发实战 辅导资料-持续更新](https://coding.imooc.com/learn/questiondetail/150166.html)
        - [Flutter与iOS混合开发实战 辅导资料-持续更新](https://coding.imooc.com/learn/questiondetail/150168.html)
		- [Flutter与Android通信开发指南](http://coding.imooc.com/learn/questiondetail/135975.html)
		- [Flutter与iOS通信开发指南](https://coding.imooc.com/learn/questiondetail/159484.html)
- **其他部分的辅导文档和源码查看方法**
    - 方法一： -> [通过git查看](https://git.imooc.com/coding-321/flutter_trip/src/master/doc/如何查看各章节的源码.md)
	- 方法二： -> 通过锚点查看（锚点只覆盖了部分章节的文档哦）：
	![doc-learn-help](http://www.devio.org/io/flutter_app/img/blog/doc-learn-help2.jpg)

	>然后通过如下方式查看锚点中的文档：
	![doc-learn-help](http://www.devio.org/io/flutter_app/img/blog/doc-learn-help1.jpg)


