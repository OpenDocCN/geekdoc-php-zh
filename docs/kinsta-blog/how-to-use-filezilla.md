# 如何像专业人士一样使用 FileZilla(并解决错误)

> 原文：<https://kinsta.com/blog/how-to-use-filezilla/>

作为使用最广泛的 FTP 客户端之一，FileZilla 是通过互联网在计算机之间传输文件的常用解决方案。FileZilla 通过链接客户机和服务器来实现这种传输功能，这样用户就可以在客户机和服务器之间来回发送文件。

尽管有许多其他 FTP 客户端(具有更现代的界面)可供选择，但 FileZilla 仍然很受欢迎，因为它可靠、易于使用且速度快。简而言之，作为初学者，很容易开始使用 FileZilla，有经验的用户将这个 FTP 客户端视为可靠的伙伴，总能完成工作。
[作为使用最广泛的 FTP 客户端之一，FileZilla 是通过互联网在计算机之间传输文件的常用解决方案。👨‍💻在本指南中了解更多信息！🚀 点击推文](https://twitter.com/intent/tweet?url=https%3A%2F%2Fkinsta.com%2Fblog%2Fhow-to-use-filezilla%2F&via=kinsta&text=As+one+of+the+most+widely+used+FTP+clients%2C+FileZilla+serves+as+a+common+go-to+solution+for+transferring+files+between+computers+over+the+internet.+%F0%9F%91%A8%E2%80%8D%F0%9F%92%BB+Learn+more+in+this+guide%21+%F0%9F%9A%80&hashtags=FTP%2CSSL)
在本文中，我们将讨论如何使用 FileZilla 将文件上传到您的网站，并访问网站文件以进行进一步管理。

## FileZilla 是什么？

FileZilla 是一个 FTP(文件传输协议)程序或“客户端”,允许用户通过互联网在计算机之间移动文件。这意味着人们使用 FileZilla 来完成几项任务，例如:

*   上传文件
*   下载文件
*   复制文件
*   移动文件
*   重命名文件
*   删除文件

FileZilla 提供多平台支持，可以在几乎所有类型的计算机上共享文件。您可以在 Mac、Windows 和 Linux 电脑上安装它。


## 为什么应该使用 FileZilla？

第一个问题是为什么首先需要使用 FileZilla 进行 FTP？









以下是主要原因:

*   **为了保护您的内容:**用户经常需要移动包含敏感信息的数据或需要在没有任何入侵者的情况下可靠交付的文件。标准的 FTP 是不加密的，但是有其他的协议，像 FTPS 和 SFTP(FileZilla 都支持)会加密数据以保护传输中的数据。
*   **对于灾难恢复:**网站文件，无论多么安全，都有可能被破坏、删除，并引发一系列其他问题。因此，明智的做法是使用 FileZilla 将站点文件的[备份转移到其他位置，比如](https://kinsta.com/help/external-backups/)[云存储](https://kinsta.com/knowledgebase/wordpress-google-cloud-storage/)或你自己的电脑。如果出现问题，您可以重新上传损坏或丢失的文件。
*   **移动大文件:**使用电子邮件、云存储工具和其他文件共享软件，你会经常遇到[文件大小发送限制](https://kinsta.com/blog/gmail-attachment-size-limit/)。用户经常需要一次发送大量文件，而不是压缩文件或将它们分成更小的文件。像 FileZilla 这样的 FTP 程序支持为这些组织移动大文件，例如，如果您正在发送或接收大容量的视频文件或一组原始图像。**为了更好地控制文件:** FileZilla 提供用户权限和访问控制，以确定谁可以通过系统共享、编辑、上传和下载文件。
*   **改善您的整体工作流程:** FileZilla 不仅允许组织发送大文件，还允许他们同时运行其他传输，从而提高了组织的效率。这意味着你可以继续工作在另一个上传或下载，而不是坐在那里等待每个进程。另外，FTP 为组织内部的文件共享提供了一个统一的标准，而不是让每个人自己选择数据共享的方式(大部分效果会差一些)。最后，所有这些文件最终都存储在一个位置，帮助您快速找到文件并最大限度地减少数据丢失。

### 相比其他 FTP 客户端，您应该考虑 FileZilla 的 10 个理由

尽管有几个很好的选择，我们还是倾向于 FileZilla，原因如下:

1.  **可访问:** FileZilla 提供了一个所有用户都非常熟悉的直观界面，并且在大多数主流操作系统上都受支持。因此，你应该不会有任何问题，你也不必担心它是否与你的操作系统兼容。
2.  **有据可查:**FileZilla 网站和整个互联网都充斥着如何使用 FileZilla、如何适应它以及如何利用它的许多特性的教程。这对于初学者和需要特性参考的高级用户来说都是非常理想的。还有一个[论坛可以和其他 FileZilla 用户聊天](https://forum.filezilla-project.org/)。
3.  **扎实快速:** FileZilla 以可靠性和速度著称。这是您希望从 FTP 客户端获得的两个主要优势，尤其是在传输站点文件、敏感数据或大文件时。
4.  **多种传输协议:**支持多种传输文件的协议，有 FTP、SFTP (SSH 文件传输协议)、FTP over SSL/TLS (FTPS)等选项。
5.  **多语言:**该软件有多种语言版本。
6.  **搜索功能:**有一个远程文件搜索功能，可以快速找到文件。根据权限，您还可以从远程位置编辑这些文件。
7.  **易于使用:**它提供了一个可以快速移动文件的拖放界面，以及指示文件已成功传输的视觉指示器。
8.  **不限文件大小:**可以发送大文件。从技术上讲，FileZilla 对文件大小没有限制。然而，你可能有你的托管公司的限制。
9.  **导航简单:**选项卡式用户界面和书签便于导航和查找功能和文件。
10.  免费:它是开源的，完全免费(除非你选择升级到 Pro 版本)。

总的来说，学习如何使用 FileZilla 来共享大文件，更有效地管理文件，以及从更广泛的角度来看，管理您的网站是很有价值的。即使是非技术网站所有者也应该学会如何接入 FileZilla FTP 来替换损坏或丢失的文件。批量访问你的文件可能意味着普通的一天和失去许多销售的区别。

关于如何使用 FileZilla 的一般知识也将您的工作流程和公司安全带入一个更好的位置。没有理由在未加密的电子邮件中发送大型或敏感文件，所有企业都应该利用安全、快速、统一的文件存储和发送系统来提高工作效率。

然而，许多网站所有者和开发者认为 FTP 是一种过时的技术，尤其是如果他们使用的是带 GUI(图形用户界面)的 web 主机。我们鼓励这些人继续学习如何使用 FileZilla FTP，因为只使用 GUI 会让他们完全依赖他们的托管公司。如果您的站点宕机时，您无法从 GUI 访问您的文件，该怎么办？如果该主机没有备份，或者您发现备份无法正常工作，该怎么办？

FTP 给了你完全的控制权，这就是你想要的基本文件。

## 如何安装和使用 FileZilla 的分步指南

安装 FileZilla 类似于在你的 Windows、Mac 或 Linux 电脑上下载和安装任何软件:你点击**下载**按钮，将安装文件保存到你的硬盘上，然后运行该文件进行安装。

让我们来看看如何安装 FileZilla。

首先，打开网页浏览器，访问官方 [FileZilla 网站(filezilla-project.org)](https://filezilla-project.org/)。这个主页提供了两个明显的**下载**按钮供你选择。选择显示**下载 FileZilla 客户端**的选项(不是**服务器**选项)。

![To kickstart the installation process, click the Download FileZilla Client button.](img/e4dc5aec27001a63e8e84953303ecbca.png)

To kickstart the installation process, click the **Download FileZilla Client** button.



默认情况下，您的浏览器和 FileZilla 网站会检测您的电脑上使用的是哪种操作系统。

![download filezilla button](img/efbb969a74cc018b7c8df48510bafa07.png)

Choose the **Download** button for your operating system.



如果您没有看到适合您的操作系统的正确版本，或者如果您更愿意下载旧版本的 FileZilla，您可以查看大的**下载**按钮下面的其他下载选项。

小图标代表主要的操作系统，显示以下版本的 FileZilla:

*   Windows 64 位
*   Windows 32 位
*   Linux 64 位
*   Linux 64 位

您也可以选择**Show Additional Download Options**链接来查看 FileZilla 的其他不常用版本。

![You can view FileZilla versions for other platforms.](img/3f9565b41815e9e2906951446187ef14.png)

You can view FileZilla versions for other platforms.



您可以查看其他平台的 FileZilla 版本。

您也可以选择**Show Additional Download Options**链接来查看 FileZilla 的其他不常用版本。

![A page with all FileZilla versions and their Download links.](img/751b65e9218fc6e437650312a93de376.png)

A page with all FileZilla versions and their Download links.



点击您选择的**下载**按钮后，会出现一个弹出窗口，要求您决定下载哪个 FileZilla 包。您可以简单地下载没有任何文档的 FileZilla，或者您可以选择接收包含下载文件的全面的 PDF 手册。

这里的另一个选择是下载 FileZilla Pro，它包括各种各样的其他功能(主要用于链接到云存储服务)。我们将在本文后面的章节中介绍 FileZilla Pro。目前，标准的 FileZilla 程序是您所需要的。

因此，点击标题为 **FileZilla** 栏下的下载按钮或标题为 **FileZilla with Manual** 的按钮。

![Choose to download FileZilla by itself or with a manual.](img/eb372dcb4325391999ccf44a46196276.png)

Choose to download FileZilla by itself or with a manual.



将该文件保存在计算机上一个容易记住的地方，然后转到该位置并单击程序文件以完成安装。所有的操作系统都是不同的，所以你可以让**运行**文件，只需点击它，或者选择一个**安装**选项。

![Open or Run the program file once it's on your machine.](img/27776fc5927851398bf7de48e5b94e77.png)

Open or Run the program file once it’s on your machine.



一旦激活并安装到您的计算机上，找到并单击 FileZilla 徽标快捷方式来运行该程序。您可以将它移动到更合适的位置，以便自己可以访问。

![The FileZilla program shortcut.](img/87ddaaf99e12be0cda36cc3ddc051f04.png)

The FileZilla program shortcut.



FileZilla 现在在您的计算机上打开，在客户端软件前面有一个欢迎弹出窗口。

如您所见，在使用 FileZilla 的过程中，有几个链接可供您查找帮助。例如，有提问和报告错误的链接，以及基本使用说明、配置 FileZilla 和您的网络以及更多文档的文档链接。

要移除弹出窗口，点击**确定**按钮。

![Check out FileZilla's support documents or proceed to the program by clicking OK.](img/7176bfc6df1b9ffb99102d62c4c91bba.png)

Check out FileZilla’s support documents or proceed to the program by clicking OK.



现在，您应该可以看到 FileZilla 的标准主屏幕，其中有用于输入主机凭证(以连接到您的网站服务器)的字段，底部有关于文件传输的信息，等等。

以下是您看到的一瞥:

*   位于左侧的**本地站点**部分显示了您在本地机器(您的计算机)上的文件。
*   上半部分显示文件目录，并允许您浏览计算机上的所有文件。
*   下半部分显示计算机上文件夹中的文件。

在接下来的小节中，您将学习如何连接您的主机服务器(如 Kinsta)，如何在右侧面板上从该服务器调出文件，以及如何使用 FileZilla 中的拖放工具从本地计算机或远程服务器传输文件。

![The view of your local files in FileZilla.](img/b67ee7d66a642eed58fdf6f92c047073.png)

The view of your local files in FileZilla.



请记住，根据您当前的权限和操作系统，您可能必须允许访问您的本地文件。

![Allow access for FileZilla to use your local folders.](img/9bc5b9ab16f1dd5151a330787a173138.png)

Allow access for FileZilla to use your local folders.



## 如何将主机凭证添加到 FileZilla 并连接到您的站点

FileZilla 的首要任务是在本地计算机和网站的远程服务器文件之间建立链接。这个过程不会以任何方式合并这两者，而是在它们之间打开一个共享文件的连接。

### 使用 FileZilla 快速连接工具

打开从电脑到服务器的共享的最简单方法是在 FileZilla 窗口顶部的几个输入栏中添加主机凭证。

这被称为 **Quickconnect** 部分，因为它提供了一种从主屏幕键入主机服务器凭证的方式。然而，它默认为 FTP 连接，所以如果需要一个 [SFTP 连接](https://kinsta.com/knowledgebase/how-to-use-sftp/)或其他类型的协议，您可能会看到一个错误。

无论如何，首先尝试一下**快速连接**字段来看看它是否对你有用是值得的。

以下是您需要填写的字段:

*   主持
*   用户名
*   密码
*   港口

![The Quickconnect panel asks you for Host login credentials.](img/6438c052c80a7b295cfacd8f3e23de76.png)

The Quickconnect panel asks you for Host login credentials.



那么，从哪里开始寻找输入这些字段的凭证呢？

通常情况下，你需要进入你的[主机仪表板或 cPanel](https://kinsta.com/blog/cpanel-alternatives/) 来定位你网站服务器的唯一主机凭证。有时你可能需要联系你的主机或网站开发者来找出正确的登录信息。

对于 Kinsta 客户，这些凭证方便地显示在 [MyKinsta 仪表板](https://kinsta.com/mykinsta)中。只需导航到 MyKinsta，登录您的帐户，并点击菜单中的**网站**按钮。然后点击您试图查找服务器登录凭证的站点。

![In MyKinsta, click on Sites, then choose the site you want to connect to.](img/7dd80091a9d7e50dbe88b63d36e1d72e.png)

In MyKinsta, click on Sites, then choose the site you want to connect to.



选择**信息**选项卡(默认情况下应该已经选中)并滚动到 **SFTP/SSH** 部分。

![Go to Info > SFTP/SSH in MyKinsta.](img/bae05c76e9abac21024d81ec4a988ba8.png)

Go to Info > SFTP/SSH in MyKinsta.



Kinsta 为**主机**、**用户名**、**密码**和**端口**提供字段。这些是我们在 FileZilla **Quickconnect** 区域看到的完全相同的字段，让您对所需的一切一目了然:

![Copy the credentials from MyKinsta to FileZilla.](img/840e75c037115948e11eda313a2c5380.png)

Copy the credentials from MyKinsta to FileZilla.



将每个文件复制到各自的 FileZilla 字段。完成后，点击 **Quickconnect** 按钮开始本地计算机文件和远程服务器文件之间的链接。

![Click Quickconnect once you have typed in the credentials.](img/c6fb47e4cc13514be069e608d867a175.png)

Click Quickconnect once you have typed in the credentials.



您可能会看到一条信息，询问您是否希望 FileZilla 将来记住密码。然而，将这些凭证直接保存在 FileZilla 中会被认为是一种安全风险，所以我们建议使用一个[密码管理器](https://kinsta.com/blog/password-managers/)来存储这些敏感的细节。

或者，您可以选择在 FileZilla 中创建一个主密码，以防止入侵者使用保存的密码。但问题是，你必须记住或安全地存储你的主密码，因为你以后不能恢复它。

![Save a password or make a Master Password.](img/19eaf44251d4cb0a52bec1ce4c9d35dd.png)

Save a password or make a Master Password.



之后，您应该会在**消息日志**中看到一个**成功**通知。另外，所有的**远程站点**文件应该出现在**本地站点**文件右边的面板中。

![A successful connection between a local site and a remote site.](img/bb619f2f5dcb6032e4ab92c0852c3865.png)

A successful connection between a local site and a remote site.





### 信息

您的本地或远程站点上可能有一些隐藏文件。如果你找不到某个特定的文件，记得先[检查它是否被隐藏](https://kinsta.com/knowledgebase/filezilla-show-hidden-files/)。



### 协议之间的差异

FileZilla 支持以下文件传输协议:

*   **FTP(文件传输协议):**最古老的传输协议之一。它使用两个通道来移动数据，需要您使用多个端口号。这两个通道称为命令和数据通道。它们都没有加密，因此不如其他传输方式安全。人们也倾向于 FTP 的防火墙问题。
*   **FTPS(基于 SSL/TLS 的 FTP):**这是一种因互联网安全问题而产生的协议。PCI compliance 和 HIPAA 等法规最终规定，许多在线数据传输必须包括加密。FTPS 使用 SSL(安全套接字层)和 TLS(传输层安全性)来保护您的数据。数据交换与标准 FTP 完全相同(您有两个通道和两个端口号)，但在此过程中所有内容都被加密。缺点包括无法为连接创建基于密钥的身份验证，以及强大的防火墙会导致连接出现问题。
*   SFTP (SSH 文件传输协议):许多人把 FTPS 和 SFTP 搞混了，因为他们都在传输过程中保护文件。然而，除此之外，他们几乎没有什么共同之处。SFTP 使用安全外壳协议(SSH)，并通过将连接从两个减少到一个来最大限度地减少连接。这样，数据和命令在同一个连接上各自的特殊包中被移动。这也很好，因为所有通信只需要一个端口号，允许通过防火墙进行更容易的传输。最后，SFTP 使用一个密码和可选密钥(你可以公开或保密)对传输的数据进行加密。
*   **Storj:** 这是一种完全独特的传输协议，使用分散的云机器网络，不仅可以加密您的数据，还可以将数据发送到单独的块中，从而消除了将数据存储在集中式数据中心的需求。Storj 最近才作为 FileZilla 上的一个协议引入。

### 如何使用 FileZilla Site 站点管理器或其他协议

FileZilla 中的 **Quickconnect** 工具对于那些习惯使用 FTP 传输文件的人来说应该很好用。然而，一些主机(包括 Kinsta)使用 [SFTP 作为其协议](https://kinsta.com/knowledgebase/ftp-vs-sftp/)，以确保所有文件传输始终加密和安全。

由于这种配置，您可能会看到一个错误，指出**快速连接**按钮不起作用。

这些错误通常类似于**“无法建立 FTP 连接”**或**“严重错误:无法连接到服务器”**。

![Errors arise when you use the wrong protocol.](img/690ca86f964e558932588ce66e834297.png)

Errors arise when you use the wrong protocol.



你如何解决这个问题？

这相当简单，只要你知道你的主机使用的是哪种协议。由于它的安全措施，SFTP 变得更受欢迎，所以所有需要做的就是进入 FileZilla 的**站点管理器**部分，指定你想要使用 SFTP 而不是 FTP。

**站点管理器**按钮允许您配置默认协议、处理默认目录以及指定高级传输设置。它位于窗口的左上角。该图标看起来像多台服务器连接在一起。

![Select the Site Manager button.](img/2734a4b286d6fe1c2bf971013d928170.png)

Select the Site Manager button.



您也可以在主 FileZilla 菜单中选择**文件>站点管理器**来调出该面板。

![Go to File > Site Manager.](img/361e069cbfe97f8bdef3b7685e5c4e83.png)

Go to File > Site Manager.



**站点管理器**页面提供标题为**常规**、**高级**、**传送设置**和**字符集**的选项卡。如果您不添加新的站点或文件夹来建立本地计算机和远程服务器之间的连接，这些选项将呈灰色显示。

要解锁**常规**选项卡，选择**选择条目**部分下的**我的站点**文件夹，然后点击**新建站点**按钮。这将在 FileZilla 中生成一个新的站点文件夹。

![Choose My Sites, then click on the New Site button.](img/e043c1baff9a3a0eb203214b9516268f.png)

Choose My Sites, then click on the New Site button.



给新网站起一个你想要的名字(最好是一眼就能识别的名字，比如网站的名字或域名)。

一旦添加了新站点，您就可以访问右边更高级的设置，包括 **General** 选项卡。

选择此**通用**选项卡，可以看到我们之前看到的相同字段，例如**主机**、**用户名**、**端口**和**密码**。

![The General tab in the Site Manager contains ways to change the Protocol and type in login credentials.](img/10a44076218edc48a19a07299a65ba58.png)

The General tab in the Site Manager contains ways to change the Protocol and type in login credentials.



完全可以在这个区域输入 FTP 凭证，而不是在**快速连接**部分。然而，在我们的例子中，我们希望实现一个 SFTP 连接，因为 Kinsta 与 SFTP 一起工作。

为此，打开**协议**下拉菜单，显示 FileZilla 中可用于链接的协议列表，然后将**SFTP–SSH 文件传输协议**选项标记为您想要使用的协议。

![Select SFTP under the Protocol field.](img/34b97cdca9482376823198e1c1eb7557.png)

Select SFTP under the Protocol field.



现在您已经有了添加 SFTP 凭证并通过 FileZilla 连接到您的 Kinsta 网站的理想设置。

点击**连接**按钮继续。

![Fill in the credentials for the right protocol and hit Connect.](img/31f7b63891d4c8ecef386dd4777fd5d0.png)

Fill in the credentials for the right protocol and hit Connect.



与远程站点的连接过程应该只需要几秒钟。

在某些情况下，如果服务器的主机密钥未知，您可能会被要求信任主机。如果您确信自己拥有正确的服务器凭据，请随意选中复选框**始终信任此主机**；这将防止提示再次出现。

点击**确定**。

![Tell FileZilla that you trust the host for the future.](img/c43d0084b1624202bc433a87d2cd9fc6.png)

Tell FileZilla that you trust the host for the future.



FileZilla 将运行一些状态更新，然后告诉您目录列表连接成功。在状态更新列表底部查找**成功**文本。

成功的连接还会显示来自您的主机服务器的文件目录。在这个例子中，我们使用了一个托管在 Kinsta 服务器上的 WordPress 站点。FileZilla 窗口的右侧现在显示了根目录，以及单击站点文件夹后该目录中的所有文件。

如果你在定位根目录时遇到困难，寻找像 **/www** 或**/thenamofyoursite**这样的文件夹，以确保你在正确的位置。

![The connection success message.](img/4082de508a81434221bb6da7ecf37a69.png)

The connection success message.



如上所述，这个远程服务器保存着 WordPress 站点的内容。所以，你可以深入到根目录，点击 **/public** 文件夹。

正如你对 WordPress 网站的期望，FileZilla 在 **/public** 文件夹下显示了类似于 **/wp-admin** 、 **/wp-content** 和 **/wp-includes** 的文件夹。这些是 WordPress 站点的一些[主文件，所以记住如何找到它们是明智的。](https://kinsta.com/knowledgebase/wordpress-files/)

![The Remote Site section now shows common WordPress files, all of which are ready for transfer.](img/6a149d28275734942d69c17e2e5ac1a4.png)

The Remote Site section now shows common WordPress files, all of which are ready for transfer.



祝贺您，您已经通过 FileZilla 成功建立了 SFTP 连接！

这使得从您的计算机和远程主机服务器移动、删除、复制、上传和下载文件成为可能。我们将在下面的章节中讨论这些任务。



### 信息

如果您不是 Kinstsa 客户，请到您主机的仪表板或 cPanel 查找登录凭据。所有这些仪表板略有不同，但你通常可以去**帐户**、**用户**或**网站**页面寻找你的主机凭证，你也可能会发现主机有一个专门的 **FTP** 或 **SFTP** 部分，上面有所有这些信息。如果你有困难，联系你的主人问一下。



## 如何在 FileZilla 界面中导航

FileZilla 以其简单、直观的界面而闻名，不会经常改变。偶尔我们会看到新的特性，但是 FTP 客户端背后的一般结构，它的主界面，以及分散在整个程序中的按钮通常保持不变。

在这一节中，我们将解释 FileZilla 中每个元素的用途。此外，我们将讨论如何有效地使用 FileZilla 接口来完成最常见的任务。

下面，你会看到 FileZilla 主屏幕的视图。我们已经标记了每个部分，并在下面引用了这些部分的用途。

![A full view of FileZilla and its many functions.](img/1bc9b84a9449047e9d7a204d014e7174.png)

A full view of FileZilla and its many functions.



1.  **控制面板:**FileZilla 窗口的顶栏。在这里，您可以使用 **Quickconnect** 功能，使用主机凭证快速链接本地和远程目录。它还包含用于完成常见任务的快捷键。从左边开始，这些按钮的名称/功能如下:
    1.  现场经理
    2.  切换消息日志的显示
    3.  切换本地目录树的显示
    4.  切换远程目录树的显示
    5.  切换传输队列的显示
    6.  刷新文件和文件夹列表
    7.  切换传输队列的处理
    8.  取消当前操作
    9.  从当前可见的服务器断开连接
    10.  重新连接到上次使用的服务器
    11.  打开“目录列表过滤器”对话框
    12.  切换目录比较
    13.  切换同步浏览
    14.  递归搜索文件
2.  **消息日志:**显示您的 FTP 或 SFTP 连接当前状态的消息。您可以在这里看到成功消息，或者错误、断开连接和目录详细信息的消息。
3.  **本地目录树:**您当前在本地机器上的文件的层次结构。您可以打开所有这些文件，四处移动它们，或者通过将它们拖放到右侧来将它们传输到远程站点。
4.  **远程目录树:**远程服务器上文件的层次结构。像本地目录一样，你可以通过左右点击来修改这些文件，并打开文件来查看里面的内容。
5.  **本地目录内容:**您当前在本地目录树中选择的文件的内容列表。你也可以在这个区域修改文件。
6.  **远程目录内容:**您当前在远程目录树中选择的文件夹内的文件列表。也可以在这个区域修改文件。
7.  **传输队列:**显示排队的、失败的或成功的文件传输信息的区域。使用底部的选项卡只过滤其中一个类别。

这些区域中的大部分都是以某种方式交互的，这意味着你可以左击或右键单击像**本地目录内容**、**消息日志**或**传输队列**这样的部分，以调出具有更多选项的附加菜单。

### 目录树和目录内容

例如，FileZilla 用户通常从工作在**目录树**或**目录内容**区域开始。右键单击**本地目录树**或**内容**部分中的文件，加载带有选项的菜单以完成以下操作:

*   将文件上传到远程站点
*   将文件添加到队列
*   在您的计算机上打开文件进行查看
*   在您的计算机上编辑文件
*   创建目录
*   创建目录并输入它
*   仅刷新此文件
*   从当前目录中删除文件
*   重命名文件

![Right-clicking in the Local Directory Contents module shows a myriad of options for those files.](img/e4f652578a9292dff9acdb0096ff09e8.png)

Right-clicking in the Local Directory Contents module shows a myriad of options for those files.



根据您放置鼠标的区域，右键选项会有所不同。如果您将鼠标指针移动到**远程内容**模块并右键单击，您会看到所选文件的一组不同的命令。这是有道理的——与本地文件相比，用户在处理远程文件时更倾向于选择其他操作。

因此，右键单击**远程内容**区域会产生以下选项:

*   将文件从远程服务器下载到您的本地计算机
*   将文件添加到队列
*   查看或编辑您选择的文件
*   从所选文件创建目录
*   创建目录并输入它
*   在 FileZilla 中打开文件夹内创建一个新文件
*   刷新加载的文件
*   删除您在远程目录中选择的文件
*   重命名文件
*   将 URL 复制到剪贴板
*   查看所选文件的文件权限

![A right-click on a remote file brings up different choices.](img/06544acf094684c39c5b170023fe2bcd.png)

A right-click on a remote file brings up different choices.



另一方面，左击允许您展开文件夹以查看里面的内容，或者完全打开它以操作和管理其内容。

您还可以按住鼠标左键将文件拖到 FileZilla 界面中的另一个位置。

例如，下面的 GIF 显示了我们在**本地目录内容**区域中按住并选择一个 PNG 文件，并拖动它将其放置在**远程目录树**中。

![Dragging a local file to the remote site activates an instant upload.](img/5a6ad1c5c56b9d3ab8ce5bb57515c88d.png)

Dragging a local file to the remote site activates an instant upload.



在上面的例子中，我们上传了一个 PNG 图像文件到 WordPress 主题的 **/image** 文件夹中(确切的说是 TwentyTwentyOne 主题)。这将以前的本地文件发送到远程环境，同时在本地目录中留下原始映像文件的副本。

### 本地和远程目录内容

您还可以将**本地目录内容**移动到**远程目录内容**，或者通过将项目从远程服务器传输到本地文件来反转操作。

拖放文件后，根据您将文件移动到的位置，可能会发生许多操作之一。例如，移动到远程服务器的本地文件会上传到您选择的目录。将远程文件移动到本地会将该文件下载到您的本地机器上。

### 使用快捷键自定义 FileZilla 界面

我们在上一节讨论了**控制面板**快捷键，但是现在我们将向您展示如何使用它们来调整 FileZilla 界面的布局。通过这种方式，您可以自定义窗口中显示的内容，以获得更加友好的用户体验。

作为一个提示，快速键没有标签，但是你可以将鼠标放在每一个上面来查看一个描述性的弹出窗口。

首先，**站点管理器**按钮提供了一些设置，以自定义哪些目录始终显示。点击**站点管理器**图标打开。

![Select the Site Manager button.](img/642e9626e1e62a2890f3ed8fd9b96066.png)

Select the Site Manager button.



我们已经知道可以连接站点并在**站点管理器**中输入 SFTP 凭证。还有改变 FileZilla 界面的设置，甚至制作书签或新文件夹。

找到包含**常规、高级、传输设置和字符集**选项卡的菜单区域。选择**高级**选项卡继续。

![Go to the Advanced tab.](img/264e0a349aa6e8a3171626d800f60355.png)

Go to the Advanced tab.



#### 更改默认的本地和远程目录

在这一部分中，您可以找到两个重要的自定义设置。第一个是针对**默认本地目录**。第二个为**默认远程目录**。

对于这两者，您都可以单击**浏览**按钮来查找本地或远程环境中的目录。这样，无论何时用相同的凭证打开 FileZilla，它都会自动从头开始显示这些目录。

我们可能会建议选择 **/public** 文件夹作为**的默认远程目录**，因为这是一个在 WordPress 站点上开始工作的热门位置。

![Default local and remote directories.](img/0631a2ba0c0fd7974e0992da3e709064.png)

Default local and remote directories.



#### 传输设置

在**传输设置**标签下，你会看到一个选项**限制 FileZilla 中同时连接**的数量。简而言之，FileZilla 提供了一种同时连接多个远程服务器的方法。如果你不喜欢这样，只需勾选复选框，在**最大连接数**字段中输入一个数字。

![It's also an option to limit the number of simultaneous connections in FileZilla.](img/f963c56f3034a2943ffcb4f2e640e456.png)

It’s also an option to limit the number of simultaneous connections in FileZilla.



#### 字符集

在**站点管理器**中的最后一个标签叫做**字符集**。尽管这并不一定控制 FileZilla 的接口，但它与您的工作流紧密相关，并确保您检测到文件名的正确字符集编码。

你可以选择**强制 UTF-8** 或者制作一个**自定义字符集**，但是我们强烈建议坚持使用**自动检测**设置，因为使用错误的字符集会在 FileZilla 中不正确地显示文件名。

![Leave the Charset settings on Autodetect.](img/0d48f8b2bd367908721a3a93937b304b.png)

Leave the Charset settings on Autodetect.



### 快速键按钮

回到主窗口，FileZilla 提供了几个快捷键按钮，用于从视图中移除元素。这可以帮助你清理整体布局，隐藏 FileZilla 中不常用的部分。

#### 消息日志快捷键

在**站点管理器**按钮旁边的第一个图标是切换**消息日志**的显示。**消息日志**(**FTP 凭证**字段下面的部分)显示了您当前连接的状态。

有些人可能想隐藏这些消息，因为普通用户不需要知道 FileZilla 正在“检索目录列表”或“使用用户名”。毕竟，我们已经知道我们试图进入哪个用户名和目录。

![This button toggles the display of the Message Log.](img/8604ec3416f4173caf0b33307aaf396b.png)

This button toggles the display of the Message Log.



点击该按钮会将**消息日志**从视图中移除，只显示 **FTP 凭证**字段和**站点目录**过滤器。

请记住，尽管**消息日志**有时可能感觉像是快速移动的代码和消息的无用组合，但它也是告诉您连接是否发生错误的模块。因此，当你通过 SFTP 或 FTP 连接时，至少将**消息日志**留在视野中是个好主意。

![The Message Log no longer appears.](img/2ed785766d29633c050ea15ff2e1b0af.png)

The Message Log no longer appears.



#### 本地目录树快捷键

左边第三个按钮让您切换 FileZilla 中本地目录树的显示。这将隐藏或取消隐藏与本地机器相关的**目录树**部分。

一些用户认为**本地目录树**和**本地目录内容**部分是多余的。虽然不完全是这样，但是暂时给**本地内容**区域更多空间来导航本地机器上的特定文件是有意义的。

![Toggle the display of the Local Directory Tree.](img/be40300ec76c04e164e116e44150c1dd.png)

Toggle the display of the Local Directory Tree.



如上所述，快速点击该按钮会删除**本地目录树**，但会给**本地目录内容**留下比以前多得多的空间。您还会注意到,**远程站点**端一点也没有改变——无论是**远程目录树**还是**远程目录内容**都仍然可供您将文件上传到您的服务器。

![The Local Directory Tree is now hidden.](img/ba81cb975da5196de127dad933cc9eee.png)

The Local Directory Tree is now hidden.



#### 远程目录树快捷键

如果您想完成一个类似的操作，但是使用的是在**远程目录**端的接口，该怎么办呢？嗯，再往右一个快捷按钮通过切换**远程目录树**的显示来工作。

![Toggle the display of the Remote Directory Tree.](img/3741c4476c546295a0d8c2f34b6f8d0e.png)

Toggle the display of the Remote Directory Tree.



这是屏幕右侧的目录树。使用该按钮隐藏树，并为**远程目录内容**腾出额外的空间。

在这种情况下，**远程目录树**消失了，但是左侧的所有内容(对于**本地目录**来说)都保持不变。

![The hidden Remote Directory Tree.](img/ee43258f13a7a48e3207852f6e55be06.png)

The hidden Remote Directory Tree.



#### 转移队列快捷键

FileZilla **控制面板**中左起第五个按钮看起来像多个指向相反方向的蓝色和绿色箭头。选择此按钮切换 FileZilla 界面底部的**传送队列**的显示。

就像**消息日志**一样，用户偶尔会把这个部分看作是一个背景功能，你不必每次转移时都看到。

话虽如此，失败的和排队的传输会显示在这个列表中，所以如果您怀疑某个文件没有正确下载或上传，或者如果某个文件需要很长时间才能完成，最好检查一下**传输队列**。

![Toggle the Transfer Queue display.](img/4cd6211ee0af08129f75600960c2534d.png)

Toggle the Transfer Queue display.



点击按钮，你会注意到**转移队列**部分消失了，窗口变得更小、更整洁。

![No more Transfer Queue.](img/2ac109fc3126ea77d76ba62f4e762946.png)

No more Transfer Queue.



#### 附加转移修改快捷键

FileZilla **控制面板**中间的快捷键与管理 FileZilla 布局没有任何关系。但是，您应该知道它们都是用来修改正在进行的传输或连接的服务器的。例如，这些按钮允许您立即取消当前操作，断开与当前服务器的连接，或者自动连接到最近登录的服务器。

![Quick keys for things like canceling operations and disconnecting servers.](img/c74d7d735bdcd9f6f9803f08f8631ed4.png)

Quick keys for things like canceling operations and disconnecting servers.



#### 切换目录比较快捷键

定制 FileZilla 界面的另一种方式是利用**切换目录比较**按钮。快捷键在某些页面或文件上看起来像一个放大镜。

激活该按钮将获取您打开的两个目录(一个来自本地，另一个来自远程)并比较它们，以便您可以查看它们是否有相同的文件。

例如，您可能需要从本地机器上传一组资产到您的服务器。事后，检查它是否工作的一个很好的方法是运行**目录比较**工具。它将相似或相同的文件堆叠在一起，如果发现重复的文件，就会显示绿色阴影。

![A side-by-side comparison of files in the Local Site and Remote Site.](img/50bee010a31de37f279cf3454313b204.png)

A side-by-side comparison of files in the Local Site and Remote Site.



上图截图中，我们的**。本地文件和远程列表中都显示了之前上传的 png** 文件。这正是我们想要的:在两个位置有相同的文件副本。

## 如何使用 FileZilla 上传、下载和管理文件

我们简单地提到过，您可以在 FileZilla 中上传、下载和管理远程和本地文件。在这一节中，我们将深入了解每一个细节，并带您完成正确完成它们所需的步骤。

简而言之，在 FileZilla 中有两种上传、下载或管理文件的方法:右键单击有问题的文件或将其拖放到新位置。

### 如何使用 FileZilla 下载文件

在 FileZilla 中，用户可以从**远程目录树**或**远程目录内容**模块下载整个目录或单个文件；这基本上是屏幕右侧的所有内容。

在你控制**本地目录树**和**本地目录内容**的左侧，没有**下载**按钮，而是有一个**上传**到远程服务器的按钮。

为了下载文件，在远程服务器上找到您想要下载到本地环境的元素。例如，我们可以从 WordPress 站点打开一个主题文件，并在 **/template-parts/footer** 下查找 **/footer-widgets.php** 文件。

您下载、查看或编辑此文件的原因可能会有所不同。有些人只是想更好地了解他们的网站中有哪些类型的文件。其他时候，您可能需要下载一个文件，编辑其内容，然后[将其重新上传回服务器](https://kinsta.com/blog/html-to-wordpress/)。你也可能会发现一些文件被破坏[或者被黑](https://kinsta.com/blog/wordpress-hacked/)。这可能需要您下载或查看该文件，以检查潜在的问题。

不管您的推理是什么，通常最好是从右键单击有问题的文件开始，查看您的文件管理选项。同样，我们在这个例子中使用了 **/footer-widgets.php** 文件。

右键单击文件以打开下拉菜单。这是管理 FileZilla 中任何文件的最佳方式，因为它提供了传输、编辑或管理文件的所有可能方式。

该菜单中可供选择的选项包括:

*   [计] 下载
*   将文件添加到队列
*   查看/编辑
*   创建目录
*   创建目录并输入它
*   创建新文件
*   恢复精神
*   删除
*   重新命名
*   将 URL 复制到剪贴板
*   文件权限

在某些时候，您可能想要查看文件以进行编辑，或者只是想看看里面有什么。在这种情况下，点击**查看/编辑**按钮。

![Right-click on a file and choose the View/Edit button.](img/590295a39935630e93228520985e872c.png)

Right-click on a file and choose the View/Edit button.



### 如有必要，将文件下载到本地站点

有时，根据您的文件权限和提取文件的位置，无法从远程服务器查看或编辑文件。如果是这样的话，你可以下载到你的本地网站上查看。

此外，您可能需要在您的计算机上为该文件类型设置一个默认编辑器。我们建议[寻找你最喜欢的文本编辑器](https://kinsta.com/blog/best-text-editors/)来编辑 HTML 和 PHP 文件。你必须考虑所用文件类型的兼容程序，比如使用图片软件处理 [PNG 或](https://kinsta.com/blog/image-file-types/)JPG 文件。

![Select a program that's able to open, view, and edit the desired file.](img/62681b6276b5a8a0d20a2c6946c40f74.png)

Select a program that’s able to open, view, and edit the desired file.



现在，该文件将在您之前选择的程序中打开。在本例中，我们在 Atom 文本编辑器程序中打开了一个**footer-widgets.php**文件，允许我们查看文件内容并进行编辑。

![View and edit any file from FileZilla in the local software of your choosing.](img/d8c7d4bdadfadb1704a165fd412cd92e.png)

View and edit any file from FileZilla in the local software of your choosing.



要将文件下载到本地站点，右键单击远程服务器文件并选择**下载**选项。

![Right-click and use the Download button.](img/848da2c0cada750839a00ff09d069c81.png)

Right-click and use the Download button.



根据文件大小，**下载**功能需要几秒钟时间。该文件最终会出现在您在 FileZilla 的远程站点端链接并打开的文件目录中。现在您应该能够从您的计算机或通过 FileZilla 接口访问它了。

请记住，通过将文件从 FileZilla 的右侧拖放到左侧，也可以从远程站点下载文件。它的工作方式与点击**下载**按钮完全相同。只需确保将文件拖到本地机器上您希望看到它的文件夹中。

如果您对传输过程有任何疑问，请查看**消息日志**区域。当下载正常工作时，FileZilla 会显示类似“文件传输成功”的消息。如果失败，您应该会看到一条“文件传输不成功”的消息。这通常以红色文本显示。

![The transferred file in its new location, along with a Success message.](img/bb35da824c568c7ea0899af84b51a631.png)

The transferred file in its new location, along with a Success message.



### 将文件添加到队列

您可能已经看到，当右键单击远程站点文件时，您可以选择**将文件添加到队列**。当您选择这种方法时，您是在告诉 FileZilla，您最终想要将文件下载到您的本地站点，但是要晚一点。

这允许您在点击**进程队列**按钮下载队列中的所有内容之前，从不同的位置将多个文件放入队列中。与拖放非常相似，**进程队列**按钮(当处理远程站点文件时)完成了到本地站点的标准下载。

![The Process Queue button in action.](img/54afb4316c84780ba412d8808b9664c0.png)

The Process Queue button in action.



### 检查文件权限

另一种在远程站点管理文件的方法是检查[文件权限](https://kinsta.com/blog/wordpress-permissions/)并修改它们以增强网站安全性。简而言之，文件权限告诉您的服务器谁可以读取、写入和执行文件。

![t's possible to view File Permissions from FileZilla.](img/ca820b05b50bd4b9e90c077db8c2a707.png)

It’s possible to view File Permissions from FileZilla.



这些权限代表了要考虑的安全性的一个重要方面。使它们过于严格可能会破坏您的站点，但是不检查它们可能会带来安全问题。

![You can change file permissions right in FileZilla.](img/d7bde11ac61362550060a6d74c3476b7.png)

You can change file permissions right in FileZilla.



### 管理本地文件

现在让我们看看如何打开、上传和编辑位于本地站点(也称为您的计算机)的文件。

我们已经知道，FileZilla 界面左侧的文件目录和内容是您计算机上文件目录的直接副本。因此，我们可以将图像、HTML 文档或视频等任何文件上传到远程站点，而无需打开您的内容管理系统或托管仪表板。

在 FileZilla 中还有其他几种处理本地文件的方法。

您应该总是从 FileZilla 的**文件目录内容**部分中调出所需的文件开始。然后，右键单击单个文件或完整的目录，以查看带有几个选项的下拉菜单。

这个下拉列表与我们右键单击远程站点文件时看到的略有不同。在这里，我们看到:

*   上传
*   将文件添加到队列
*   打开
*   编辑
*   创建目录
*   创建目录并输入它
*   恢复精神
*   删除
*   重新命名

其中大多数，像删除和重命名，都是不言自明的。但是有几个可能不太清楚。

在本地站点上查看和编辑文件的最常见方式之一是选择**打开**子菜单项。

![A right-click on a local file presents options for uploading.](img/44ce437664e3ce1621a99c5f033b9887.png)

A right-click on a local file presents options for uploading.



从 FileZilla 的本地端打开文件通常要快得多，因为您不必指定要使用的程序。此外，所有这些文件都已经在你的电脑上，所以不应该有任何麻烦的文件权限。

## 注册订阅时事通讯



### 想知道我们是怎么让流量增长超过 1000%的吗？

加入 20，000 多名获得我们每周时事通讯和内部消息的人的行列吧！

[Subscribe Now](#newsletter)

一旦你点击了**打开**按钮，FileZilla 就会寻找使用该文件所需的程序。

在本例中，我们在 Atom 文本编辑器中打开了一个**functions.php**文件。这样，我们就可以查看该文件的内容，而无需修改代码。

![Viewing the functions.php file in Atom.](img/a799b725afe9ba37eaba51b2d3a0e490.png)

Viewing the functions.php file in Atom.



如果您想对文件进行更改并在完成后保存到 FileZilla，也可以选择 **Edit** 菜单项。

### 从本地上传到远程

使用 FileZilla 的一个主要原因是将文件从本地计算机上传到远程服务器(比如网站)。在相同的本地站点部分，您可以选择完整的目录或单个文件，然后右键单击您的选择再次查看菜单。

要将文件发送到右侧选择的远程目录，请单击菜单中的**上传**按钮。

![Click on the Upload button.](img/e812d4cc6159b710adf7d7d94111f27b.png)

Click on the Upload button.



给你一个真实世界的例子，你可能发现你的站点崩溃了，你怀疑是 functions.php 文件中的某个东西导致了这个问题。很明显，你不能从 WordPress 访问这个文件(因为网站关闭了)，而且你可能很难进入你的主机的仪表板。

但是您可以通过上传一个干净的**functions.php**文件来完全替换损坏的文件来解决这个问题。

如果文件是新的，您不会看到任何替换现有文件的消息。然而，在这种情况下，我们试图上传一个干净的**functions.php**文件，并摆脱旧的。

因此，FileZilla 识别相同的文件名，并询问您是否想要覆盖远程服务器上现有的**functions.php**文件，或者做些其他事情，比如重命名文件或完全跳过这个过程。

对于我们的例子，我们将在**动作**标题下标记**覆盖**选项。

点击**确定**按钮继续。

![Overwrite the old file.](img/85dc877d802b50d958f80e7e18a42346.png)

Overwrite the old file.



与所有传输一样，传输时间取决于文件大小。话虽如此，FileZilla 以快速上传和下载文件而闻名，即使是较大的文件。

### 检查传输状态

为了确保您的文件确实上传了，查看**远程目录内容**区域，并在文件树中找到它。

如果您找不到它，您可能一直在上传文件以替换同名的远程文件。您可以查看文件并寻找新的更改，但是编码文档对您来说太复杂了。

因此，我们建议转到**消息日志**来阅读您上传的状态更新。您应该会看到类似“开始上传”和“文件传输成功”的消息，表明文件已上传到远程站点。如果出现问题，您应该会看到红色的失败消息。

![Check on the status updates to ensure files get moved properly.](img/01b042b51147dddc593efb4be2c4747b.png)

检查状态更新以确保文件被正确移动。



T6】

### FileZilla 支持的文件格式

FileZilla 支持传输您可以保存在电脑上的任何文件类型。您本地计算机上的任何文件，以及您存储在远程服务器上的任何文件类型，都可以顺利地通过 FileZilla 传输。您以后是否能够打开它们取决于第三方程序。

FileZilla 通过利用两种主要的“数据类型”来管理这种全接受数据传输系统:

*   美国信息交换标准代码
*   二进制的

FileZilla 偶尔会使用其他数据类型，比如 EBCDIC 和 Local，但这种情况非常少见。

简而言之，FileZilla 接受您计划传输的任何文件，并通过交换数据类型来使用另一种传输模式。这有点像转变，但不完全是。相反，FileZilla 通过选择与您要移动的文件类型相对应的适当数据类型，将文件作为文本或原始数据传输。

虽然听起来很复杂，但 FileZilla 实际上只是在两种数据类型之间做出决定，所以这个过程只需要一会儿。

此外，您不需要自己决定:，因为 FileZilla 有一个 **Auto** 模式来选择最有意义的传输类型。FileZilla 的默认设置是这样的，但是你总是可以通过进入 **FileZilla >设置>传输> FTP:文件类型**来改变它。

![You can change the transfer type or set it as Auto in the FileZilla Settings window.](img/8a2b9812f9339daf1e049fa78eea0560.png)

You can change the transfer type or set it as Auto in the FileZilla Settings window.



在 **Auto** 模式下，FileZilla 会在两种最常见的上传或下载文件的数据类型中做出选择。无论你是上传还是下载都没关系，但程序中发送的是什么类型的文件却很重要。

ASCII 把你的文件作为文本数据格式传输。因为所有的传输都是在文本中完成的，所以在移动 TXT、HTML 和 PHP 文件时经常会看到这种数据类型。

另一方面，考虑到二进制数据类型通过使用原始数据进行传输，二进制最适合更复杂的文件类型，如 JPG、MP3 和 WAV 文件(或基本上任何类型的媒体文件)。毕竟，视频文件转换成文本文件最终不会产生高质量的结果。

总的来说，你可以期待 FileZilla 在 **Auto** 模式下轻松完成所有文件传输。传输以文本或原始数据格式完成；选择的数据格式取决于上传或下载的文件类型。

## 如何使用 FileZilla 过滤文件

从您的电脑和远程服务器打开文件会增加 FileZilla 的编辑或传输选项列表。当您打开更多的文件夹时，即使是最有经验的开发人员也会感到有些害怕或困惑。

当然，FileZilla 可以处理数以千计的文件，但是人类的大脑可能会在试图记住它把一张图片或 CSS 文件放在哪里时不知所措。

这就是过滤发挥作用的地方。

过滤允许您选择在 FileZilla 屏幕上显示的特定文件类型。这样，您就有机会隐藏大多数您永远不会使用的文件，或者专注于您希望更频繁访问的特定目录。

所有过滤都发生在**目录列表过滤对话框**区域。它位于本文前面讨论的一个快捷键下。快捷键图标看起来像两个界面面板，中间有绿色、红色和黄色的线条。

点击此按钮继续过滤。

![To filter files in FileZilla, click on the Directory Listing Dialog button.](img/bbcd378701371e92cde99cdcea894c5c.png)

To filter files in FileZilla, click on the Directory Listing Dialog button.



### 目录列表过滤器

这将显示一个名为**的页面，其中列出了过滤器**。在这里，您会看到两个过滤器列表:一个用于**本地过滤器**，另一个用于**远程过滤器**。每一端都有相同的过滤器类型，但是它们为各自的目录工作。

为了让您了解它是如何工作的，我们将勾选复选框**，以便在**本地滤镜**和**远程滤镜**上仅显示图像**。完成选择后，点击 **OK** 按钮使过滤器生效。

![One filter is for only showing images in FileZilla results.](img/f26d7ad01e704032af3019771321cdc7.png)

One filter is for only showing images in FileZilla results.



因此，FileZilla 现在只显示图像文件，而不考虑您打开的目录。

在下面的截图中，**本地站点**部分在本地**/下载**文件夹中有一个 PNG 和 JPG 文件的列表——除此之外别无其他——这要感谢我们的过滤器。

![Only image files appear in FileZilla with the filter active.](img/49308717bf54d3ca7ea79b325c6b226b.png)

Only image files appear in FileZilla with the filter active.



但是，您将能够查看这些目录中的文件夹，即使由于过滤器的原因，它们最终没有显示任何内容。

![Many of the folders appear empty since they don't contain image files.](img/63fcafd4e474c19b65c41919bc7058bb.png)

Many of the folders appear empty since they don’t contain image files.



### 附加过滤器

对于更多的过滤器，返回到列出过滤器的目录模块。您会发现主要的默认过滤器有:

*   源代码管理目录
*   无用的浏览器文件
*   临时文件和备份文件
*   配置文件
*   仅显示图像

总的来说，其中一些过滤器是为了清理你的界面，使 FileZilla 中的搜索过程更简单。这就是为什么他们可以选择删除默认的“临时文件”和“无用的资源管理器文件”。

然而，有些过滤器是用来显示所有事物的本质的。这就是为什么我们看到默认的“配置文件”和“图像”

过滤器需要考虑的另一个方面是如何独立添加**远程过滤器**和**本地过滤器**。随意过滤**本地过滤器**部分的图像，同时在**远程过滤器**侧显示**源代码控制目录**等内容。

每当试图激活过滤器时，点击 **OK** 按钮。

![You can add different filters on the remote and local sides.](img/b427d3bb37fa7231a3e08d7d73ab4888.png)

You can add different filters on the remote and local sides.



但是，如果默认的过滤器不足以满足您的需要呢？

在这种情况下，点击**编辑过滤规则**按钮，使其更加具体。

![Select the Edit Filter Rules button.](img/14d45d122fad4a1f907596c5659572ae.png)

Select the Edit Filter Rules button.



### 编辑过滤器窗口

**编辑过滤器**窗口为之前的每个默认过滤器提供了独特的条件和规则。例如，您可以在那里过滤掉与以“.”结尾的文件名不匹配的项目。png“，”。gif "，或者"。jpg”。

您还可以将过滤器同时应用于文件、目录或两者。

![Add more specific filter rules on this page.](img/be1ba5fd445141267f2380faf9ad4050.png)

Add more specific filter rules on this page.



作为另一个例子，您可以转到**源代码控制目录**过滤器，并将文件名设置为类似于。svn“和”。git ”,以便只显示那些文件，其余的文件从视图中过滤掉，如下面的截图所示。

![You can narrow down filters by only showing specific file extensions.](img/aba7acd9ca5b1ee0347c10e95db064ec.png)

You can narrow down filters by only showing specific file extensions.



## 如何在 FileZilla 中添加书签和多个站点

过滤器使得在 FileZilla 中移动变得更容易，但是书签对于直接进入经常使用的文件目录也很方便。

FileZilla 的书签功能就像浏览器书签一样，只是 FileZilla 不是保存网页，而是保存文件目录的一部分。

要添加和管理书签，点击**站点管理器**快捷键。

![Go to the Site Manager to work with bookmarks.](img/21cfa849258547ba990ac7d726b4123f.png)

Go to the Site Manager to work with bookmarks.



一旦进入**站点管理器**窗口，你会发现一个名为**我的站点**的文件夹。当您通过 FileZilla 创建 FTP 或 SFTP 链接时，所有远程站点连接都放在这里。

**站点管理器**还提供了与您的托管凭证实际建立连接的字段(如本文前面所述)。如果您已经通过 FTP 或 SFTP 连接，您应该会在**我的网站**文件夹中看到一个网站名称。在我们的例子中，我们站点的名称叫做“Testingsite”。

这里的目标是为该站点添加一个书签，使其更容易访问特定的目录或文件夹，而不必花费几分钟时间。

您可以为存储在 FileZilla 中的每个站点制作书签。由于我们目前在**站点管理器**中只连接了一个站点，选择该站点使其高亮显示。

现在，转到窗口底部，选择**新书签**按钮。

![Use the New Bookmark button after highlighting a site.](img/99463339562e622f1f3801a694379809.png)

Use the New Bookmark button after highlighting a site.



FileZilla 在您的 **My Sites** 文件夹中的站点层级下方添加了一个带有星形图标的“新书签”标签。您可以随意重命名书签以供参考。

移动到窗口右侧，找到**本地目录**和**远程目录**字段。这些开始时是空的书签，但你可以浏览特定的目录，以便在你进入书签时发送给它们。

Struggling with downtime and WordPress problems? Kinsta is the hosting solution designed to save you time! [Check out our features](https://kinsta.com/features/)

记录书签的一个原因是这样你就可以随时访问你的网站在本地目录下的备份文件。您也可以在**远程目录**字段中为**/公共**文件夹创建书签。有了这种配置，当发生文件损坏或网站崩溃等情况时，您可以将最近的备份文件上传到网站服务器上的正确位置。

要在字段中建立书签目录，您必须通过**浏览**找到正确的目录，或者将其粘贴到字段中。

**本地目录**字段很简单。只需点击**浏览**按钮，搜索您想要添加书签的文件，并将其添加到 FileZilla。

**远程目录**字段要求您复制并粘贴所需的目录或文件结构，您可以通过返回主 FileZilla 页面找到。他们在**远程目录树**上方的**远程站点**下拉列表中列出了整个目录地址。



### 信息

请记住，不需要同时为**本地目录**和**远程目录**制作书签。您可能只想快速导航到其中一个文件夹。



现在您已经指定了一个**本地**和(或)**远程目录**，点击 **OK** 按钮将其保存到 FileZilla 中，以备后用。

![Fill in the desired paths for your local or remote bookmarks.](img/cd60ec583f38d741ab28d1e71cb832e9.png)

Fill in the desired paths for your local or remote bookmarks.



那么现在你已经设置了一些新的书签，你如何激活一个书签来快速重新路由到你选择的文件呢？

书签保存在 FileZilla 中。因此，只要您在程序中保持该站点活动，您就可以继续访问该书签。

所以，假设你打开一些随机的远程和本地文件。您可以在下面的截图中看到，这两个文件夹都不包含我们在书签中的内容。

![An example of a user being elsewhere in FileZilla.](img/e561e260e7390f1d09f3c0e7e337784a.png)

An example of a user being elsewhere in FileZilla.



要使用书签，点击左上角的**站点管理器**按钮，然后从您的**我的站点**文件夹中选择书签。

点击**连接**按钮激活书签并直接发送到文件。

![Click Connect in the Site Manager to move away from what you're doing and towards the save bookmark.](img/b69cde0cfbb7f891353f1bd8b252ccd6.png)

Click Connect in the Site Manager to move away from what you’re doing and towards the save bookmark.



如果您已经连接到服务器，通常会出现警告。如果您希望保持多个连接运行，您可以中止连接或建立到新服务器的新连接。

在这种情况下，我们将使用 **Abort Previous Connection** 选项，因为我们不关心我们之前在做什么。然而，如果你想保存你以前的位置，使用**在新标签页建立连接**选项可能会更好。

如果您不想在将来看到这个弹出窗口，也可以选择**总是执行这个动作**框。

无论您选择什么，点击 **OK** 按钮继续。

![Decide to abort the previous connection or make a new one in a separate tab.](img/c9e0e38ef1e1b082fdb7f388acf3ebb4.png)

Decide to abort the previous connection or make a new one in a separate tab.



书签然后直接打开在站点管理器中指定的文件。

在一瞬间，你可以在本地站点**和远程站点**访问一些重要的东西。如前所述，如果你不想要的话，没有必要为两者都做书签。****

我们的截屏显示了这样一个书签的便利，看到我们如何自动获得对 WordPress 站点备份的所有重要文件的访问，如 **/wp-admin** 、 **/wp-content** 和 **/wp-includes** 。**远程站点**部分将我们发送到 **/public** 文件夹，其中包含恢复备份时通常需要替换的文件夹。

现在需要做的就是将文件从**本地站点**上传到**远程站点**，以便完全恢复备份。当你考虑使用书签恢复备份时，你也应该[考虑微调你的 WordPress 备份过程](https://kinsta.com/blog/restore-wordpress-from-backup/)。

记住，这只是你可能考虑在 FileZilla 中打开书签的原因之一。

有时候，直接访问常用的文件目录就很好了。其他时候，您需要在紧急情况下定位文件，或者需要在插件中替换横幅图像。选择是无穷无尽的。

![The bookmark directly sent us to the save folders from before.](img/bc6926d2dbdddecde38513a38b052cfb.png)

The bookmark directly sent us to the save folders from before.



为了总结这一节，我们想谈谈如何在 FileZilla 中添加多个站点，因为这是在管理书签的同一个地方完成的。

添加一个新网站意味着你要连接几个网站同时在 FileZilla 上运行。每个站点都需要自己的 SFTP 或 FTP 托管凭据，之后您就可以连接到站点并在站点之间切换。

再次选择 FileZilla 主窗口右上角的**站点管理器**按钮。接下来，进入**我的站点**文件夹，点击**新站点**按钮。

![Select My Sites and click on New Site.](img/34f6ee2e2cff44fdd7d560b44529540d.png)

Select My Sites and click on New Site.



FileZilla 会自动在 **My Sites** 文件夹中生成一个新站点。你可以点击网站进行重命名，供自己参考。

关于 FileZilla 上的新网站，以下是一些需要记住的重要事项:

*   你可以在 FileZilla 上创建任意多的站点。它们都存储在那个**我的网站**文件夹下。
*   您可以为列在**我的站点**文件夹中的每个站点创建独特的书签。
*   您必须使用唯一的 FTP 或 SFTP 主机凭据连接每个新站点。这与我们在本文前面介绍的方法没有什么不同。你必须去你的主机，复制凭证，如**主机**、**用户**、**端口**和**密码**。
*   记住要选择正确的协议，否则会出错。大多数知名主机都使用 SFTP，因为它更安全。

![All new sites require their own host credentials to make a connection.](img/fbbbd34839d72731ee1019ed4a3ac26c.png)

All new sites require their own host credentials to make a connection.



## 如何使用 FileZilla 进行本地、远程和比较文件搜索

跳过 FileZilla 内部混乱的另一个解决方案是使用 **Search** 函数。

尽管 FileZilla 的**搜索**工具可能有点慢，但你可以键入与你正在寻找的文件匹配的关键字，然后在后台设置搜索查询，以便在你处理文件时完成搜索。

首先找到位于 FileZilla 主窗口右上角的双筒望远镜图标。这是**控制面板**中的最后一个快捷键。

这个按钮叫做**递归搜索文件**，它允许你在远程和本地站点完成大范围的搜索，以及两者的比较搜索。

点击**文件搜索**(双筒望远镜)按钮开始搜索。

![The binoculars icon is for file searching.](img/acd13922669495758f89bc9efe5c9711.png)

The binoculars icon is for file searching.



如你所见，有选项可以完成一个**本地搜索**、**远程搜索**和**对比搜索**。

### 本地文件搜索

我们将从**本地搜索**开始，因此选择该选项并转到**搜索目录**字段，键入您想要搜索的计算机目录。默认情况下，这通常是根据您在 FileZilla 中浏览的内容来填充的。如果您想在搜索中包括所有计算机文件，您可能需要将搜索范围扩大到一般用户目录。

在**搜索条件**字段中，选择**匹配以下所有**。

然后，转到搜索参数，键入可能包含在您想要查找的文件中的关键字。这将扫描整个目录，查找包含关键字的文件名。在这种情况下，我们将键入“kinsta”作为关键字来定位我们正在寻找的 Kinsta 徽标。

点击**搜索**按钮运行流程。

![Search FileZilla by typing in a keyword for a file name.](img/31c1df8481de7030345935977ce8e3ed.png)

Search FileZilla by typing in a keyword for a file name.



应该只需要几秒钟就可以显示一些结果，但是对较大目录的查询可能会继续在后台运行，或者需要更长时间才能产生任何结果。

移动到**结果**面板，查看**搜索**工具产生的结果。不出所料，FileZilla 在我的 **/document** 和 **/library** 文件夹中找到了几个 Kinsta 徽标的实例。

![The search results show up at the bottom of the window.](img/2c2f046f140faca71b3a43a44ff65fba.png)

The search results show up at the bottom of the window.



随意右键单击其中一个文件来完成操作，如在文件管理器中显示它，上传到远程服务器，或完全删除文件。

在这种情况下，我们将选择文件管理器中的**显示**链接来打开计算机上的图像。

![Choose what to do with your search results.](img/8cf74ec0295df8559bb2b71ed4abbd83.png)

Choose what to do with your search results.



就在那里！

![From FileZilla's search results, we can open those files on the computer.](img/7d3c19ba8d794997b7571862001de584.png)

From FileZilla’s search results, we can open those files on the computer.



**文件搜索**面板提供多种设置，使您的搜索更加具体。例如，您可以选择将**文件名**更改为以下之一:

*   Filesize
*   小路
*   日期

使用 **Filesize** 选项允许您查找大于或小于特定大小的文件。**日期**选项允许您键入日期范围，以定位在特定时间段创建的文件。

![Search for files based on name, size, path, or date.](img/e670dc67ff89829a5752c2d9938bdcdc.png)

Search for files based on name, size, path, or date.



**包含**下拉字段有其他选择来扩大或缩小您的搜索范围。单击该下拉菜单会显示以下选项:

*   包含
*   等于
*   始于
*   结尾为
*   匹配正则表达式
*   不包含

这些是您的一些主要搜索参数，因为它们如何指定必须对下一个字段中的条目做什么。例如，您可能只想找到以 PNG 结尾的**文件名**，而排除所有其他非 PNG 文件。

您也可以使用它得到更具体的信息，使用**等于**选项，只显示与您之前输入的关键字完全匹配的文件。

![Match searches based on other parameters like where the Filename begins with or ends with a specific keyword.](img/af52a2ce56b5f4fe5b97a2029ac2b6ee.png)

Match searches based on other parameters like where the Filename begins with or ends with a specific keyword.



最后，FileZilla 显示了一个带有以下选项的**搜索条件**下拉字段:

*   匹配以下所有内容
*   匹配以下任一项
*   不匹配以下任何一项
*   不匹配以下所有内容

这些与您可以在下面的框中包含多个搜索条件这一事实有关。因此，使用**匹配所有后续的**选项要求搜索与每个搜索条件一致。

您还会注意到窗口底部的几个复选框。同样，这些增强了您搜索更多特定需求的可能性。例如，您可以确保所有的**条件都区分大小写**。也可以限制您的搜索文件，目录，或两者都没有。

![Change your search conditions.](img/48270fca4c0743d4b829e220f97e26d1.png)

Change your search conditions.



继续，FileZilla 的**文件搜索**部分包含另外两种**搜索类型**:一种用于**远程搜索**，另一种用于**比较搜索**。

### 远程文件搜索

选择**远程搜索**单选按钮，将您的搜索限制在您的**远程站点**上的文件。

与**本地搜索**功能一样，该窗口要求您为您的**远程搜索**填写**搜索目录**。您必须粘贴到这个特定的目录中，或者自己键入。

**搜索条件**和其他搜索参数都与我们刚才提到的相同。您仍然可以调整从**文件名**到**日期**或者**包含**到**不包含**。

此外，您可以为想要查找的文件或目录键入搜索关键字。

对于本教程，我们将敲入“footer.php”，因为你经常需要定位**footer.php**文件，用于[调整 WordPress 页脚](https://kinsta.com/blog/how-to-edit-footer-in-wordpress/)，或者有时用于[向插件或主题添加 HTML 或 CSS](https://kinsta.com/knowledgebase/edit-wordpress-code/) 之类的东西。

点击**搜索**按钮运行搜索。

![Use the Remote Search radio button to only peruse files from the remote server.](img/ab2bac9e8f09a943b4e5e03e192615ce.png)

Use the Remote Search radio button to only peruse files from the remote server.



几个**footer.php**文件出现在我们的**搜索结果**部分。一定要检查**路径**列，以确定它是否是您想要的实际文件。

通过点击文件、查看文件或将文件下载到您的本地网站，您将有能力进一步探索这些文件。

![Footer.php search results on the remote site.](img/98f03ffd19bb862935a2a6146da4b7de.png)

Footer.php search results on the remote site.



### 比较文件搜索

FileZilla 上最后一种搜索工具叫做**比较搜索**。这允许您添加多个搜索条件，并在本地和远程目录中运行这些规则。结果并排显示，便于您分析差异或发现项目中实际需要使用哪一个。

对于这个，你必须选择搜索一个**本地目录**和一个**搜索目录**(远程目录)。我们将键入“wp-content”作为关键字，看看我们是否能够在本地备份文件和站点文件中识别出 **/wp-content** 文件。

![Select the Comparative Search button and select which directories you want to check.](img/dcbfe420cfd129079904eefc7d850fee.png)

Select the Comparative Search button and select which directories you want to check.



点击**搜索**按钮，然后等待查看**本地结果**和**远程结果**中出现的内容。

除了显示这两个文件在两种环境中存在或不存在之外，没有做太多的“比较”。除此之外，比较搜索还允许您选择那些文件进行编辑、上传或下载。

![We see that the /wp-content file is available in both the local and remote environments.](img/a043af4653a27d90a329405bdca076c4.png)

We see that the /wp-content file is available in both the local and remote environments.



## 如何修复 FileZilla 中的连接错误

尽管 FileZilla 很健壮，但由于不正确的登录凭证、DNS 信息问题或其他问题(如连接缓慢或不可靠)，它偶尔会出现错误。

在这一节中，我们将介绍 FileZilla 中显示的所有常见错误，并指导您完成解决这些错误的步骤。

### 致命错误:操作超时

“操作超时”错误的发生有多种原因。由于大写的红色“致命错误”消息，它看起来很严重，但通常情况下，有一个快速修复方法。

![Example of an “Operation Timed Out” error.](img/74a87b1b82bd10367f28c523c67033f9.png)

Example of an “Operation Timed Out” error.



首先，操作超时往往与你打错了无关。事实上，当您有一段时间没有使用 FileZilla 时，也会出现此错误。因此，出于安全目的，该应用程序只是将客户端与服务器断开连接。

在这种情况下，回到**站点管理器**再次点击**连接**按钮。只要以前的 FTP 凭证仍然正确，这应该会建立一个新的连接。

请注意，由于不正确的用户凭据或不可靠的连接，可能会出现超时错误。确保您仔细检查登录凭证的准确性。

如果这不是问题，可能是您的互联网连接不稳定，或者您的主机服务器有一些限制连接速度的限制。在这些情况下，您可以延长**超时**设置，给 FileZilla 更多的时间来建立连接。

进入 **FileZilla >设置**完成该过程。

![Go to the Settings page to extend the Timeout defaults.](img/f10245dc9c84b956058cfee4a99e5a7c.png)

Go to the Settings page to extend the Timeout defaults.



在新窗口中，转到**连接**选项卡。找到以秒为单位的**超时**字段，给 FileZilla 更多的时间来处理连接。您还可以调整重试次数，看看是否有帮助。

![Add a higher number to the field called Timeout in Seconds.](img/c43edc9ebbccd9c8ee4a6acdbb68a537.png)

Add a higher number to the field called Timeout in Seconds.



### 错误:目录列表被用户中止

FileZilla 的一个错误是“目录列表被用户中止”。

虽然这可能是由于超时问题而出现的，但更有可能的是，您选择中止连接，以便重新打开过去的连接或链接到新站点。当您试图导航到一个书签时，这种情况也很常见。

这没什么大不了的。您可以继续您建立的新连接，或者您可以考虑返回到**站点管理器**重新连接到以前的站点或连接。

![Example of the “Directory Listing Aborted By User” error.](img/687f69ca36f2b0c32f1399c4c52f7351.png)

“目录列表被用户中止”错误的例子。



T6】

### 错误:无法建立到 SFTP 服务器的 FTP 连接:请选择正确的协议

FileZilla 显示“无法连接到服务器”错误，这是告诉您连接失败的一种宽泛方式。所以，你可能会因为很多原因看到这一点。

从寻找更具体的错误开始，为您提供“无法连接到服务器”错误的实际原因的线索。

例如，“请选择正确的协议”消息表明您可能输入了正确的凭证，但使用了错误的协议。对于那些试图通过 **Quickconnect** 模块经由 SFTP 连接的人来说，这是很常见的。

![Some errors say that you're using the wrong protocol.](img/3b3f716cf8872a57897318d41c92f2b1.png)

Some errors say that you’re using the wrong protocol.



我们知道，默认情况下，**快速连接**按钮只允许使用标准 FTP。因此，你必须进入**站点管理器**来调整服务器或你的托管公司使用的协议。

![Changing protocols in the Site Manager often solves the problem.](img/4c79ae5d1b94de65c7f8e275c825eef1.png)

Changing protocols in the Site Manager often solves the problem.



### 错误:验证失败

“验证失败”错误告诉您，您键入了错误的用户名或密码来建立连接。

![Example of an “Authentication Failed” error.](img/a3594a058184a0da992eb4b67d0cf229.png)

Example of an “Authentication Failed” error.



要解决此问题，请尝试再次键入它们，或者复制并粘贴它们以保持准确性。

如果您仍然有问题，请联系服务器的所有者，如您的托管公司，解释您的 FTP 登录凭据不起作用。

### 各种主机和端口错误

键入错误的**主机 ID** 或**端口**会导致相同的错误信息。您会收到“连接超时”消息，然后出现“无法连接到服务器”错误。

这些是相当通用的，可能意味着一些事情，但是你知道当 FileZilla 用一个响应和命令结束消息传递时，这是一个**主机 ID** 或**端口**问题。它基本上是在说“这是我们尝试过的，但没有成功。可能您输入了错误的主机或端口。”

![Response and Command messages usually appear when you have an inaccurate Host or Port credential.](img/266e0179f0c6ce7a1a4bb762d5026de7.png)

Response and Command messages usually appear when you have an inaccurate Host or Port credential.



这个问题的解决方案很简单:再次检查您是否正确地输入了这两个问题。您可以复制并粘贴它们，以消除人为错误的可能性。最后，如果你仍然有问题，联系你的主人。

### 配置不正确的服务器

有时，FileZilla 可能会共享一个关于“空闲连接”或“超时”的错误。这通常意味着在本地计算机和远程站点之间的某个地方有一个配置不正确的服务器。

如果麻烦的服务器是你的，那是你自己的问题。然而，大多数用户并不是服务器的所有者，所以您对这种情况没有多少控制权。

你可以试着联系服务器所有者，看看他们是否能帮忙。

或者，您可以选择在 FileZilla 中进行调整来暂时修复这个问题。

要试一试，请到主菜单中的**编辑>设置**。

![Go to Edit > Settings.](img/4bbb2d4621be352aa5c092355f60335e.png)

Go to Edit > Settings.



点击**连接> FTP** ，然后定位 **FTP 保活**部分，勾选复选框**发送 FTP 保活命令**。

正如 FileZilla 自己提到的，您不应该经常使用它。这里的问题是服务器配置不正确，所以最好联系服务器管理员来弄清楚发生了什么。

话虽如此，如果你没有时间等待管理员，我们喜欢这种解决方案。

![Utilize the FTP Keep-alive setting to temporarily resolve a server issue.](img/be3401c2f563cc95bd97f7dc69b756ba.png)

Utilize the FTP Keep-alive setting to temporarily resolve a server issue.



## FileZilla 客户端与 FileZilla 服务器

一个关于 FileZilla 的常见问题通常会在用户下载该软件之前出现。这是因为 FileZilla 网站提供了两个**下载**按钮:一个用于 FileZilla 客户端，另一个用于 FileZilla 服务器。

两者有什么区别？

FileZilla 指出，如果你想传输文件，你应该“选择客户端”。如果您想让其他人也可以使用文件，请获取服务器。

![The FileZilla website had two download options for the FileZilla Client and the FileZilla Server.](img/df66982c0cb503023d629c4849be9280.png)

The FileZilla website had two download options for the FileZilla Client and the FileZilla Server.



这有点含糊不清，所以让我们更仔细地看看这两者。

### FileZilla 客户端

*   FileZilla 客户端允许用户向/从 FTP 服务器上传和下载文件。为了来回移动文件，需要在服务器和本地机器(客户机)之间建立连接。
*   多个 FileZilla 客户机可以链接到一个 FileZilla 服务器，以便从服务器检索文件。您也可以使用客户端来连接远程 FTP 服务器，例如托管您的网站的服务器。
*   您可以在 Windows、Linux 和 Mac 计算机上安装 FileZilla 客户端。
*   客户端启动所有传输。此外，客户端可以连接到无限数量的 FTP 服务器。

### FileZilla 服务器

FileZilla 服务器提供了一些您可能想要利用的附加特性:

*   FileZilla 服务器为您提供了一种在本地计算机上托管文件集合的方式。
*   它是 FTP 客户端用户随时从该计算机检索文件的集中位置。他们还可以向服务器发送文件。
*   FileZilla 服务器只能在 Windows 电脑上运行。
*   服务器无法启动传输。它作为一个存储工具，与发起传输的 FileZilla 客户机协同工作。您不能将一台服务器连接到另一台服务器。它只允许来自客户端的向内连接。

总的来说，FileZilla 客户端和 FileZilla 服务器之间的连接类似于 Dropbox 或 Google Drive 等云存储应用程序。然而，访问模式、安全措施和总体成本都完全不同。

最明显的区别是通过 FTP 传输文件需要客户机和服务器，就像 FileZilla 的客户机和服务器一样。云存储只需要一个 web 浏览器或一个应用程序来访问云文件。

## 免费 FileZilla vs FileZilla Pro

FileZilla 的免费版本拥有你需要的大部分功能。这是它如此受欢迎的原因之一。

然而，也有一个付费的升级版本，叫做 FileZilla Pro。

这个 FTP 客户端的专业版需要支付很少的费用，但它增加了几个高级功能，对高级用户来说可能会很方便。

让我们来看看这两个版本是如何相互叠加的。

### FileZilla(免费)

FileZilla 客户端的常规版本面向所有需要 FTP 功能的用户，包括个人和专业用户。功能列表很长，大多数用户从免费版本中获得他们需要的东西应该没有问题。

以下是我们可以期待的:

*   支持多种传输协议，如 FTPS、FTP 和 SFTP
*   Mac OS X、Linux 和 Windows 版本的跨平台使用
*   使用规则和参数定位文件的远程文件搜索
*   书签可以帮助您直接进入文件目录中的各个部分，而不是每次都要四处寻找
*   支持多种语言
*   高速传输大文件
*   比较两个站点目录的目录浏览配置
*   远程文件编辑，这样当文档需要编辑时，您不必重新上传文档
*   基于文件名、文件大小或其他参数缩小搜索范围的过滤工具
*   将文件从一个站点移动到另一个站点的拖放界面。拖放允许你点击一个按钮来上传或下载文件。
*   一个**快速连接**按钮，用于使用正确的凭证立即建立 FTP 连接
*   一个**站点管理器**模块，帮助你建立更安全的连接，添加多个站点，并处理像书签这样的事情
*   用于配置文件传输速度的选项
*   带有快捷键的选项卡式用户界面，用于重新组织和隐藏某些模块，以提供更加友好的用户体验

### FileZilla Pro(档案 Zilla Pro)

如前所述，免费的 FileZilla 客户端对大多数用户都有意义。然而， [Pro 版本](https://filezillapro.com/)中可能有一两个功能可以让您的工作流程更简单。

FileZilla Pro 主要通过添加对云存储选项的支持来迎合专业用户。我们认为，如果你对云传输感兴趣，这些对非专业用户也有帮助。

FileZilla Pro 包含了 FileZilla 免费版的所有内容。除此之外，您还将获得对以下云存储服务和协议的支持:

*   亚马逊 S3
*   B2 服务中心
*   Dropbox
*   来自微软的 OneDrive
*   微软 Azure 的文件存储服务
*   微软 Azure 的 Blob 存储服务
*   谷歌云存储
*   Google Drive
*   OpenStack Swift 存储
*   箱子
*   WebDAV
*   任何使用亚马逊 S3 的第三方提供商

还有一个名为 FileZilla Pro + CLI 的可下载版本，用于使用命令行界面和运行批量传输。这对于那些习惯于通过 CLI 命令工作的人来说很方便，比如[开发人员和工程师](https://kinsta.com/blog/wordpress-developer-salary/)。
[无论你是初学者还是有经验的 FileZilla 用户，本指南都将帮助你提高技能💪 点击推文](https://twitter.com/intent/tweet?url=https%3A%2F%2Fkinsta.com%2Fblog%2Fhow-to-use-filezilla%2F&via=kinsta&text=Whether+you%27re+a+beginner+or+an+experienced+FileZilla+user%2C+this+guide+will+help+you+level+up+your+skills+%F0%9F%92%AA&hashtags=FTP%2CSSL)

## 摘要

学习如何使用 FileZilla 只需要一点时间，但是还有许多其他有用的特性可以帮助您将文件传输管理提升到一个新的水平。虽然不像当今市场上的其他 FTP 客户端那样现代，但 FileZilla 以其可靠性、速度和传输文件、制作书签和修改文件的广泛功能弥补了这一点。

现在轮到你了:你用过 FileZilla 吗？你喜欢它什么，不喜欢它什么？请在评论区告诉我们！

* * *

让你所有的[应用程序](https://kinsta.com/application-hosting/)、[数据库](https://kinsta.com/database-hosting/)和 [WordPress 网站](https://kinsta.com/wordpress-hosting/)在线并在一个屋檐下。我们功能丰富的高性能云平台包括:

*   在 MyKinsta 仪表盘中轻松设置和管理
*   24/7 专家支持
*   最好的谷歌云平台硬件和网络，由 Kubernetes 提供最大的可扩展性
*   面向速度和安全性的企业级 Cloudflare 集成
*   全球受众覆盖全球多达 35 个数据中心和 275 多个 pop

在第一个月使用托管的[应用程序或托管](https://kinsta.com/application-hosting/)的[数据库，您可以享受 20 美元的优惠，亲自测试一下。探索我们的](https://kinsta.com/database-hosting/)[计划](https://kinsta.com/plans/)或[与销售人员交谈](https://kinsta.com/contact-us/)以找到最适合您的方式。