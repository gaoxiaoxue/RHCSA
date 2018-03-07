## 虚拟机安装redhat操作系统环境配置

### 配置环境：

* 最低内存4G I5以上CPU

* 建议内存8G I7CPU 硬盘SSD

### 一.安装VMware Fusion

* 1.自定义分区

* 2.Linux->Red Hat Enterprise Linux7

* 3.继续

* 4.继续

* 5.自定义设置

* 6.起名

* 7.选内存建议4G cpu->4个处理器核心

### 二.安装操作系统

* 1.CD/DVD

* 2.选择安装的镜像

* 4.安装完之后先用root登陆 进行一些配置

* 打开terminal

<pre> mount /dev/sr0 /mnt

 yum-config-manager --add-repo=file:///mnt

 echo "gpgcheck=0">> /etc/yum.repos.d/mnt.repo</pre>

* 5.关机然后做一个快照 防止毁坏
