## 虚拟机安装redhat操作系统环境配置

### 配置环境：

* 最低内存4G I5以上CPU

* 建议内存8G I7CPU 硬盘SSD

### 一.安装VMware Fusion以及安装操作系统

* 1.自定义分区

* 2.Linux->Red Hat Enterprise Linux7

* 3.继续

* 4.继续

* 5.自定义设置

* 6.起名

* 7.选内存建议4G cpu->4个处理器1个核心（处理器越多性能越好）

* 8.内存（图形化至少得1G内存才能运行）建议选4G仅主机

* 9.磁盘类型选SCSI(S)

 硬盘类型：IDE-SATA(A)-SCSI(S)-SAS-SSD 机械硬盘几乎没有使用寿命（`硬盘怕静电`）

         SSD前面的都叫机械硬盘（性能绝大部分取决于它的转数）

         SAS就是串行的SCSI

         SCSI已经很少有人用了，性能低，价格贵

         IDE就是ATA盘

         SATA就是串行的ADE硬盘（笔记本一般用的都是这个5400转）转数在5400-7200之间

* 10.磁盘容量100G+ 并选将磁盘存储为单个文件，可移植性好（可以直接拷贝）

* 11.会生成vmdk文件（磁盘文件）

* 12.自定义硬件：删除声卡，删除打印机，处理器（打开第二个），光驱选外部存储iso镜像（）

* 13.编辑虚拟机设置，再添加一块2.5T（2560）的硬盘，创建新的磁盘，存储为单个文件
   
 ## 开机后设置
 
 
 * 安装完之后先用root登陆 进行一些配置
 
 1.语言选英文
 
 2.DATE & TIME(在中国地图上选一个时区)
 
 3.`software selection`->选 server with GUI（图形用户界面(Graphical User Interface    CLI命令行界面(Command Line Interface))
 
 4. INSTALLATION DESTINATION (硬盘的分区选项)->选100G的那个-> i will configure partitioning->standard partition(不要选`LVM`)->添加 /和20G点击添加挂载点->done->接收
 
 5.network and hostname ->起名按照域名的方式 例如rhel7-0.redhat.com->选择网络->选configer->ipv4 Settings(method:automatic(DHCP)自动获取)->general->选第一个自动连接到网络
 
 6.设置管理员密码，五以上的版本必须有一个普通用户
 
 * 2.打开terminal

<pre> mount /dev/sr0 /mnt

 yum-config-manager --add-repo=file:///mnt

 echo "gpgcheck=0">> /etc/yum.repos.d/mnt.repo</pre>

* 3.关机然后做一个快照 防止毁坏
