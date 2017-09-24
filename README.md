# Java-9-Feature-List
Java 9 – The Ultimate Feature List
http://blog.takipi.com/java-9-the-ultimate-feature-list/

# 被接受的特性
1. Jigsaw 项目;模块化源码

Jigsaw项目是为了模块化Java代码、将JRE分成可相互协作的组件，这也是Java 9 众多特色种的一个。JEP是迈向Jigsaw四步中的第一步，它不会改变JRE和JDK的真实结构。JEP是为了模块化JDK源代码，让编译系统能够模块编译并在构建时检查模块边界。这个项目原本是随Java 8发布的，但由于推迟，所以将把它加到Java 9.

一旦它完成，它可能允许根据一个项目需求自定义组件从而减少rt.jar的大小。在JDK 7 和JDK 8的rt.jar包中有大约20,000个类，但有很多类在一些特定的环境里面并没有被用到(即使在Java 8的紧凑分布特性中已经包含了一部分解决方法也存在着类冗余)。这么做是为了能让Java能够容易应用到小型计算设备(比如网络设备)中，提高它的安全和性能，同时也能让开发者更容易构建和维护这些类库。





© 2017，Ricky


