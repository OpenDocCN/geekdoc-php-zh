# 如何解决 WordPress 不发送电子邮件的问题(关于如何用最常用的联系表单插件解决这个问题的提示)

> 原文：<https://kinsta.com/blog/wordpress-not-sending-email/>

网站所有者的一个普遍问题是 WordPress 不能正确发送邮件或者根本不发送邮件。

包括 Kinsta 在内的大多数 WordPress 托管服务提供商都不提供电子邮件托管服务。然而，这并不意味着你不能用你的 WordPress 系统发送邮件。在 Kinsta，所有网站都配备了[交易电子邮件支持](https://kinsta.com/help/transactional-email/)，这意味着你的 WordPress 网站将能够发送通知、WooCommerce 订单确认和其他类型的网站相关电子邮件。

通常，当你试图解决 WordPress 不发送电子邮件的问题时，这不是服务器的问题，而是 WordPress 安装上的电子邮件设置不正确或者存在不兼容。

在这篇文章中，我们将向你展示如何识别为什么 WordPress 不向你或你的用户发送邮件，并向你展示如何修复它。无论你运行的是一个普通的 WordPress 网站还是一个 WooCommerce 商店，我们都将向你展示如何让电子邮件重新运行起来。

我们还将看看一些最流行的联系表单插件，并确定为什么它们中的每一个都有发送电子邮件的问题。

### 更喜欢看[视频版](https://www.youtube.com/watch?v=-SsVKWWwqFw)？



## 为什么 WordPress 不发送电子邮件

WordPress 不发送电子邮件可能有几个原因。其中包括:





> Kinsta 把我宠坏了，所以我现在要求每个供应商都提供这样的服务。我们还试图通过我们的 SaaS 工具支持达到这一水平。
> 
> <footer class="wp-block-kinsta-client-quote__footer">
> 
> ![](img/60f15faa5735bd2437bf9dada5ee9192.png)
> 
> <cite class="wp-block-kinsta-client-quote__cite">Suganthan Mohanadasan from @Suganthanmn</cite></footer>

[View plans](https://kinsta.com/plans/)

 让我们来看看如何识别这些问题中的哪一个可能导致了问题。

### 1.电子邮件正在发送，但会变成垃圾邮件

在运行任何其他测试之前，确保来自 WordPress [的电子邮件不是垃圾邮件](https://kinsta.com/blog/email-authentication/)。

如果一个用户向你报告说 WordPress 没有发送邮件，很可能只是他们的邮件变成了垃圾邮件。

让他们检查垃圾邮件文件夹中来自系统的电子邮件。一些电子邮件客户端可能会将来自 WordPress 的邮件识别为垃圾邮件，因为它们是自动生成的。

### 2.您的服务器配置不正确

WordPress 不发送邮件的一个常见原因是你的服务器没有配置为发送邮件。

网络服务器不是为发送电子邮件而设计的，可能你的服务器没有配置使用`PHP mail()`功能。

好消息是，您可以很容易地检查这是否是导致问题的原因，并且您可以修复它。


#### 如何测试服务器是否正在发送电子邮件

你可以做的第一件事是用免费的[检查邮件](https://wordpress.org/plugins/check-email/)插件在你的 WordPress 网站上运行一个测试。

这是一个基本插件，用来测试你的 WordPress 安装和/或服务器是否可以发送电子邮件。

安装完成后，在你的 WordPress 仪表盘中进入**工具>查看邮件**。输入要发送测试的邮件地址，点击**发送测试邮件**。

![Send test email](img/6aa7fd275f5e478b804748c681bd2e36.png)

Send test email



然后你会看到一个确认。

![Test email confirmation](img/47ba6bc635e05962d5f2a4bf01123d15.png)

Test email confirmation



检查你的电子邮件客户端，看看你是否收到了测试邮件。主题行将显示为“来自 https://yourdomain.com 的测试电子邮件”

![Email test received](img/1f90aa37e9d996f48102d78311303d60.png)

Email test received



此外，请确保检查您的垃圾邮件或垃圾邮件文件夹。如果你收到了一封邮件，这意味着 WordPress 可以在你的网络服务器上发送邮件。

如果你仍然没有收到邮件，这意味着很可能是你的联系方式插件配置错误或者不兼容。你可以随时向插件开发者寻求帮助。让他们知道你已经运行了上面的测试，并且电子邮件正在你的 WordPress 安装上运行。或者按照下面的步骤使用一些最极端的接触式插件。

如果你是 Kinsta 的客户，并且使用 [HHVM](https://kinsta.com/blog/hhvm-wordpress/) ，你可以暂时切换到 PHP 7 来测试是否有兼容性问题。你可以在你的 [MyKinsta 仪表板](https://kinsta.com/MyKinsta/)中轻松地[切换到 PHP 7](https://kinsta.com/knowledgebase/how-to-update-php-in-wordpress/) 。测试后，您可以切换回 HHVM。

对于 Kinsta 客户和使用其他主机的客户，如果您有连接问题，您可能还需要尝试其他端口。您的主机可能阻塞了端口。

Kinsta 使用谷歌云平台，默认情况下[会阻止端口 25 上的出站连接](https://cloud.google.com/compute/docs/tutorials/sending-mail/)。根据谷歌的说法，“这个出站 SMTP 端口被阻止是因为这个端口容易被大量滥用。”在这种情况下，[尝试一个备用的](https://kinsta.com/blog/smtp-port/) [端口比如 2525](https://kinsta.com/blog/smtp-port/) 。587 和 465 端口在 Kinsta 开放。

### 3.您的联系人表单插件正在发送“欺骗”电子邮件

如果你已经运行了上面的测试，并且你的服务器被配置为发送电子邮件，那么这意味着从你的 WordPress 站点发送电子邮件的插件有问题。

很有可能这将是一个[联系表单插件](https://kinsta.com/blog/wordpress-contact-form-plugins/)。

联系人表单插件发送的电子邮件有时会被电子邮件客户端识别为欺骗电子邮件。这些类似于垃圾邮件:电子邮件客户端会将其标记为可疑。

联系表单电子邮件区域有时被视为欺骗的原因是，它们是从不同的地址发送的，而不是添加到您收到的电子邮件中的 **From:** 字段的地址。

因此，如果你已经配置了你的联系表单，用填写表单的人的电子邮件地址来填充 **From:** 字段，但是该电子邮件实际上是来自你的 WordPress 站点，那么你的电子邮件客户端将会怀疑该电子邮件，并可能将其标记为欺骗。

如果电子邮件是从同一个电子邮件地址发送的，你也可能会遇到问题。因此，如果你的表单插件从你的管理员邮箱地址发送邮件，并且你也配置了发送邮件到那个地址，一些邮件提供商可能不喜欢。与“欺骗”电子邮件问题相比，这不太可能是一个问题。

对于联系人表单，通知电子邮件的收件人通常是您。这意味着你可以改变你的联系方式插件的设置来解决这个问题，你可以很容易地测试电子邮件是否被接收。

#### 受影响的联系人表单插件

任何联系人表单插件都会受到这个问题的影响。以下是一些你可能会遇到这个问题的插件:

*   [联系方式 7](https://kinsta.com/blog/contact-form-7/)
*   重力形式
*   忍者形态
*   开心农场
*   网络表单
*   Jetpack 联系表单
*   可怕的形式

我将很快向你展示如何解决每个联系表单的电子邮件无法发送的问题。首先，让我们看看你是如何解决 WordPress 对于我们已经确定的每一个原因都不发送邮件的问题的。

[WordPress 是不是不发你的邮件了？😱在这里了解为什么会发生这种情况以及如何修复⬇ 点击发布推文](https://twitter.com/intent/tweet?url=https%3A%2F%2Fkinsta.com%2Fblog%2Fwordpress-not-sending-email%2F&via=kinsta&text=Is+WordPress+not+sending+your+emails%3F+%F0%9F%98%B1++Learn+why+it%27s+happening+and+how+to+fix+it+right+here+%E2%AC%87&hashtags=Email%2CWPTips)


## 如何阻止 WordPress 邮件变成垃圾邮件

### 1.将电子邮件地址列入白名单

如果[电子邮件要发送垃圾邮件](https://kinsta.com/blog/why-are-my-emails-going-to-spam/)，你可以通过将你的电子邮件地址添加到他们的联系人中，让你的用户将你的电子邮件加入白名单。

在 [Gmail](https://kinsta.com/blog/gmail-add-ons/) 中，如果他们将电子邮件转移到[收件箱](https://kinsta.com/blog/gmail-search-operators/)，这应该意味着将来来自该地址的电子邮件不会被转移到垃圾邮件中——但是将该地址添加到联系人中也将是最安全的。

### 2.使用更安全的电子邮件地址

您可能还想查看您的网站发送电子邮件的电子邮件地址。默认情况下，这将是您的管理员电子邮件地址。如果这是[【受电子邮件保护】](/cdn-cgi/l/email-protection)[【受电子邮件保护】](/cdn-cgi/l/email-protection)[【受电子邮件保护】](/cdn-cgi/l/email-protection)或类似的东西，那么电子邮件提供商可能会认为这是垃圾邮件。

尝试将[电子邮件地址改为看起来更专业的](https://kinsta.com/blog/professional-email-address/)，并确保发送到该地址的任何电子邮件都被转移到您的正常地址，这样您就不会错过任何回复。为此，您可以为您的电子邮件地址创建一个别名。

### 3.设置电子邮件认证

你的 WordPress 邮件可能会变成垃圾邮件的另一个原因是因为你的域名没有被正确的认证。

遵循我们的指南[电子邮件认证](https://kinsta.com/blog/email-authentication/)以确保你有它正常工作。

## 注册订阅时事通讯



### 想知道我们是怎么让流量增长超过 1000%的吗？

加入 20，000 多名获得我们每周时事通讯和内部消息的人的行列吧！

[Subscribe Now](#newsletter)

## 如何在 WordPress 中设置 SMTP 发送邮件

如果您已经运行了上述电子邮件测试，但电子邮件根本没有从您的网站发送，那么您需要使用第三方 SMTP 提供商，并将其与您的网站链接，以便它可以再次发送电子邮件。

SMTP 代表简单邮件传输协议。它在网络上或跨网络传送电子邮件。因此，如果你的服务器没有配置发送电子邮件，这将使它成为可能。

有许多 SMTP 提供商可供选择，包括一个免费的选择(如 [Gmail SMTP 服务器](https://kinsta.com/blog/gmail-smtp-server/)):所以这不需要花费你任何钱，只需要一点点时间。

要设置这个，请按照我们的指南使用免费的 SMTP 服务器和 WordPress 。

## 如何配置您的表单插件以正确发送电子邮件

如果您的服务器被配置为发送电子邮件，但您仍然无法发送表单条目，这可能意味着您需要调整表单的设置。

让我们来看看你应该为每个最流行的表单插件做些什么来让那些邮件再次发送。

对于其中的每一个，我假设你已经尝试在你的网站上添加 SMTP，或者你的服务器已经在发送电子邮件了(并且你已经检查了垃圾邮件文件夹)，但是电子邮件仍然没有通过。

### 修正联系人表格 7 不发送电子邮件

联系表单 7 是最古老和最流行的免费 WordPress 表单插件之一。

如果你发送电子邮件有问题(你知道你的服务器正在发送电子邮件)，解决方法是改变发送电子邮件的地址。

在你的 WordPress admin 中，进入**联系人>联系表格**。

![Contact forms](img/dc2555702339f5a38e2d82c1a0cad4e0.png)

Contact forms



选择您创建的表单并打开**邮件**标签。

![Email tab in contact forms](img/d1b2d37b065db9f11206f2944645bc11.png)

Email tab in contact forms



确保 **From** 字段有您站点的管理员电子邮件地址，而不是表单中输入的电子邮件地址。您可以在**回复**字段中使用，但不能在字段中使用**。**

避免对从到**和从**到**字段使用相同的电子邮件地址。请使用与您的网站不同的电子邮件地址。**

保存您的更改。

现在，通过自己完成表格来测试一些东西。

### 修正重力形态不发邮件

Gravity Forms 是最流行和最受推崇的高级表单插件之一。与使用 Contact Form 7 相比，你不太可能遇到不是通过这个插件发送的电子邮件的问题，但如果真的发生了。你会在[插件文档](https://docs.gravityforms.com/troubleshooting-notifications/)中找到详细的指导。

需要一个给你带来竞争优势的托管解决方案吗？Kinsta 为您提供了令人难以置信的速度、一流的安全性和自动伸缩功能。[查看我们的计划](https://kinsta.com/plans/?in-article-cta)

![Gravity forms documentation](img/341f36fc43909c99a644de0958d753c4.png)

Gravity forms documentation



按顺序完成文档中的选项，直到一切恢复正常。

### 修正忍者形态不发送电子邮件

[忍者形态](https://kinsta.com/blog/wordpress-contact-form-plugins/#ninja-forms)有免费版和高级版。还有很多 ti 的附加插件，你可以从 WordPress 资源库免费下载。

如果你遇到了与 Ninja 表单的电子邮件相关的问题，推荐的解决方案是使用由同一个团队开发的 [SendWP](https://sendwp.com/) 插件。

![SendWP](img/6f9e9233c5c35b8bedc5c1eddce56868.png)

SendWP



SendWP 旨在让 SMTP 在你的服务器上工作——你也可以使用免费插件来实现。如果问题不在于你的服务器没有发送电子邮件，SendWP 不会修复它。

因此，如果你不想每月为 SendWP 支付 9 美元，试着遵循他们文档中的[电子邮件故障排除](https://ninjaforms.com/blog/troubleshooting-ninja-forms-email-part1/)指南。

### 修复不发送电子邮件的快乐表单

HappyForms 是另一个有免费和高级版本的插件。

![Happyforms](img/a0ebea700f4a2d9d70487904afb21261.png)

Happyforms



HappyForms 有一个[帮助指南](https://happyforms.me/help-guide),但是它没有详细说明如果它的电子邮件没有发送该怎么做。

要更改发送快乐表单的电子邮件地址，您可以编辑单个表单的电子邮件设置，方法与联系表单 7 类似。

转到**快乐表单>所有表单**并选择您想要编辑的表单。这将打开一个类似定制器的界面。

打开**电子邮件**标签。

![Happyforms email tab](img/56ad127a85d2ae46fbb7af70568300e1.png)

Happyforms email tab



在这里，你可以定制通知和确认的**到**和**发件人**地址，以确保你没有发送欺骗邮件。

一旦你完成了修改，点击顶部的**更新**按钮并测试你的表单。

### 修复 webforms 不发送电子邮件

weForms 是另一个表单插件，有免费版和高级版。它可以让你配置插件来使用一系列电子邮件提供商的邮件，包括 WordPress 本身、 [SendGrid](https://kinsta.com/blog/free-smtp-server/#sendgrid) 或其他。

它有一个[故障排除指南](https://weformspro.com/docs/tutorials/how-to-fix-weforms-not-sending-email/)来帮助你解决 weForms 不发送邮件的问题。遵循指南，找出问题的根源，让您的电子邮件再次工作。

### 修正了 Jetpack 联系人表单不发送电子邮件的问题

如果你运行的是 [Jetpack 插件](https://kinsta.com/knowledgebase/wordpress-jetpack/)，你可能会使用它附带的基本联系方式。你可以通过在 WordPress 的页面或文章中添加一个表单块来实现。

Jetpack 没有专用表单插件那么多的配置选项，但是您可以更改电子邮件的接收地址。

因为 Jetpack 不使用电子邮件的**至**或**自**字段中的表单字段，所以您不太可能遇到与电子邮件相关的问题。如果你真的遇到了问题，那是因为你用同一个地址发邮件。

一旦你添加了表单，点击它上面的编辑图标，就会出现一个下拉菜单。使用此选项可更改表单的接收地址。

![Jetpack contact form](img/162b84cc22c1079ff37a8f62d0d77d59.png)

Jetpack contact form



如果你想更改发送表单的地址，你必须更改网站的管理员电子邮件地址，因为这是 Jetpack 表单使用的地址。

### 修正不发送电子邮件的可怕形式

强大的表单是另一个表单插件，有免费和高级版本。如果你在用令人生畏的表格从你的联系人表格发送电子邮件时遇到问题，[官方文档](https://formidableforms.com/wordpress-not-sending-emails-smtp/)建议在你的网站上添加 SMTP。

但是如果你已经这样做了，但事情仍然不工作呢？嗯，这很可能是因为你的电子邮件被标记为“欺骗”电子邮件，因为它们是从一个地址发出的，而不是真正的发送地址。

在 WordPress admin 中，进入**强大的>表单**，然后选择你想要编辑的表单。点击顶部的**设置**选项卡，然后点击侧面的**动作&通知**选项卡。从这里，打开**电子邮件通知**元框。

![Formidable forms email notification settings](img/2881c3f1339c6558fdc4c11d732d4ebe.png)

Formidable forms email notification settings



您可以在此编辑通知电子邮件的发送地址和接收地址。默认情况下，它将使用两者的管理员电子邮件地址，而不是取自表单的电子邮件地址。

要更改电子邮件的接收地址(这样就不是发送地址)，编辑**到**字段，手动输入您想要使用的电子邮件地址。

设置屏幕会保存您所做的更改，因此请确保您输入的内容是正确的。

[If your emails aren't sending through WordPress, these common issues could be at the root of the problem...👀Click to Tweet](https://twitter.com/intent/tweet?url=https%3A%2F%2Fkinsta.com%2Fblog%2Fwordpress-not-sending-email%2F&via=kinsta&text=If+your+emails+aren%27t+sending+through+WordPress%2C+these+common+issues+could+be+at+the+root+of+the+problem...%F0%9F%91%80&hashtags=EmailTips%2CWordPress)

## 摘要

有时候 WordPress 不发送邮件，你可能很难找到原因。这个问题是最常见的 WordPress 错误之一，可能是因为电子邮件会变成垃圾邮件，因为你的服务器没有配置为发送电子邮件，或者因为你的联系人表单中的设置需要更改。

按照上面的指导来诊断你的 WordPress 站点不发送邮件的原因并解决问题。你应该很快就能正常使用电子邮件了！

* * *

让你所有的[应用程序](https://kinsta.com/application-hosting/)、[数据库](https://kinsta.com/database-hosting/)和 [WordPress 网站](https://kinsta.com/wordpress-hosting/)在线并在一个屋檐下。我们功能丰富的高性能云平台包括:

*   在 MyKinsta 仪表盘中轻松设置和管理
*   24/7 专家支持
*   最好的谷歌云平台硬件和网络，由 Kubernetes 提供最大的可扩展性
*   面向速度和安全性的企业级 Cloudflare 集成
*   全球受众覆盖全球多达 35 个数据中心和 275 多个 pop

在第一个月使用托管的[应用程序或托管](https://kinsta.com/application-hosting/)的[数据库，您可以享受 20 美元的优惠，亲自测试一下。探索我们的](https://kinsta.com/database-hosting/)[计划](https://kinsta.com/plans/)或[与销售人员交谈](https://kinsta.com/contact-us/)以找到最适合您的方式。