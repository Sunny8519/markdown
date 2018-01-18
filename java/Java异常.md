#### 一.异常的分类

Java中的异常基类为Throwable，Error和Exception都继承自Throwable。

Error是指当前应用程序无法处理的错误，通常这些Error都是来自虚拟机，一般情况下我们不需要特别关注。

Exception是指代码异常，如果代码中抛出了这种异常就说明应用程序有问题。它分为RunTimeException和CheckTimeException，RunTimeException又叫做**运行时异常**，这种异常通常是在应用程序运行的过程中发生的，比如最常见的NullPointerException、IllegalArgumentException等等，一般情况下这些异常是由系统来处理，不需要我们人为去捕获。CheckTimeException叫做**编译时异常**，顾名思义，这种异常如果我们不进行人为捕获处理的话，编译器是不会通过的。

#### 二.异常处理机制



#### 参考

[异常上](http://mp.weixin.qq.com/s/SB5d0IU7aj-hRSneg3hE9g)

[异常下](http://mp.weixin.qq.com/s/8XiwZGn8djtO7TvtonAe8w)

[Java基础夯实2：全面了解异常](https://mp.weixin.qq.com/s/q0jsOrBSNezGIBOzozlQzA)



