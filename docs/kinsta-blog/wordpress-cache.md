# WordPress 缓存——Kinsta 会处理它，所以你不必这么做

> 原文：<https://kinsta.com/blog/wordpress-cache/>

说到网页性能，WordPress 缓存只是每个网站所有者都必须处理的事情之一。我们喜欢 WordPress，但它绝对不是最快的平台，尤其是如果你把它和一个完全静态的网站相比的话。其中一个原因很简单，因为它是建立在 PHP 上的，而 PHP 只能快速执行。我们看到了 PHP 8.0 和 PHP 8.1 的巨大改进，但是如果你没有正确的缓存你的站点，它仍然会爬行。

如果你不用担心找出哪个缓存插件是最好的，那不是很好吗？嗯，在 Kinsta，我们会为您处理缓存事宜，因此您可以专注于业务发展。

## 什么是 WordPress 缓存？

[缓存](https://kinsta.com/blog/what-is-cache/)是存储来自一个请求的资源并为后续请求重用这些资源的过程。基本上，它**减少了生成一个页面视图所需的工作量**。

为什么应该使用缓存？很简单，缓存使 WordPress 网站更快，并减少网络服务器的负载。这就是为什么每个站点都应该努力使用尽可能多的缓存。此外，在 CDN 缓存的情况下，它还通过存储 WordPress 主机外部的静态资源，减少了生成页面视图所需的服务器带宽。


## Kinsta 不需要 WordPress 缓存插件

没错！如果你用 Kinsta 托管你的 WordPress 站点，你不需要担心搞乱任何复杂和混乱的[缓存插件](https://kinsta.com/blog/wordpress-caching-plugins/)。这是因为我们已经实现了不同类型的缓存。你终于可以停止在谷歌上搜索“2022 年最佳缓存插件”，专注于更有成效的任务。

在 Kinsta，我们利用以下**四种类型的缓存**，它们都是在软件或服务器级别自动完成的:









*   [字节码缓存](#bytecode-cache)
*   [对象缓存](#object-cache)
*   [页面缓存](#page-cache)
*   [CDN 缓存](#cdn-cache)

我们的许多客户报告说，仅仅通过迁移到 Kinsta，加载时间就大大减少了。下面是一个站点的例子，该站点的性能提高了 **212.5%。这是没有安装任何缓存插件。**

![WordPress load times at Kinsta](img/695d33fb502a7f25462c804d03135742.png)

WordPress load times at Kinsta



加载时间的减少还涉及到其他变量，但缓存是其中很大的一部分。我们并不是说所有的缓存插件都是不好的，事实上，很多时候这是由于用户没有正确配置缓存插件，从而降低了他们的 WordPress 站点的速度。有没有试过[配置 W3 总缓存](https://kinsta.com/blog/w3-total-cache/)？很快就会变得非常混乱。

### 不要相信我们的话

至于性能，不要只相信我们的话，看看迁移到 Kinsta 的人的一些评价。所有这些都不再使用缓存插件。

> 将 [@WPColt](https://twitter.com/WPColt?ref_src=twsrc%5Etfw) 移动到 [@kinsta](https://twitter.com/kinsta?ref_src=twsrc%5Etfw) 后，加载时间瞬间减少 37%！(无缓存插件)🚀🚀🚀
> 
> —WP colt(@ WP colt)[2018 年 1 月 3 日](https://twitter.com/WPColt/status/948585957757988865?ref_src=twsrc%5Etfw)