﻿ 

   当时我在学netty时, 是从github上拉取的netty原生工程, 然后在本地重新编译运行, 这样我就能在源码工程中写注解, 记笔记...

 

![todo](https://img2018.cnblogs.com/blog/1496926/201912/1496926-20191209144123033-597684128.png)

 

   在这个工程里面大概写了 1400 多行注释(所有的笔记都打上了todo 高亮标记) , 也翻译了一些类和方法上的文档和注释, 不能说百分百正确, 但是这个过程也是挺走心的, 比如netty是如何解决JDK空轮询的bug的? 这些在代码中都是有迹可循的,如下

 

![空轮询bug](https://img2018.cnblogs.com/blog/1496926/201912/1496926-20191209144121926-20869901.png)



\> **另外一个学习的感触就是忘东西, 还有就是随着时间的推移, 接触到技术会越来越多, 确实很难在同一个时间将学的所有的技术都提升到最高的熟练程度,  好处也有, 可能原来学用了一个星期, 现在重新看只要1天就够了**

\> **我更推荐你也这样自己编译一个使用**

\> **致敬真神： Netty的创始人trustin lee 和 Netty的开发者们**