# 如何正确运行网站速度测试(你做错了)

> 原文：<https://kinsta.com/blog/website-speed-test/>

对于你的 WordPress 网站来说，**速度很重要**。这是事实。为什么？首先，网站速度是谷歌算法中的一个重要因素。快速下载网站可以期望[在 SERPs 中排名更高，吸引更多的访问者](https://kinsta.com/blog/what-does-seo-stand-for/)。其次，还有所有用户体验的考虑。如果一个网站加载速度很快，访问者更有可能逗留，阅读你的内容，并最终转化。换句话说，一个闪电般快速的网站解锁所有站长渴望的好东西。

然而，我们今天不是来讨论如何让你的网站更快。我们已经在我们的[加速 WordPress 指南](https://kinsta.com/learn/speed-up-wordpress/)和关于[页面速度的文章](https://kinsta.com/learn/page-speed/)中广泛涉及了这一点。我们在这里讨论另一个我们看到 WordPress 用户每天都会犯的常见问题，那就是不正确地运行网站速度测试。

你可能不认为这是一个大问题…但事实上，这是一个大问题，尤其是当你试图衡量改进的时候。如果你以错误的方式运行网站速度测试，你的网站可能看起来更慢，而实际上它更快。

因此，下面，我们将深入探讨运行网站速度测试的正确方法，以及一些可以用来切实测量网站速度和跟踪任何改进的工具。

## 在你运行网站速度测试之前

在运行速度测试之前，你应该检查你的 WordPress 站点上是否已经配置并运行了以下两个东西:

1.  [缓存](#caching)
2.  [内容传递网络](#cdn)

如果你不知道，请咨询你的网络开发商或主机提供商。如果你正在启动一个全新的网站，确保先**设置好这些东西**，然后运行你的速度测试。





> 需要在这里大声喊出来。Kinsta 太神奇了，我用它做我的个人网站。支持是迅速和杰出的，他们的服务器是 WordPress 最快的。
> 
> <footer class="wp-block-kinsta-client-quote__footer">
> 
> ![A picture of Phillip Stemann looking into the camera wearing a blue button down shirt](img/12b77bdcd297e9bf069df2f3413ad833.png)
> 
> <cite class="wp-block-kinsta-client-quote__cite">Phillip Stemann</cite></footer>

[View plans](https://kinsta.com/plans/)

### 1.配置缓存

如果你是一个 Kinsta 客户端，我们的[服务器级页面缓存](https://kinsta.com/blog/wordpress-cache/)已经在你的 WordPress 站点上运行了，所以你不需要配置任何东西。但是，请记住，出于开发和调试目的，缓存在我们的暂存环境中是默认禁用的。为了[在分段环境](https://kinsta.com/help/staging-environment/#1-page-cache-settings-for-staging-sites)上启用缓存，您可以在 MyKinsta 的工具页面上切换“启用缓存”按钮。

> 将 [@WPColt](https://twitter.com/WPColt?ref_src=twsrc%5Etfw) 移动到 [@kinsta](https://twitter.com/kinsta?ref_src=twsrc%5Etfw) 后，加载时间瞬间减少 37%！(无缓存插件)🚀🚀🚀
> 
> —WP colt(@ WP colt)[2018 年 1 月 3 日](https://twitter.com/WPColt/status/948585957757988865?ref_src=twsrc%5Etfw)