   Foreman是一个集成的数据中心生命周期管理工具，提供了服务开通，配置管理以及报告 功能，和Puppet Dahboard一样，Foreman也是一个Ruby on Rails程序。Foreman和 Dashboard不同的地方是在于，Foreman更多的关注服务开通和管理数据中心的能力，例如和引导工具，PXE启动服务器，DHCP服务器及服务器开通工具进行集成。
Foreman 机器统一管理平台：

  1. Foreman可以与Puppet集成使用,通常是作为puppet的前端接入。

  2. Foreman takes care of provisioning until the point puppet is running, allowing Puppet to do what it does best.

  3. Foreman能够通过Facter组件显示系统目录信息，并且可以从Puppet主机报表中提供实时信息。

  4. Foreman能够准备你管理新机器的所有工作。它的设计目标是能够自动化的完成所有手工管理的工作，通过Foreman可以重新配置机器。

  5. Foreman能够管理大规模(当然也包括小规模)的，企业级的的网络，可能有很多域，子网和很多puppet master节点。Foreman也可以实现配置版本的回溯。
