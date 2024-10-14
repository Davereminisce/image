# Vmware的Linux虚拟机安装以及与vscode的远程连接

## 1.Vmware的下载

点击下面的链接进行下载（夸克网盘）

[网盘分享链接](https://pan.quark.cn/s/b3e13befc19f#/list/share)

#### 1.1 ![image-20241008131347356](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008131347356.png)

这两个版本下哪个都可以，这里我们下载17.6版的。

#### 1.2![image-20241008131622075](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008131622075.png)

进入下载目录，点击这个exe安装文件，接下来进行安装工作

## 2.Vmware的安装

#### 2.1 安装前的工作

##### 2.1.1 先找一个空间充足的盘创建Vmware的目录

#### ![image-20241008132946975](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008132946975.png)

为了便于查找我们直接起名为VmWare

##### 2.1.2 在刚才创建的文件夹里创建vmware的安装目录和虚拟机的存放目录（*非常重要！！！*）

![image-20241008133049621](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008133049621.png)

为了区别于主目录我们将Vmware中的W小写  

**到此前期准备工作已经全部完成**

#### 2.2 安装

点击这个exe安装文件

![image-20241008131622075](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008131622075.png)

若是弹出是否允许该程序对你的计算机进行更改，选择是，若无效可以右键该程序选择以管理员身份运行



![image-20241008133659115](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008133659115.png)

选择下一步



![image-20241008133739679](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008133739679.png)

选择接受协议  选择下一步



![image-20241008133828126](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008133828126.png)

注意 一定要选择更改下载路径  **不要下在C盘！！不要下在C盘！！不要下在C盘！！**

*（建议所有的软件都下载在C盘以外的磁盘并且自己做好分类，这在电脑使用后期会为你节省许多功夫！）*



![image-20241008134148129](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134148129.png)

安装地址就选择我们先前已经新建的安装目录，之后选择确定

![image-20241008134315300](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134315300.png)

![image-20241008134356198](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134356198.png)

取消勾选*启动时检查产品更新*和*加入VMware可以体验提升计划*之后选择下一步

![image-20241008134512468](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134512468.png)

此处可自己按需选择

![image-20241008134540769](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134540769.png)

点击安装，等待安装完成。

![image-20241008134736358](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134736358.png)

安装完成点击许可证

![image-20241008134812500](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134812500.png)

我使用的密钥   MU29H-8KKEK-4J8D9-11C7P-ALUQF  若失效的话就自己去网上搜索，挺容易搜到的

  ![image-20241008134953471](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008134953471.png)

点击输入

![image-20241008135021084](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008135021084.png)

点击完成，安装部分就圆满完成了。

若在安装过程中粗心未输入密钥，则可以打开vmware点击  ***帮助***

![image-20241008135248665](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008135248665.png)

![image-20241008135308742](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008135308742.png)

![image-20241008135346163](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008135346163.png)

在这里重新输入就可以，至此安装工作就全部完成了。

### 3.修改创建的虚拟机的默认存放位置



由于vmware的虚拟机默认存放位置是在C盘，所以我们要手动将其默认位置调整为我们最初创建的虚拟机文件储存文件夹

![image-20241008140041765](https://raw.githubusercontent.com/Imagineer233/image/main/undefinedimage-20241008140041765.png)

选择 编辑  首选项

![image-20241008140129656](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008140129656.png)

![image-20241008140200056](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008140200056.png)

此处选择我们最初建的文件夹VMwareData

![image-20241008140241542](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008140241542.png)

点击确定  大功告成！以后的虚拟机都会安装到这个文件夹了，方便后期进行管理和调整。

## 4.Linux虚拟机的安装

#### 4.1 下载 Ubuntu 下载地址 [清华大学镜像站](https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/22.04.4/)

![image-20241008145604208](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008145604208.png)

点击下载镜像

***Vmware的一系列操作***

![image-20241008202944153](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008202944153.png)

![image-20241008203040302](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008203040302.png)

![image-20241008203247663](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008203247663.png)

选择我们刚才下载的镜像地址

![image-20241008203420386](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008203420386.png)

自主填写

![image-20241008203513705](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008203513705.png)

建议为虚拟机单独弄一个文件夹，我们之前已经设置过默认储存位置，所以这一步只需要调整自己的虚拟机名称

![image-20241008203822973](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008203822973.png)

最大磁盘大小可以给40-50g，这并不是说设置之后电脑会直接少50g，而是虚拟机中用了多少电脑内存会少多少。

![image-20241008204752265](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008204752265.png)

等待虚拟机开机

![image-20241008205136836](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008205136836.png)

选择中文键盘，汉语拼音

![image-20241008205345456](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008205345456.png)

选择最小安装，选择安装Ubuntu是下载更新。之后点击continue等待

![image-20241008205524149](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008205524149.png)

选择清除磁盘并安装Ubuntu，之后点击Istall Now。

![image-20241008205807830](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008205807830.png)

where are you 选择上海即可，之后点击continue

![image-20241008205946550](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008205946550.png)

填写你的信息，之后点击continue等待安装完成，安装完之后点击restart重启虚拟机，

![image-20241008211630726](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008211630726.png)

输入密码后即可进入虚拟机。至此，虚拟机已经全部安装完成。

## 5.通过remote-ssh远程连接虚拟机

#### 5.1 前言

通过vmware上启动虚拟机进行开发会占用一部分电脑资源，并且虚拟机的UI界面比较简单，大大降低了开发效率，我们可以使用vscode的插件remote-ssh来远程链接虚拟机，在本地进行虚拟机上的开发，非常方便。

#### 5.2 Linux安装openssh-server

我们用的是Ubuntu，所以这里只对于Ubuntu进行安装

第一步  打开终端

![image-20241008213729024](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008213729024.png)

![image-20241008213823644](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008213823644.png)

在终端中输入以下代码：

`sudo apt-get remove openssh-server      # 先卸载，无论咋样都先做一下，以免出现问题
sudo apt-get install openssh-server     # 安装
sudo service ssh --full-restart     # 重启ssh 服务
sudo systemctl enable ssh       # 自动启动`

安装之后在终端输入 ssh -v 若如下图显示则证明ssh 安装完毕

![image-20241008215104231](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008215104231.png)

进行文件配置 

输入下列代码，进入配置文件

`sudo cp /etc/ssh/sshd_config /etc/ssh/sshd_config.backup # 无论怎样，备份是个好习惯
sudo vi /etc/ssh/sshd_config`

编辑配置文件，看情况进行删除和添加

**对于Linux中vi文本编辑器的使用指南，在这：[vi编辑器怎么编辑文件](https://blog.csdn.net/qq_42175986/article/details/82770878)**

[vi编辑器怎么保存文件](https://blog.csdn.net/qq_37908248/article/details/103961393)

***（因为Linux中文本编辑与我们常用的操作逻辑有较大差距，务必查看上述链接内容！！!）***

`Port 22     # 默认连接端口为22
PermitRootLogin yes
PasswordAuthentication yes
AllowUsers xxx # 这里的 "xxx" 改成你自己的登陆用户名
RSAAuthentication yes
PubKeyAUthentication yes`

#### 5.3 vscode安装ssh

**第一步**![image-20241008232631832](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008232631832.png)

在插件搜索栏搜索ssh下载到你的vscode

**第二步**

在vscode的界面按下ctrl+shift+p，搜索ssh选择打开ssh配置文件，如果是英文就选open ssh configuration file，打开之后我们回到虚拟机

**第三步**

新建一个终端，输入ifconfig查看虚拟机的网络配置情况

![image-20241008233827251](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008233827251.png)

**第四步**

返回vscode中的配置文件，进行编辑

![image-20241008234245692](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008234245692.png)

第一行写虚拟机主机名，不知道的可以在虚拟机终端输入hostname命令来查看

第二行写虚拟机的IP地址

第三行写user名字，也就是之前所编辑的Allowuser后面的名字

第四行添加Port 22

**第五步**

在Vscode中输入ctrl+shift+p，输入ssh，点击*将当前窗口连接至主机*，选择对应主机，输入虚拟机密码之后就是连上了，连接上之后可以从这里快速链接虚拟机

![image-20241008234924617](https://raw.githubusercontent.com/Imagineer233/image/main/image-20241008234924617.png)

至此，我们已经完成了Ubuntu虚拟机的搭建以及用vscode远程链接虚拟机的操作，还需要在找一点时间去学习一下docker。

（还有记得写感悟）

​                                                                                                                                                                                        ——*2024.10.8*

