# 华科系统结构实验2021

#### 介绍
华中科技大学计算机系统结构实验

#### 使用说明

1.  实验环境为Linux-64位
2.  实验所需要设计的文件位csim.c，即设计cache并进行模拟仿真
3.  所有的make文件均已经编写好，完成csim.c的编写后，在命令行输入如下命令进行编译
```
->make clean
->make
```
4.  编译完后会得到csim输出文件，输入对应的指令即可以模拟cache运行，然后将结果同csim-ref所执行相同指令得到的结果相比较。
5.  也可以直接运行如下指令进行总体测试
```
->./test-csim
```

#### 阿里云服务

1.  本实验也给出了阿里云服务器的模拟，需要下载的相关软件在Xshell-7.0.0054p.rar压缩包中，解压后分别安装Xftp7和Xshell。
2.  打开本实验所用到的阿里云链接[华科计算机系统结构](https://developer.aliyun.com/adc/scenario/98e50c84bb4341018c06cb6c25e2ced6)，然后注册阿里云账户并登陆
3.  点击`开始体验`，进入到如下界面<br>![阿里云服务器信息](https://images.gitee.com/uploads/images/2021/0430/104409_d06873eb_8206880.png "屏幕截图.png")
4.  选择`免费开通`，会自动加载云产品资源，得到如下所示的云服务信息<br>![云服务器信息](https://images.gitee.com/uploads/images/2021/0430/103731_16ba75d3_8206880.png "屏幕截图.png")
5.  打开Xftp7，新建会话，然后会弹出如下窗口<br>![新建会话窗口](https://images.gitee.com/uploads/images/2021/0430/104253_2194c746_8206880.png "屏幕截图.png")
6.  在云服务器信息上找到对应信息并填写后，打开刚刚新建的会话，然后新建Xshell，如图<br>![新建Xshell](https://images.gitee.com/uploads/images/2021/0430/104634_342ad697_8206880.png "屏幕截图.png")
7.  然后在刚刚的Xftp窗口找到实验包所在路径，并在Xshell界面转到，即输入如下指令
```
#cd /hzkj/cachelab-handout
```
8.  对文件夹中的csim.c文件进行修改，完成对cache的正确模拟，如图<br>![文件路径和命令行](https://images.gitee.com/uploads/images/2021/0430/105139_1e60fb84_8206880.png "屏幕截图.png")
9.  完成相关操作后，编译测试。
