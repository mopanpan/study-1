---
sidebar: auto
sidebarDepth: 2
---
## 环境配置
### 重装系统
- [系统下载](https://msdn.itellyou.cn/)


![头像](/study/spa/timg2.jpg)
- 今天是8.2git 去国外看了个电影(自己能git到吗)

###View的事件分发机制
Widnow是View得载体，在ViewRootImpl的setView方法中添加Winodw到WMS之前，会先调用requestLayout绘制整颗View Hierarchy的绘制
https://user-gold-cdn.xitu.io/2019/7/22/16c1991b84bbb34c?imageslim
- [view官方文档下载]
(https://user-gold-cdn.xitu.io/2019/7/22/16c1991b84bbb34c?imageslim)


###JavaScriipt标准
标准内置对象层主要包含这些东西

特殊值

Infinity
NaN
undefined
null
globalThis


函数

eval()
uneval()
isFinite()
isNaN()
parseFloat()
parseInt()
decodeURI()
decodeURIComponent()
encodeURI()
encodeURIComponent()


基础对象

Object
Function
Boolean
Symbol
Error
EvalError
InternalError
RangeError
ReferenceError
SyntaxError
TypeError
URIError


数值和时间

Number
BigInt
Math
Date


文本处理

String
RegExp


索引容器

Array
'TypedArray'


键值容器

Map
Set
WeakMap
WeakSet


结构化数据

ArrayBuffer
SharedArrayBuffer
Atomics
DataView
JSON


控制抽象化对象

Promise
Generator
GeneratorFunction
AsyncFunction


反射

Reflect
Proxy


国际化

Intl


WebAssembly
其他

arguments
这些全局基本对象数量很少, 这些对象是每个JavaScript开发者必须掌握的.



###标准库？的标准

它们标准库大致都有这些内容：

网络协议
文件系统

文件系统
流
标准输入输出
二进制处理


算法

密码算法
编码
压缩、归档
排序
数学
字符串、文本


数据结构, 例如树、堆、队列等等
数据持久化和序列化. 比如JSON序列化，二进制序列化，数据库操作等等
调试/辅助
单元测试
文档处理
设计模式. 标准库中经常会携带(或辅助设计)该语言的最佳实践和设计模式, 例如go中的context, Ruby中的singleton
国际化
时间、日期
操作系统

命令行
环境变量
系统资源


并发

进程
线程
协程


语言或运行时的底层接口

大部分语言的核心都很小(C++除外)，我们学一门语言，大部分时间是花在标准库上和语言的生态上面，但是你会发现这些标准库一般都是大同小异，这就是为什么有经验的开发者可以很快地入手一门语言.
显然上面这些功能大部分在NodeJS中已经实现了，鉴于NodeJS这么广泛的使用率，NodeJS可以算是事实上的标准了




