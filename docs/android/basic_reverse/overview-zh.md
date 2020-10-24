[EN](./overview.md) | [ZH](./overview-zh.md)
# Android 逆向基本介绍

首先，我们需要明确一下 Android 逆向的目的： **希望分析出程序的功能** 。那么我们自然也就有两个方面（方法与对象）可以考虑

- 分析方法，可以采用以下方式
    - 静态分析，对源代码进行逆向，然后阅读分析
    - 动态分析，对代码进行动态调试，一般来说动态分析离不开静态分析。
- 分析对象，一般有以下两类对象
    - java，层代码
    - 原生层代码

不难看出，要想分析 Android 应用，基本的 java 层的知识与原生层的知识还是有必要掌握的。

目前来说，Android 逆向主要应用于以下几个方向

1. app 安全审查
2. 系统漏洞挖掘
3. 恶意代码杀查
4. 同行业产品技术原理分析
5. 移除安全机制