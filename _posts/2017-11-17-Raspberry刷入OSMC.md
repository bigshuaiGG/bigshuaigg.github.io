---
 layout:   post                                                                            # 使用的布局（不需要改）
 title:    利用RaspberryPi 3刷入OSMC17.4打造个人机顶盒                                       # 标题 
 subtitle: 家里办了网，又不想办有线，乱费钱，就想到了捣鼓树莓派当机顶盒，接下来手把手教你刷入OSMC # 副标题
 date:     2017-11-17                                                                      # 时间
 author:   bigshuaigg                                                                      # 作者
 header-img:                                                                               # 这篇文章标题背景图片
 catalog:  true                                                                            # 是否归档
 tags:                                                                                     # 标签
     -Raspberry  
---
 
 
 ## Hey
 >
 这是我的第一篇博客。
 
  物理机系统：Windows7x64
 刷入系统：OSMC17.4
 刷入的硬件：Raspberry Pi 3
 读卡器：1个
 空白内存卡： 16G TF(Micro SD)Class 10 一张
 
 进入正题。
 一、什么是Kodi
     Kodi是一个优秀的自由和开源的（GPL）媒体中心软件，最初为Xbox而开发，可以运行在Linux、OSX、Windows、Android4.0系统。 
 二、什么是OSMC
     OSMC是一个自由和开放源代码的媒体中心，服务于广大群众，它是基于KODI项目的。
     我们如果在树莓派上搭建一个媒体中心为了方便和性能最优推荐在树莓派上刷入OSMC。
    首先进入<a href="https://osmc.tv/download/">OSMC官网</a>下载磁盘映像，我这里是Raspberry Pi3选择对应的文件，将得到的压缩包解压
 得到.img结尾的文件，我们将它剪切到我们的本地磁盘的根目录上(ps:据说不能用中文目录，文件名不能太长啥的，我们就按潜规则这么干吧)。
     我是在Windows平台下，我们用Win32DiskImager这个软件将我们的OSMC刷入系统，刷入完毕后，退出读卡器，将SD卡插入树莓派。
     我们将树莓派的HDMI连接好，接上电源，网线，我们就可以看到系统启动了，界面是英文的。
 至于后面的中文配置和插件的安装和具体细节问题下篇博文详述，今天只讲输入成功并看到界面。
