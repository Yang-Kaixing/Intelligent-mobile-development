# Flutter-Introduction

### 前导


随着移动开发技术的日渐成熟，一些厂商开始考虑跨平台技术的解决方案，从早期的Cordova、Xamarin，再到后来的React Native和Weex等等，可谓是百家齐放，每种框架都有各自的优缺点，但目标都是一致的，就是提升应用的开发效率，降低研发成本，一套代码运行多个平台。这些框架除了Xamarin外都是采用Web端技术开发移动端应用，但提供比Web更好的用户体验。

### Flutter面世


Flutter是Google在2015年推出的移动UI框架，可快速在iOS和Android上构建高质量的原生用户界面。Flutter第一次亮相于2015年5月Dart开发者峰会上，初始名字叫做“Sky”，后更名为Flutter，Flutter使用Dart语言开发，Dart是Google于2011年推出的新的计算机编程语言。

### Flutter特点

* 快速开发
* 性能优越
* 富有表现力的精美UI

### Flutter框架

![](image/flutter-introduction/1615724571615.png)


### Flutter原理

无论是iOS还是安卓都是提供一个平台的View给Flutter层，页面内容渲染交由Flutter层自身来完成，所以其相对React Native等框架性能更好。Flutter中图形渲染流程：

![](image/flutter-introduction/1615724635358.png)


大致流程如下：

1. GPU的Vsync信号同步到UI线程
2. UI线程使用Dart来构建抽象的视图结构
3. 视图结构在GPU线程中进行图层合成
4. 合成后的视图数据提供给Skia图形引擎处理成GPU数据
5. 数据再通过OpenGL或Vulkan提供给GPU进行渲染

### 结语

以上即是对Flutter的基本介绍，希望能使读者对其有所了解。
