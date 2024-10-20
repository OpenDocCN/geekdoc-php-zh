# 为什么试图成为一名系统管理员来节省每月 20 美元不是一个好主意

> 原文：<https://kinsta.com/blog/sysadmin/>

一次又一次，我们在论坛和社交媒体上看到用户抱怨托管 WordPress 主机是对金钱的巨大浪费。他们的理由？管理自己的服务器会好很多。不幸的是，他们从来没有提到这一切实际上意味着什么。对于一个不经意的 WordPress 用户来说，这肯定会给人错误的印象。这听起来很容易，也很便宜，但最终的结果是你可能会花费比你想象的更多的时间和金钱。

你可能会想，“你们这些家伙是一个[应用](https://kinsta.com/application-hosting/)、[数据库](https://kinsta.com/database-hosting/)、[管理 WordPress 托管](https://kinsta.com/wordpress-hosting/)公司，这样不就有点偏心了吗？”也许吧，但我们也有优势，能看到双方的视角。

我们在 Kinsta 团队中有系统管理员，他们为客户管理我们自己的所有服务器，因此，我们知道如何正确地做这件事，以及为什么对你们大多数人来说，**成为系统管理员实际上是一个坏主意**。事实上，在某些情况下，这可能是一场彻头彻尾的噩梦。作为一名系统管理员需要很大的耐心和技巧，而且你必须真正喜欢修复坏掉的东西！

![Sysadmin meme](img/fb3d8714af278754092d1e6f0bd7cb8e.png)

Sysadmin meme (Image source: [quickmeme](http://www.quickmeme.com/meme/35cm7g))



除了我们自己的团队之外，我们还可以看到来自客户的所有反馈，这些客户以前试图自己管理一切。一旦他们到达像金斯塔这样的主机，答案几乎总是，“它值得每一分钱。”

如果你正在考虑是管理你自己的服务器(作为一名系统管理员)还是去找一个主机提供商，这篇文章是为你准备的！下面我们将深入探讨所有的优点和缺点。是的，两边都有好有坏。

 

## 什么是系统管理员？

系统管理员(sysadmin)是负责配置、更新和保持服务器运行的人员。我们在 Kinsta 的系统管理员全天候在幕后工作，以确保一切顺利运行。当一台服务器停机时，系统管理员的工作就是查找故障原因并使其恢复运行。

Support

任何人在某种程度上都可以是系统管理员。这并不一定意味着他们是一个好的或应该这样做。😉但是，如果一个人负责管理他们的站点所在的服务器，那么很可能他是在做系统管理员的工作。我们将在下面详细介绍通常伴随而来的所有责任。









## 作为系统管理员的优势

很快，你可能会说我们对这个话题有很强烈的看法。但是不要误解我们，成为一名系统管理员并不全是坏事。事实上，它肯定比使用托管 WordPress 主机有一些优势。

然而，这肯定需要某种心态和个人来做好这一点。我们所说的“好”是指，不要因为花费比实际工作更多的时间来修复和排除故障而造成损失。无论你是企业主、WordPress 开发者，还是[代理](https://kinsta.com/blog/wordpress-agency/)，你都应该问问自己；你应该花时间做的最重要的任务是什么？你有能力成为一名系统管理员吗？
T3】

### 1.准系统/VPS 非常便宜

成为自己的系统管理员的第一个原因是，大多数准系统和虚拟专用服务器(VPS)的原始成本实际上非常便宜！如果你有能力和技术专长，你肯定能省下一些钱。

例如，如果你看一看来自 Linode、Digital Ocean 或 Vultr 的 VPS，这些**起价低至 5 美元/月**。这甚至比大多数共享主机提供商更便宜。有些甚至提供基于所用资源的现收现付计划。

![Digital Ocean prices](img/26aba05e7bc8fdf88fb141fe001533ca.png)

Digital Ocean prices



这里的警告是，这些机器不只是即插即用。你只是在为 CPU、RAM、磁盘等付费。虽然他们中的许多人都有一键式应用程序，但其他一切都由你负责。您可以尝试使用 ServerPilot 之类的工具来简化这一过程，但这并不能在您最需要的时候为您提供全天候支持。这是为什么这种方式通常被称为 DIY 托管的原因。

### 2.你可以安装任何你想安装的东西

显然，成为你自己的系统管理员的最大好处之一就是你可以完全控制所有的事情。你可以在你的服务器上安装和运行任何你想要的东西。需要安装像 Ioncube 这样的软件包或 PHP 扩展吗？你不必担心询问支持团队会降低速度，你可以简单地将 SSH[到你的服务器](https://kinsta.com/help/connect-to-ssh/)中，然后自己安装。

### 3.您将获得完全的根用户访问权限

与上面相关的是，有些东西需要 root 权限才能安装在服务器上。当使用托管 WordPress 主机时，你通常[不会获得 root 访问权限](https://kinsta.com/help/technical-faq/#do-you-provide-root-access)。为什么？因为他们不能冒你弄坏东西的风险。一个错误的命令就可能导致服务器停机。Root 访问是一把“双刃剑”然而，如果你有技能，那么拥有完全根权限的**就派上用场了**。仅仅这个原因有时就是用户选择管理自己的服务器的原因。

### 4.有可能实现令人敬畏的性能

另一个优势是，如果配置得当(通常这需要大量的工作和知识)，**您可以在管理自己的服务器时获得惊人的性能**。这是因为准系统资源通常相当便宜，而且由于你管理一切，你可以确保没有资源被任何其他站点共享。事实上，很多网站用户倾向于购买比他们网站实际使用的更多的资源。
T3】

## 作为系统管理员的缺点

现在是时候深入了解作为一名系统管理员的许多缺点了。是的，正如你可能猜到的，缺点比优点多得多。但这也是系统管理员的工作如此重要的原因。你只要问自己，那个人应该是你吗？

[Being a sysadmin takes a lot of patience, skill, and you have to really enjoy fixing things that break! 😩Click to Tweet](https://twitter.com/intent/tweet?url=https%3A%2F%2Fbit.ly%2F2Avlv8i&via=kinsta&text=Being+a+sysadmin+takes+a+lot+of+patience%2C+skill%2C+and+you+have+to+really+enjoy+fixing+things+that+break%21+%F0%9F%98%A9&hashtags=sysadmin%2Cwebhosting)

我们还将向您展示，在 Kinsta，您可以不费吹灰之力完成每一项任务。

### 1.服务器的设置和配置完全是你的责任

每当你需要一个新的服务器，设置它完全是你的责任。如果您使用的是准系统机器或 VPS 提供商，这通常意味着启动一台新机器。所以你最好知道根据你的流量，你的站点需要多少内存、CPU 和 PHP 工作人员。您还必须知道数据库的内存需求( [InnoDB 缓冲池](https://kinsta.com/knowledgebase/convert-myisam-to-innodb/))、系统内存需求、php-fpm worker 需求等。).

在它运行之后，您必须对它进行配置。根据您的需求，这可能包括各种任务，例如:

*   分配 [IP 地址](https://kinsta.com/tools/what-is-my-ip/what-is-my-ip/)
*   设置 DNS 记录
*   安装 Nginx/Apache(看看我们的 web 服务器对决: [Nginx vs Apache](https://kinsta.com/blog/nginx-vs-apache/) )
*   安装 PHP
*   安装软件包，如 Node 或 Yarn
*   安装 PHP 扩展，如 Ioncube 或 Recode
*   更新至最新版本的 [MySQL 或 MariaDB](https://kinsta.com/blog/mariadb-vs-mysql/)

如果你使用的是准系统，安装(和升级)和配置 WordPress 所需的所有服务可能需要几天时间。如果你使用自动安装程序，你仍然不知道如何保持机器更新或安全。MySQL 和 php-fpm 设置也是如此。确切地知道要改变什么，改变到什么值，可以使白天和黑夜有所不同。

许多人没有意识到幕后发生的一切。在 Kinsta，我们定制编译了一堆 Linux 包以获得最佳性能。这几乎不可能靠你自己来完成，因此你会从一开始就失去性能。我们的 Nginx 规则集是基于我们运行数万个高流量 WordPress 网站的经验而构建的。这些规则集包括从安全性到性能调整的所有内容。

我们也有超过 30 个不同的软件包和 PHP 扩展，通常由客户使用。对于那些可能不熟悉安装服务器端软件的人来说，这些通常不只是一键安装程序。为了给你一个更好的印象，下面是如果你自己安装 Ioncube (PHP 扩展)的典型步骤:

1.  将 Ioncube 下载并解压缩到服务器
2.  将文件复制到 PHP 目录中
3.  编辑 php.ini 文件
4.  测试并重新加载 Nginx
5.  重启当前的 PHP 引擎
6.  检查日志，清除缓存等。

换句话说，如果您正在管理自己的服务器，请确保在需要时留出一些时间来配置新的服务器。之后，你仍然需要安装和设置你的 WordPress 网站。

#### 在 Kinsta 推出新网站

如果你使用一个应用程序、数据库和托管的 WordPress 主机，比如 Kinsta，你不需要在服务器上配置任何东西。您可以随时启动新网站。只需登录 MyKinsta 仪表盘，点击“[添加一个站点](https://kinsta.com/help/new-site/)”你最大的任务就是从我们为你提供的 35 个不同的[数据中心位置](https://kinsta.com/knowledgebase/google-cloud-data-center-locations/)中进行战略选择。

![Launch new WordPress site at Kinsta](img/f3b0981b83167cb9ab3b1aefb22a7512.png)

Launch new site at Kinsta



需要安装像 Ioncube 这样的新软件包或 PHP 扩展吗？很可能它已经在 Kinsta 的服务器上运行了。但是如果没有，你可以通过点击仪表板上的一个按钮轻松地[启用它。](https://kinsta.com/blog/ioncube-loader/)

### 2.你必须做好备份

当您管理自己的服务器时，您很可能需要自己的备份解决方案。一些提供商可能会为此提供额外的服务，但通常并不完美。例如，如果你正在使用数字海洋水滴，他们只提供你的机器每周的快照。他们还**增加了 20%的成本**。任何人都会同意，每周备份远远不够。

这还只是服务器备份。很可能你也想为你的 WordPress 站点本身配置一个单独的异地备份解决方案，特别是当你在一个服务器上有多个站点的时候。因此，这可能会导致解决方案和存储它们的磁盘空间的额外成本。看看几个推荐的 [WordPress 增量备份插件](https://kinsta.com/blog/wordpress-backup-plugins/)。
T3】

#### Kinsta 的备份工作方式

Kinsta 的备份再简单不过了！在服务器级别，我们在 24 小时内每隔 4 小时为基础架构中的每台机器创建并存储[永久磁盘快照](https://cloud.google.com/compute/docs/disks/create-snapshots),然后在两周内每隔 24 小时创建并存储一次。Google Cloud Platform 通过自动校验和自动在多个位置冗余存储每个快照的多个副本，以确保数据的完整性。

这意味着快照存储在与其最初创建位置不同的数据中心。如果我们的谷歌云平台基础设施受到影响，我们总会有快照需要恢复。

然后，当涉及到您的站点时，Kinsta 提供[自动每日备份](https://kinsta.com/help/wordpress-backups/)、可下载备份、手动备份还原点，甚至系统生成备份，即在特定事件期间创建的自动系统备份。如果这还不够，我们还有一个每小时备份插件，您可以购买它来创建每小时或每 6 小时的备份。备份存储在永久磁盘快照中(在多个位置)。

正因为如此，如果你用 Kinsta 做主机，就不需要备份插件了。🤘您可以通过单击一个按钮来恢复备份，甚至可以将它们复制到您的暂存环境中。更好的是，Kinsta 不把你的备份包括在你的总磁盘空间使用量中。

![WordPress backups](img/91bf4fce39f6684bbfdb2c1b66d8a66f.png)

WordPress backups



### 3.锁定你的服务器和 WordPress 网站取决于你自己

当您管理您的服务器时，锁定它们由您决定。Linux 加固，一般来说，**需要多年的经验**。

如果恶意代码进入您的网络，或者有人发起暴力攻击，您将对此负责。然后还有 [DDoS 攻击](https://kinsta.com/blog/what-is-a-ddos-attack/)可以在几分钟内让你的服务器离线。相信我们， **DDoS 攻击总是在最糟糕的时候到来**。你最好知道如何识别源头并阻止它。

[DDoSd on a Saturday night while camping? ⛺ This is just one of the many reasons you don't want to be a sysadmin.Click to Tweet](https://twitter.com/intent/tweet?url=https%3A%2F%2Fbit.ly%2F2Avlv8i&via=kinsta&text=DDoSd+on+a+Saturday+night+while+camping%3F+%E2%9B%BA+This+is+just+one+of+the+many+reasons+you+don%27t+want+to+be+a+sysadmin.&hashtags=ddos%2Csysadmin)

保护您的服务器和 WordPress 站点包括各种不同的任务，例如:

*   实施[硬件和软件防火墙](https://kinsta.com/blog/what-is-a-firewall/)(从服务器级软件到 web 应用[防火墙，如 Cloudflare](https://kinsta.com/blog/cloudflare-settings-wordpress/#firewall) 或 Sucuri)。
*   安装[恶意软件扫描软件](https://kinsta.com/blog/types-of-malware/#removing-malware-from-a-wordpress-website)。这通常需要 Linux 和 WordPress。
*   修补 Nginx/Apache 或用安全更新更新 PHP。
*   收紧服务器上的文件/文件夹限制。
*   清理被黑的 WordPress 网站(你永远无法 100%保护 WordPress，它所需要的只是一个坏插件)。

WordPress 很棒，但是今年是我们见过的插件漏洞最严重的一年。你最好确保你知道如何正确地清理 WordPress 网站上的恶意软件。我们一次又一次地听到用户自己尝试这样做，并为此奋斗了几天！

以下是我们金斯塔团队最近不得不处理的几起事件:

*   [供应商后门&pip dig 电源包中的可疑代码](https://wpvulndb.com/vulnerabilities/9247)
*   [XSS 和 RCE 社交战插件中的漏洞和攻击数据](https://www.webarxsecurity.com/social-warfare-vulnerability/)
*   [未经授权调用 Yuzo 相关帖子插件中的任何动作](https://wpvulndb.com/vulnerabilities/9254)
*   [黄色铅笔视觉主题定制器中的零日漏洞](https://www.wordfence.com/blog/2019/04/zero-day-vulnerability-in-yellow-pencil-visual-theme-customizer-exploited-in-the-wild/)
*   [重复页面 WordPress 插件中的 SQL 注入](https://blog.sucuri.net/2019/04/sql-injection-in-duplicate-page-wordpress-plugin.html)
*   [WP 谷歌地图插件中未经认证的 SQL 注入](https://wpvulndb.com/vulnerabilities/9249)

请务必阅读我们关于 SQL 注入的深度[指南。](https://kinsta.com/blog/sql-injection/)

一些 VPS 提供商，如 Digital Ocean，提供云防火墙。但是实现它们仍然取决于您，例如，您需要知道端口上的哪些入站规则，哪些 IP 地址应该被列入黑名单或白名单，等等。

![Sysadmin security](img/2c4282031e2fb312ddc6eb99eeee4418.png)

Sysadmin security (Image source: [Reddit](https://www.reddit.com/r/ProgrammerHumor/comments/7ptgok/))



#### 晚上在金斯塔的诺克斯堡像安全一样高枕无忧

你真的想把周末花在抵御黑客或阻止 DDoS 攻击上吗？你知道怎么做吗？这就是为什么除非你在安全方面有很强的技术能力，否则你迟早会遇到严重的安全问题。

如果你有一个应用程序、数据库和托管的 WordPress 主机，比如 Kinsta，我们会为你处理所有这些。这里只是我们在所有托管计划中提供的一些安全特性。

*   Kinsta 检测 DDoS 攻击，**监控正常运行时间**，自动封禁一分钟内登录失败次数超过 6 次的 IP。
*   当直接访问你的 WordPress 站点时，只支持加密的 SFTP 和 SSH 连接(不支持 FTP)(这里是 [FTP 和 SFTP](https://kinsta.com/knowledgebase/ftp-vs-sftp/) 的区别)。
*   硬件防火墙以及额外的主动和被动安全措施可以防止对您数据的访问。
*   我们对前端请求隐藏了你正在使用的 WordPress 和 PHP 版本。我们的 open_basedir 限制也不允许在容易受到恶意脚本攻击的公共目录中执行 PHP。
*   Kinsta uses Linux containers (LXC) on top of [Google Cloud Platform (GCP)](https://kinsta.com/blog/google-cloud-network/) which provides **complete isolation** for not just each account, but each separate site. This is a much more secure method than offered by other competitors. GCP also employs data encryption at rest.

    ![Kinsta hosting architecture.](img/21a65cbd1cd07d0fab62adae62849915.png)

    金斯塔主持架构。

    

*   Kinsta 利用谷歌云平台的[高级层网络](https://kinsta.com/blog/google-cloud-network/)和[企业级防火墙](https://cloud.google.com/vpc/docs/firewalls)。我们的防火墙配置允许我们在恶意流量进入我们的虚拟机网络之前将其拦截。与 GCP 的标准层网络相比，高级层通过谷歌快速安全的专用网络传输更多流量。
*   Kinsta 只运行支持的 PHP 版本:7.2、 [7.3](https://kinsta.com/blog/php-7-3/) 和 [7.4](https://kinsta.com/blog/php-7-4/) (不包括淘汰时间)。不受支持的 PHP 版本是危险的，因为它们不再有安全更新，并暴露于未打补丁的安全漏洞。

没有什么是 100%防黑客的，这就是为什么 Kinsta 为所有客户提供免费的黑客补丁。没错！在最近那些与社会战争，WP 谷歌地图等插件漏洞。我们的团队让客户知道并清理了受影响的网站。在某些情况下，我们的系统管理员甚至在服务器级别修补东西。我们非常重视安全性，并且在涉及到您的网站时会积极主动。

### 4.确保选择正确的缓存解决方案

说到性能，没有什么比[缓存](https://kinsta.com/blog/wordpress-cache/)更重要了！

缓存是存储来自一个请求的资源并为后续请求重用这些资源的过程。基本上，它减少了生成页面视图所需的工作量。您希望**尽可能多地从缓存中为您的站点提供服务**。这就是那些光速如此之快的原因。

当涉及到管理您自己的服务器时，您将需要做出决定。你应该实现一个服务器级的缓存解决方案(比如 [`nginx fastcgi cache module`](http://nginx.org/en/docs/http/ngx_http_fastcgi_module.html#fastcgi_cache) )还是用一个 [WordPress 缓存插件](https://kinsta.com/blog/wordpress-caching-plugins/)比如 WP Rocket？混合方法也是另一种选择。

除非你已经测试了几十种不同的解决方案和技术，否则你怎么知道哪一种是最好的或最快的呢？作为一名系统管理员，你应该明白字节码缓存、对象缓存、页面缓存、Varnish、Redis 等的区别。，以及它们如何与服务器和插件交互。拥有一个良好的缓存解决方案意味着慢速和快速站点之间的区别。

#### Kinsta 为您处理缓存(不需要插件)

如果您使用 Kinsta 托管，我们会在服务器级别自动为您处理缓存。我们的服务器使用`nginx fastcgi cache module`来提供快速页面缓存。

页面缓存配置为开箱即用，支持标准的 WordPress、BuddyPress、 [WooCommerce](https://kinsta.com/woocommerce-hosting/) 和[简易数字下载](https://kinsta.com/blog/easy-digital-downloads/)网站。你什么都不用做！只需启动你的 WordPress 站点，页面缓存就会开始。

每当您对页面或博客文章进行编辑时，页面的缓存以及归档页面都会自动清除。这确保您的访问者看到新鲜和最新的内容。我们还对归档页面施加了最短的节流时间，以确保始终保持高可用性。

虽然它在技术上不是一个缓存插件，但我们的必须使用(MU)插件安装在每个网站上，让您可以更精细地控制您的缓存。你可以很容易地从 WordPress 管理工具栏清除你站点的缓存，或者添加自定义路径，以便在我们站点更新时清除。

![Granular caching controls at Kinsta](img/9e3ef007e0f128f5188a5b6e7db46dc4.png)

Granular caching controls at Kinsta



你也可以通过简单的点击从 MyKinsta 仪表板中清除整个 WordPress 站点的缓存。

![Clear WordPress cache in MyKinsta dashboard](img/1d5bf499bb5202b0e661bf0fd580251c.png)

Clear WordPress cache in MyKinsta dashboard



我们还提供了额外的方法，您可以在我们的 [MyKinsta 分析工具](https://kinsta.com/help/mykinsta-analytics/)和 [kinsta 缓存日志](https://kinsta.com/knowledgebase/wordpress-error-log/)中分析您的缓存数据。这有助于确定是否存在可以缓存的绕过 GET 请求的缓存，或者可以消除的 POST 请求。

缓存组件堆栈(如下所示)让您可以看到每个请求的状态，是命中、绕过、未命中还是过期。您可以按过去 24 小时、7 天或 30 天过滤数据。

![Kinsta cache component stack](img/23528008f6be346c83414742247dbebd.png)

Kinsta cache component stack



高速缓存组件图表让您对高速缓存比率一目了然。从缓存中处理的请求越多越好。正如你在下面的例子中看到的，这个 WordPress 站点有 96.2%的缓存命中率。哪个好！

## 注册订阅时事通讯



### 想知道我们是怎么让流量增长超过 1000%的吗？

加入 20，000 多名获得我们每周时事通讯和内部消息的人的行列吧！

[Subscribe Now](#newsletter)

![Kinsta cache component chart](img/71db00689e082f2221f501d0347891d8.png)

Kinsta cache component chart



“顶级高速缓存旁路”部分使您可以看到哪些请求没有得到高速缓存的服务。通常这些可能包括 CRON 作业、admin-ajax 请求、电子商务结账页面、查询字符串和 UTM 参数等。

![WordPress top cache bypasses](img/7f0f5c5b176be31a1c473d2f40c66d9f.png)

WordPress top cache bypasses



### 5.暂存环境并不神奇地存在

暂存环境提供了一种简单无风险的方式来测试更新(插件、WordPress 核心、主题)、[调试代码](https://kinsta.com/blog/wordpress-debug/)，并在不影响生产站点的情况下进行开发工作。如今，我们许多人都认为集结地是理所当然的。但是想象一下如果你没有呢？你会怎么做？

如果您在管理自己的服务器，您需要实现自己的解决方案。如果你使用的是 VPS 提供商，如数字海洋(T1)或 T2(T3)，你可以克隆你的机器，但这不是一个快速的解决方案，也不是免费的。

如果你想要一个更专注于 WordPress 的解决方案，有一些不错的，如 [WP Stagecoach](https://wpstagecoach.com) (每年 120 美元起)和 [ManageWP](https://managewp.com/) (每个网站每月 2 美元起)，但这些都不是免费的。

如果你比较管理你自己的服务器和托管 WordPress 主机的价格，记住这一点很重要。

#### Kinsta 提供一键分期付款

在 Kinsta，每个站点都有自己的[暂存环境](https://kinsta.com/help/staging-environment/)。您所要做的就是单击“创建一个暂存环境”,然后您就可以立即获得生产站点的副本。这使得测试变得非常容易。

![Create WordPress staging environment](img/c25f5f9443fd65ede4013fcc3ee8262f.png)

Create staging environment



如果一个暂存设置不够，Kinsta 客户还可以选择添加多达五个[高级暂存环境](https://kinsta.com/help/premium-staging-environments/)。

完成后，只需按一个按钮，您就可以将更改推回到 live。您甚至可以将生产站点的备份恢复到暂存状态。

为了给您尽可能多的空间，在计算您的总磁盘空间使用量时，我们的报告中不包括中转站点。只有实时网站计入您的磁盘空间使用。

### 6.不要忘记监控

你最不希望看到的就是你的网站在周五凌晨 2 点关闭，直到周一早上你才意识到这一点。这适用于您的服务器和您的站点，因为每个站点都可能有自己的问题，这些问题可能会使它们脱机。

网站宕机会给你带来很多不同的影响。

1.  你的收入会受到影响。
2.  这对你的品牌和信誉不好。
3.  根据停机时间的长短，你的抓取率和搜索排名可能会受到影响。

因此，你必须 24/7/365 全天候监控你的服务器和站点，以确保一切正常顺利运行。如果您管理自己的服务器，这意味着您需要运行时间监控解决方案来提醒您。

![Updown](img/c86b4c77ad93f3b964bb54553a48b09a.png)

Updown



虽然 VPS 提供商如 Digital Ocean 和 Linode 提供服务器监控解决方案，但他们不为你的 WordPress 站点提供。根据您拥有的网站数量和您需要的提醒类型，您很可能需要为单独的服务付费。以下是一些比较流行的解决方案:

*   [updown.io](https://updown.io/)
*   [downnotifier.com](https://www.downnotifier.com/)
*   [正常运行时间](https://uptime.com/)
*   [Pingdom](https://www.pingdom.com/product)
*   [正常运行时间机器人](https://uptimerobot.com/)
*   [保鲜](https://www.freshworks.com/website-monitoring/)
*   [状态消失](https://www.statuscake.com/our-pricing/)
*   [管理 WP](https://managewp.com/)

#### 别担心，金斯塔会全天候支持你

如果你用 Kinsta 托管，你就不需要担心服务器端的事情。我们的系统管理团队会处理这些问题！如果有问题，您会在 MyKinsta 仪表盘上看到通知，或者您可以查看我们的[状态页面](https://status.kinsta.com/)。

关于您的站点，我们包括使用 [Kinsta APM 工具](https://kinsta.com/apm-tool/)的额外正常运行时间监控。你也可以使用新遗迹，虽然你需要有自己的许可证。我们每两分钟检查一次我们托管的所有网站的状态。也就是说**每天对你的每个网站进行 720 次检查**。

**我们采取积极主动的方法**。这意味着，如果您的网站出现故障，我们将是第一个得到通知的人，我们的工程师将会立即行动！如果需要，如果我们发现您的网站有问题，我们会联系您。这样你就不用担心经常检查或者在假期检查了。

### 7.你需要 SSL 证书

你的网站应该[运行在 HTTPS](https://kinsta.com/blog/http-to-https/) 之上。最简单和最便宜的方法是免费的加密 SSL 证书。问题是，如果您使用的是准系统或 VPS 提供商，您需要一个系统来进行安装和自动更新(让我们加密每 90 天到期的证书)。

最常见的方法可能是使用 [Certbot](https://certbot.eff.org/) 。但这需要以下内容:

Struggling with downtime and WordPress problems? Kinsta is the hosting solution designed to save you time! [Check out our features](https://kinsta.com/features/)

1.  在服务器上安装 Certbot
2.  设置 Nginx
3.  允许 HTTPS 通过防火墙
4.  从“让我们加密”获取 SSL 证书
5.  验证证书自动续订

另一种方法是使用像 ServerPilot 这样的解决方案以及您的 VPS 提供商。但这不是免费的，ServerPilot 计划起价为每月 5 美元。

#### Kinsta 有免费的一键式 SSL

Kinsta 让安装 SSL 证书变得异常简单！只需登录我们的 MyKinsta 仪表板，浏览到您的网站，并点击“生成免费的 HTTPS 证书。”很快你的网站就覆盖了 HTTPS。无需担心续约问题，我们的自动化系统会处理好一切。

转而使用自定义 SSL 证书？没问题，很容易从仪表板安装。

![One-click Free SSL](img/7ffaa023f9f8e7c9e66a9bd2b51e6e0d.png)

One-click Free SSL



经营网店？查看我们关于 WooCommerce 和 SSL 的深度指南。

### 8.你是 WordPress 性能故障排除方面的专家吗？

这是周一早上的第一件事，你的 WordPress 网站突然变慢了。从哪里开始解决性能问题？是服务器上的某个东西耗尽了所有的资源，还是 WordPress 站点本身的某个东西？有成百上千的事情会导致 WordPress 的性能问题。

如果你在运营一个电子商务或会员制网站，你一定会在某个时候遇到性能问题，因为这些类型的网站都有自己的问题。查看我们的[托管 WordPress 会员网站的注意事项](https://kinsta.com/blog/hosting-wordpress-membership-sites/)。

对性能问题进行故障诊断并找出发生了什么的最简单的方法是使用高级工具，如 [New Relic](https://kinsta.com/blog/wordpress-performance-new-relic/) (需要许可证)。有什么问题吗？这个工具在**的最低价格是 75 美元/月**。

#### Kinsta 的平台是可扩展的，我们可以帮助您查明性能问题

在 Kinsta 你不用担心服务器资源。我们利用位于谷歌云平台的多个数据中心的虚拟机。我们的每台机器都有多达 96 个 CPU 和数百千兆字节的内存。在可用区域，我们利用他们的[计算优化(C2)虚拟机](https://kinsta.com/blog/boosting-wordpress-performance/#kinstas-infrastructure-and-the-new-gcp-computeoptimized-vms-c2)。它们提供了 GCP 在计算引擎上提供的最高每核性能，并针对计算密集型工作负载进行了优化。硬件资源(RAM/CPU)由我们的虚拟机根据需要自动分配给每个站点容器。

我们利用 LXD 托管主机，并为每个站点编排 LXC 软件容器。这意味着每一个站点都位于自己的独立容器中，容器中有运行它所需的所有软件资源(Linux、Nginx、PHP、MySQL)。**资源是 100%私有的** **，并且** **不会在任何其他人甚至你自己的站点之间共享**。

MySQL 数据库托管在[本地主机](https://kinsta.com/knowledgebase/what-is-localhost/)T3，而不是远程服务器。这确保了机器之间没有延迟，从而加快了查询和页面加载速度。

这可能是一个外部服务超时，一个插件或活动主题引起的问题，或者网站数据库正在努力跟上查询的速度。无论是什么问题，我们通常可以缩小范围，并提供如何解决问题的建议。

解决性能问题或插件/主题问题是我们团队每天都要做的事情。你在金斯塔会得到很好的照顾。我们整个支持团队由 WordPress 开发者和 Linux 主机工程师组成。请放心，你将与能提供可行建议的人交谈。

记住，你可以自己潜入新遗迹，但是你必须有自己的执照。

### 9.更新软件可能很耗时

你更愿意花时间做什么，发展业务还是更新软件？当你管理自己的服务器时，你将不得不一直更新软件，检查安全补丁，并安装诸如最新的 PHP 版本之类的东西。

在大多数情况下，这必须通过命令行中的 SSH 来完成。所以准备好拿出你的`sudo apt-get update`命令吧。

#### 金斯塔总是提供最新和最伟大的

在 Kinsta 做主机，什么都不用装。从我们的服务器硬件到我们运行的软件，我们只在 Kinsta 使用最好的技术。无论您使用什么样的开发堆栈，我们都会安装最新的框架版本。

我们通常会在官方发布的几周内发布最新版本的 PHP！没错，不像我们的竞争对手，你不会等上几个月甚至几年。如果你想尽快测试，我们甚至尝试发布测试版。

为什么这如此重要？因为在我们最近的 [PHP 基准测试](https://kinsta.com/blog/php-benchmarks/)中，如果你比较 PHP 7.3 和 PHP 5.6，它每秒可以处理 3 倍的请求(事务)！ [PHP 7.3](https://kinsta.com/blog/php-7-3/) 也比 PHP 7.2 平均快 9%。PHP 的最新版本不仅可以帮助你提高网站的速度，还会影响你的 WordPress 管理仪表板的响应能力。

![WordPress 5.0 PHP benchmarks](img/aa3e50c1190462560cd448720e536908.png)

WordPress 5.0 PHP benchmarks



更快的速度加上更好的安全性，是 Kinsta 总是提供最新版本 PHP 的原因。你可以点击一下[改变 PHP 版本](https://kinsta.com/knowledgebase/how-to-update-php-in-wordpress/)。

![Change to PHP 7.4](img/41430c235a34e9967240ff6124e067ef.png)

Change to PHP 7.4



### 10.你必须花时间寻找答案

不管你在管理服务器方面有多好，在某些时候你不可避免地会遇到问题，你必须花时间去寻找答案。无论是浏览 StackOverflow 还是询问同事，这可能都不是很好地利用你的时间。

我们不断有客户将他们的 WordPress 网站迁移到 Kinsta，因为他们很难用他们的 VPS 调试停机时间。

![sysadmin comic](img/a4eb7fc82ed8f76d0a8c9d40b76e7418.png)

Sysadmin comic (Image source: [The Underfold](https://theunderfold.com/2017/06/19/server-maintenance/), by Brian Russell)



#### 节省您的时间，使用金斯塔的 24/7 世界一流的支持

不要依赖谷歌来找到你的答案，利用 Kinsta 的专家支持团队，即使在新年前夕，也只需点击一下鼠标。

![Kinsta 24x7 support](img/f3d1a087f7ff074ca6e799f208111330.png)

Kinsta 24/7 support



**我们彻底改变了支持的工作方式！**我们没有 1 级或 2 级支持代表。我们的整个支持团队由 WordPress 开发人员和 Linux 主机工程师组成，他们中的许多人管理自己的服务器，创建主题和插件，并为 core 做出贡献。这可以确保你从积极使用和开发 WordPress 的人那里得到专家的建议。

> 通过 [@kinsta](https://twitter.com/kinsta?ref_src=twsrc%5Etfw) 托管我的网站让我无比开心。我感觉他们的后援团从来不睡觉！惊人的服务。
> 
> —马修·豪威尔斯-巴比ξmhb . eth(@ matthewbarby)[2017 年 7 月 3 日](https://twitter.com/matthewbarby/status/881991533934911489?ref_src=twsrc%5Etfw)