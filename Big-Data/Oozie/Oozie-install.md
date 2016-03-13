


### 安装记录
---

#### 主要参考
1. [ Oozie4.2.0配置安装实战 ](http://blog.csdn.net/fansy1990/article/details/50570518)
2. [oozie 安装过程总结](https://segmentfault.com/a/1190000002738484)
3. [oozie构建和安装](https://www.zybuluo.com/xtccc/note/269190#13-%E5%8A%A0%E5%85%A5%E6%89%80%E9%9C%80%E7%9A%84%E7%AC%AC%E4%B8%89%E6%96%B9jar%E5%8C%85)
4. [Oozie4.2安装笔记](https://github.com/clark010/wiki/wiki/Oozie4.2%E5%AE%89%E8%A3%85%E7%AC%94%E8%AE%B0)

#### 安装注意点

+ 编译Oozie4.2.0时
    + ~~修改maven setting.xml ，使用开源中国的库~~，此步不需要
    + 按自己的版本设置pom.xml中各软件的版本，或编译时加上相应参数，如`bin/mkdistro.sh -DskipTests -Phadoop-2 -Dhadoop.auth.version=2.6.0 -Ddistcp.version=2.6.0 -Dspark.version=1.4.1 -Dpig.version=0.15.0 -Dtomcat.version=7.0.59`（tomcat使用系统自带版本）。上述操作最好都做。
    + 若编译出错时，考虑切换到root执行上述命令
    + 需要注释掉pom中的对`http://repository.codehaus.org/` maven库的依赖
+ 启动前的初始化
修改oozie-4.2.0/oozie-server/conf/server.xml文件，注释掉该记录：`<!--<Listener className="org.apache.catalina.mbeans.ServerLifecycleListener" />-->`

#### 其它参考

1. [Oozie4.2 安装部署、以及example测试 ](http://blog.csdn.net/u014729236/article/details/47188631)
2. [oozie 4.0.0 on hadoop2.4.1安装笔记（完整版）](http://www.qkeye.com/blog-51-424604.html)
3. [Oozie-3.3.2安装配置运行实践](http://ju.outofmemory.cn/entry/65688)

----
[↑ 返回上级](https://github.com/asin929/linux-software/blob/master/Big-Data/Big-Data.md)

[← 返回首页](https://github.com/asin929/linux-software)
