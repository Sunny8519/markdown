#### 一.前言

我们都知道Java中的包装类是有缓存机制的，具体每种包装类缓存的数值范围如下：

|   包装类名称   |   缓存数值范围   |
| :-------: | :--------: |
|   Byte    |  -128~127  |
|   Short   |  -128~127  |
|  Integer  |  -128~127  |
|   Long    |  -128~127  |
|   Float   |    不缓存     |
|  Double   |    不缓存     |
| Charactor |   0~127    |
|  Boolean  | TRUE,FALSE |

本篇文章将分四部分来介绍包装类的缓存机制原理，我们先从Byte/Short/Integer/Long四种类型中具有代表性的Integer包装类开始，然后介绍Float和Double类型为什么不实现缓存，然后再介绍Charactor缓存的实现原理，最后会了解Boolean类中的静态常量TRUE和FALSE。

#### 二.Integer包装类缓存机制

