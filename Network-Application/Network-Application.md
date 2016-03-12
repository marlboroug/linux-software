

# 目录

- [网页浏览器](#网页浏览器)
- [文本界面的网页浏览器](#文本界面的网页浏览器)
- [聊天软件](#聊天软件)
- [Email 客户端](#Email 客户端)
- [下载工具](#下载工具)
- [文件传输](#文件传输)
- [FTP客户端](#FTP客户端)


---
# 网页浏览器


|软件|简介|安装配置|星级|详情|注释|
|---|---|---|---|---|---|
|Firefox|Linux下最广泛使用的浏览器|[Firefox-install](https://github.com/asin929/linux-software/blob/master/Network-Application/Firefox/Firefox-install.md)|★★★★☆| [Firefox详情](https://github.com/asin929/linux-software/blob/master/Network-Application/Firefox/Firefox.md) |[Firefox插件汇总](https://github.com/asin929/linux-software/blob/master/Network-Application/Firefox/Firefox-addons.md)
|Chrome |一款成熟且有发展前景的浏览器|TODO|★★★★☆|TODO|TODO|
|Konqueror| Web浏览器+文件浏览器|---|★★★☆☆|---|---|
|Opera|---|---|★★★☆☆|---|---|
|Seamonkey|---|---|★★★☆☆|---|---|
|Conkeror|---|---|★★★☆☆|---|---|
|Orphne|---|---|★★★☆☆|---|---|
|dillo|---|---|★★★☆☆|---|---|


----
[↑ 返回上级](https://github.com/asin929/linux-software)

[← 返回首页](https://github.com/asin929/linux-software)









---
# 文本界面的网页浏览器

## 工具

文本浏览器我平时用的很少。如果用也只是用w3m。w3m是一个成熟、稳定且强大的命令行web浏览器，在各个发行版上都能稳定的运行。其实命令行的浏览器，用习惯了都差不多。w3m对中文的支持应该是最好的。elinks和links对中文支持都没w3m那么好。

比较有名的应该就是w3m, lynx了，elinks也不错。当然还有其它的比如links, links2等

## 选择

w3m >lynx > elinks >links2 > links

---
# 聊天软件

## 工具

因为我平时主要通过QQ，IRC和Skype聊天，所以这里只介绍QQ，IRC和Skype相关的客户端软件。IRC的客户端软件其实有很多，功能都差不多，所以找个界面舒服、功能多、稳定的客户端就可以了。至于QQ，在Linux中用的最多，最好用的还是Webqq。至于腾讯发布的QQ for Linux(linuxqq), 大家还是忘了它吧。Skype客户端就一个，那就是Skype。

**Xchat**

Xchat是非常流行的IRC客户端，利用它你可以登陆到任何的IRC服务器和别人交流! xchat运行在X11环境下，有着良好的用户界面，和许多聊天所需要的功能，例如私聊、支持多个聊天室等等。总的来说Xchat给我的印象就是非常稳定和简洁，功能能满足我基本的需要，所以我基本用Xchat作为我的IRC客户端。

**Pidgin**

Pidgin(原名：Gaim)是一款IM即时通讯软件，支持除qq外几乎所有IM软件。功能很强大，界面友好，也稳定。它还拥有不少独特的功能。最流行 的要算是好友提醒功能了，当某个特定的好友离开或者脱机，它会用某种方式对你进行提醒，比如发送消息、播放声音甚至运行某个程序。所以如果不喜欢xchat，pidgin是个不错的选择。

**Empathy**

从Empathy的功能描述来看，比较吸引人的特性包括：支持多协议，语音/视频支持，以及强调协作等方面。

**WeeChat**

WeeChat是个基于终端的快速的轻量级IRC客户端，可以在多种操作系统中运行。所有的东西都能用键盘完成，而且可以自定义。看它的官方文档貌似很不错，如果大家喜欢在终端下使用IRC的话可以尝试下WeeChat, 当然还有其它能够运行在终端中的IRC客户端，但是貌似都没有WeeChat好用。

**ERC**

ERC是Emacs的一个插件，可以作为IRC客户端用，所有的操作都是用Emacs快捷键来完成的，非常不错，我基本上都是用ERC在freenode中聊天的。Emacs控一定要尝试下。

**Firefox/Thunderbird IRC插件**

Firefox/Thunderbird中也有一些插件可以作为IRC客户端，但都不好用，主要是有新消息来了，不太容易注意到。

**Webqq**

如果想在Linux下用QQ，Webqq是最理想的选择，虽然有些功能还不支持，但是绝大部分的聊天功能都支持的很好，最重要的是稳定。目前腾讯还在积极开发Webqq，以后的Webqq用起来会更舒服。

**QQ for Linux**

腾讯官方出的Linux版QQ，功能有限，Bug多，很久没更新了，腾讯也放弃了对它的支持，所以基本上可以说这款软件是废了。

**Wine**

相信想在Linux下跑QQ的童鞋都想过或者尝试过这种方法，当然我也尝试过，给我的感觉是中文支持不好，界面不好，Bug很多，有些功能还不支持，所以不推荐用这种方式来用QQ。

**在虚拟机中用QQ**

虽然说小题大做，但是不得不说效果非常不错。大家可以起一个Xen/KVM/VMWare/Virtual Box的Windows虚拟机，在里面装上QQ，使用起来跟在物理机上Windows系统中运行的QQ效果完全一样。

**Skype**

Skype是微软的一个聊天工具，有Windows和Linux两个版本，Linux版本的Skype功能强大，简洁，稳定。Skype也是我最喜欢的聊天工具，它的目的很明确就一聊天工具。Skype还支持视频聊天，效果不错。QQ我是越来越讨厌了，腾讯出于商业目的绑定了很多非聊天的功能，把QQ搞的异常臃肿，也是无奈。另外说下微软现在也在大力推广Skype，所以Skype还是很有前景的。

## 其它

**Kopete**

Kopete是KDE的一个子项目，支持多协议的即时通信，包括ICQ、AIM、Gadu-Gadu、IRC、.NET Messenger Service、Yahoo! Messenger等协议。

## 选择

关于qq，详见[ linux下使用qq ](http://blog.csdn.net/u012948976/article/details/49330825)。

IRC客户端： pidgin &gt; xchat &gt; empathy &gt; WeeChat &gt; ERC &gt; Firefox/Thunderbird IRC插件

QQ客户端： Webqq

Skype客户端： Skype

---
# Email 客户端

## 工具

Linux下的邮件客户端有很多，还有一些是适用于不同桌面环境的，比如KDE下的KMail, GNOME下的Evolution。在众多的邮件客户端中最好用的当属Thunderbird和mutt了。

**Thunderbird**

Thunderbird是由Mozilla浏览器的邮件功能部件所改造的邮件工具。应该是目前Linux系统下应用最多，功能最强大，稳定性很好的邮件客户端了，支持垃圾邮件过滤、反“钓鱼”欺诈、高级安全等，可进行个性化配置。这个是我目前的第一选择。

**mutt**

Mutt 是一个很小型但功能强大的，使用文本界面的MIME邮件客户端，Mutt具有高可配置的特性，适合高级邮件用户使用。喜欢在终端下管理邮件童鞋的首选。

## 其它

Gmail

Kmail

## 选择

命令行： mutt

图形界面： Thunderbird


---
# 下载工具

下载工具很多，没有什么好不好的，看个人喜好。这里推荐几个常用的。

## BT下载工具

**kTorrent**

KTorrent是KDE下的一款BT下载工具，具有速度快而内存占用小的优点，设置也比较简单实用，感觉和Windows下的uTorrent不相上下。

**rtorrent**

一个Linux下控制台的BT客户端程序。

## 非BT下载工具

**wget**

wget默认在各Linux发行版都有安装，成熟稳定，方便。我一般用这个来进行下载。

**axel**

Axel通过打开多个HTTP/FTP连接来将一个文件进行分段下载，从而达到加速下载的目的。对于下载大文件，该工具将特别有用。这个工具主要特点是速度快。是一款非常不错的下载工具。

**curl**

它是对libcurl库的一个命令行工具包装。libcurl库中提供了相应功能的API，可以在程序中调用。curl使用URL的语法来传输文件，它支持FTP, FTPS, HTTP, HTTPS, TFTP, SFTP, TELNET等多种协议。curl功能强大，它提供了包括代理支持，用户认证，FTP上载，HTTP post，SSL连接，文件续传等许多特性。

## 选择

BT下载工具：kTorrent和rtorrent都不错，主要看个人喜好。

非BT下载工具：wget和curl的选择，主要看什么场景，一般的下载用wget, 主要是操作简单。如果需要用到特殊协议可以选择curl。如果想要下载速度那么就用axel.

[curl和wget的比较](http://www.cnblogs.com/kudosharry/articles/2335880.html)

---
# 文件传输

## 工具

**rsync**

rsync是一款高效的远程数据备份和镜象工具，可快速地同步多台主机间的文件。rsync功能非常强大，经常被用作企业级的数据备份。rsync更适用于大数据量的每日同步，当然也可以用来进行简单的文件传输，但没有scp命令简洁。

**scp**

scp命令是SSH中最方便有用的命令了，scp就是secure copy，是用来进行远程文件拷贝的。数据传输使用ssh，并且和ssh使用相同的认证方式，提供相同的安全保证。这个是Linux下最常用的文件传输工具。

**rcp**

rcp不是一种安全的的传输文件的方式，rcp通过rsh来执行远程命令，要使用rcp必须经过一些配置，现在rcp已经被scp取代了，常用scp来进行文件传输。

## 选择

如果是传输简单的文件： scp &gt; rsync &gt; rcp

如果是用来做数据备份: rsync


---
# FTP客户端

## 工具

**lftp**

比ftp好用，支持TAB自动补全。功能全，稳定。可作为首选的FTP客户端。

**ftp**

在命令行中ftp命令够资格，很实在。但是它不支持TAB自动补齐，这很让人头大。功能也没有lftp强。

**FileZilla**

图形界面的FTP客户端。支持Linux和Windows平台。个人感觉是最好用的图形界面FTP客户端

## 选择

命令行： lftp &gt; ftp

图形界面: FileZilla
