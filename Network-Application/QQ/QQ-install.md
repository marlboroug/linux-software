
----
## 一、QQ2012国际版
QQ2012国际版是linux下使用qq最好的解决方案了。

### **安装步骤**

1. 安装依赖包

        sudo yum install freetype.i686 libpng.i686 libgcc.i686 libXau.i686

 之后，可通过源码或rpm包安装QQ2012，如下所示

2. rpm包安装
在[Fedora Zh User Group repository](http://repo.fdzh.org/FZUG/nonfree/21/x86_64/)，下载“wine-qqintl-0.1.3-2.net.x86_64.rpm”后直接点击安装即可。

3.   源码安装

    下载[wine-2012qq国际版](http://pan.baidu.com/s/1pKchCvh)后，解压并执行

        unzip wine-qqintl.zip
        cd wine-qqintl
        ar vx wine-qqintl_0.1.3-2_i386.deb
        sudo tar -zxvf data.tar.gz -C /
        wine-qqintl

### **效果**
功能挺全，与Windows下差别不大。

![qq2012国际版](http://img.blog.csdn.net/20160129114822054)

### 存在的问题
+ 无法听到新消息的声音提醒
+ 切换到其它工作区时，qq界面消失并无法还原。如果电脑配备了多个显示屏的话，可以将qq放到其它的显示屏上，这样即使切换工作区qq界面也不会消失。

貌似这是qq在linux下的常见问题，见[wine qq 2013 for linux Ubuntu 64位兼容](http://www.longene.org/forum/viewtopic.php?t=4700)，上述文章同时也讲述了安装qq 2013、2012的方法。


----

## 二、pidgin-lwqq

### **安装步骤**
安装的过程主要分两部分，安装[lwqq](https://github.com/xiehuc/lwqq)和[pidgin-lwqq](https://github.com/xiehuc/pidgin-lwqq)．

当时主要参考的是github上的安装步骤，不过安装pidgin-lwqq时，没找到已经安装的lwqq，这时可以尝试着按以下方法解决：

1. 修改安装路径或修改.xprofile文件

		需要注意,可以使用 cmake .. -DCMAKE_INSTALL_PREFIX=/usr 来指定安装到/usr 目录下.或者在 ~/.xprofile 文件中加入 export LD_LIBRARY_PATH=/usr/local/lib:$LD_LIBRARY_PATH 才能在桌面(如pidgin)中加载 liblwqq.so成功
2. 方法１不行的话就重启一下，还不行的话就把配置写到/etc/profile里
3. 方法２不行的话，就尝试着添加如下配置

		export PKG_CONFIG_PATH=$PKG_CONFIG_PATH:/home/user/lwqq-master/build

---
### **使用gnome集成聊天和推荐插件**

lwqq配合着以上扩展使用，可以实现消息通知，屏幕截图，存储聊天记录等功能．

---
### **最近更新**

pidgin-lwqq的本质是基于webqq的，最近webqq的登录改为了只能由手机扫码来登了，也就意味着pidgin-lwqq已经不能用了．


---
## 三、其它方案：

+ [webqq](http://w.qq.com/):缺点是不够稳定，很容易崩，也不能发送图片，可以配合着微云，通过分享链接来解决。
+ 虚拟机+qq：可以安装Xen/KVM/VMWare/Virtual Box的Windows虚拟机，在上面装上qq，虽然有点杀鸡用牛刀的感觉，不过也算是一个比较好的解决方案，很多人都是这么干的。
+ [tox](https://github.com/irungentoo/toxcore)

---
## 四、参考

1. [Fedora 21 安装QQ国际版](http://www.cnblogs.com/inthedark/p/4428206.html)


----
[↑ 返回上级](https://github.com/asin929/linux-software/blob/master/Network-Application/Network-Application.md)

[← 返回首页](https://github.com/asin929/linux-software)
