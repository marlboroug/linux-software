



# phpLDAPadmin安装记录
+ 源码方式安装

    [CentOS部署OpenLDAP认证之 phpldapadmin](http://share.blog.51cto.com/278008/821807)
[openldap+phpldapadmin](http://m.oschina.net/blog/338362)

+ yum方式安装

    [Centos6 yum安装openldap+phpldapadmin+TLS+双主配置](http://54im.com/openldap/centos-6-yum-install-openldap-phpldapadmin-tls-%E5%8F%8C%E4%B8%BB%E9%85%8D%E7%BD%AE.html#phpldapadmin)

**本机采用yum方式安装，尝试使用源码方式安装失败，与SElinux有关。考虑到配置方式通用，故参考[CentOS部署OpenLDAP认证之 phpldapadmin](http://share.blog.51cto.com/278008/821807)进行配置，具体步骤为：修改`/etc/phpldapadmin/config.php`文件，注释掉相应部分即可。**

----
[↑ 返回上级](https://github.com/asin929/linux-software/blob/master/Program-Software/Program-Software.md)

[← 返回首页](https://github.com/asin929/linux-software)
