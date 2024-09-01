# GitHub_-Diary

- ## 核心日志

  - [05 配置了新图床，很好看)](#9月1号)
  - [04 买了很多域名，手上共有四个付费域名，三个免费域名](#8月30号)
  - [03 发现宝藏论坛linux.do](#8月25号)
  - [**02 弄了一个Claude反向代理**：ai.catzz.work](#8月24号)
  - [01 成功在Linux配置了Shiro主题，且学习了网站配置的相关知识](#5月27日)
  - [00 Hello, Linux](#5月25日-linux-脚本配置)

<br><br>

### 9月1号

&emsp;&emsp;**新搭建了一个图床**：之前使用的是GitHub当图床，也能用，但今天在linux.do社区看到了一个新的项目，可以用自己的域名托管上去，并且有cloud flare加速。上次的图床只能说功能没问题，但现在这个图床我很喜欢。地址是pic.k-on.live（设置了强密码,只能自己用hhhh）

![image.png](https://pic.k-on.live/file/58cd966ba61afc0bd94e4.png)

<br>

***

<br>



### 8月30号

  **收藏了关注了一些域名**：目前手上已经有4个付费域名，.com .cn .live .work。

  **买了.live域名**：k-on.live。这个域名简直完美，是我手上最完美也是我最喜欢一个域名

  **免费us.kg域名**：白嫖了免费us.kg的免费域名，注册了三个域名绑定到了cloudflare，感觉很不错，一些简单的服务可以使用

![目前手上已经有4个付费域名](https://pic.k-on.live/file/3b3a521d858b79ace5847.png)

<br>

***

<br>



### 8月25号

&emsp;&emsp;**Linux.do社区**：25号晚上收到了邀请码，并且花了大量时间去阅读其中的博文，这个社区在互联网是绝对罕见的，里面的大佬有的不是傲慢，而是把自己的技术与资源化为实例分享给社区里的人，社区里面有懂技术的，有不懂技术的，但大家都在这个社区中友好和谐的相处，我只在这个社区看到了分享、和谐、温暖。

![image.png](https://pic.k-on.live/file/c4c466793614f49208af4.png)

<br>

***

<br>

### 8月24号

&emsp;&emsp;**弄了一个Claude**：ai.catzz.work。这个主要可以防止Claude的逆天封号机制，反向代理之后，配置了一下SSL证书（因为一些疑难杂症配置了半天），代理之后可以在其他没翻墙的设备上直接使用Claude

![image.png](https://pic.k-on.live/file/71070f9fe4e9161d2c0d5.png)



### 8月1号

&emsp;&emsp;**日语考试**：6月在准备日语考，之后买了MacBook Air

&emsp;&emsp;**图片下载**：[dezoomify-rs](https://github.com/lovasoa/dezoomify-rs.git)，可以直接下载Google Art上面的高清照片，安装使用都很方便

<img src="https://github.com/sorrow233/picx-images-hosting/raw/master/Github/image.7p76s8ait.webp" alt="image" style="zoom:50%;" />

<br>

***

<br><br>

### 5月28日

&emsp;&emsp;**http和https**：SSH配置，之前只是用http先跑起来，把SSH证书添加进去有些功能才真正可以用，现在前后端都是走的https协议了

&emsp;&emsp;**图床配置**：[picx](https://github.com/XPoet/picx)比另一个开源项目PicGo好用很多，毕竟专门弄GitHub图床代理

<img src="https://github.com/sorrow233/picx-images-hosting/raw/master/Github/image.escidb9jp.webp" alt="image" style="zoom:50%;" />

<br>

***

<br><br>

### 5月27日

GitHub玩得太沉迷了这两天导致没空写

&emsp;&emsp;**01 公网与局域网**：凌晨2点天花板发呆，还是跑不起来，想通，我局域网，要发布互联网，反向代理的前提是在服务器。所以代理之后就可以直接访问，大佬教程基于服务器。随机问GPT4o，产生思路，爬起尝试用自带公网IP看能不能跑通，跑不通，大败

&emsp;&emsp;**02 家庭宽带自带公网IP**：域名解析到家庭IPV4公网地址，不出意外的话一定出意外了，无法访问，需要找运营商开通，再配置DDNS，放弃，内网穿透简单很多

&emsp;&emsp;**03 Linux重装**：下了太多东西，破防重装系统，顺便把系统盘多分150G，许多教程说主硬盘只分一点，别信，作者Win用多了，Unix都是一个分区包干的，swap和EFI分配一下，其他全部分到主硬盘最好

&emsp;&emsp;**04 内网穿透**：采用内网穿透（本地与公网连接，类似代理吧）  跟着[Sakura Frp](https://www.natfrp.com/)网站配置，选择穿透到外国服务器绕过备案，将本地东西穿透到后端域名，满足需求，希望[Sakura Frp](https://www.natfrp.com/)能稳定下去，后端免费流量基本用不完

&emsp;&emsp;**05微小而致命的失误**：前端跑不起来，浪费大量时间，主题配置文件没有复制。成功运行sorrow233.cn，很开心

总结：自己很笨，应该站在一个高的角度把这些事想明白，再去实践，会快许多，但谁知道呢，唯一确定的是，多花的时间不可能赚回来

![image](https://github.com/sorrow233/picx-images-hosting/raw/master/Github/image.5tqv0spm76.webp)

<br>

***

<br><br>

### 5月26日

[Shiro](https://github.com/Innei/Shiro)这个开源项目实在太好看，令人难以拒绝，而且站长使用的是自己的后端，这样作者未来设计新页面页依旧可以直接迁移

**接触前后端分离网站**：白天起来想了想，还是要把那个个人博客配置好，因为好看，难以拒绝。下午把后端和前端成功配置好了。之后就去弄反向代理，一直弄到晚上，结果才发现我不是服务器，反向代理弄了也白搭，之所以不能托管和反向代理没关系。到了深夜才发现

<img src="https://github.com/sorrow233/picx-images-hosting/raw/master/Github/16918FB6-DC4B-4CAB-B5CC-EA1F2BDF17C8.86thi06ea7.webp" alt="16918FB6-DC4B-4CAB-B5CC-EA1F2BDF17C8" style="zoom: 67%;" />

<br>

***

<br><br>

### 5月25日  Linux  脚本配置

&emsp;&emsp;忍受着垃圾Linux的垃圾输入法写下第一天日记，这是我第一次使用Linux写diary也是最后一次。

&emsp;&emsp;Nvidia，今天下载了显卡驱动，导致网卡掉了，我一个linux小白看着无法上网的系统，嗯，再平静的心在此刻也会变得焦躁，最后不得不重装一遍，系统安装技能得到了锻炼，让我想起一个很有趣的视频[Nvidia Love you！](https://www.bilibili.com/video/BV1rY4y1576M)

&emsp;&emsp;很早之前我就知道RSS，但一直没有去配置，一想，如果一个习惯理性上来说比之前的习惯更好，那么我就有必要尝试去养成这个习惯，抱着这个想法，我找到了Mac上的开源[NetNewsWire](https://github.com/Ranchero-Software/NetNewsWire)，之后又去找了一些订阅源[RSSHub](https://github.com/DIYgod/RSSHub)，但找订阅源的时候，看到了很多吸引人的新闻，导致新闻订阅源没找，全部花时间看新闻去了

&emsp;&emsp;之后想使用linux配置一些自动化脚本，成功在配置好了两个开源项目[B站自动化](https://github.com/lkeme/BiliHelper-personal.git)和[米哈游自动签到](https://github.com/Womsxd/MihoyoBBSTools.git) b站只用了10分钟，主要因为升级PHP 8.3包的问题，米游社因为代码不支持社区活动，但readme.md没写出来，导致我配置了一个半小时，还是不能成功运行，最后退而求其次，只弄了简单的每天早上6点自动运行签到脚本，同时我也在更多可以24小时不间断运行的脚本，**计算机最大的魅力之一就是能自动化**。

![E85060BF-54AE-41B0-B466-1BBBB715EF2C_1_105_c](https://github.com/sorrow233/picx-images-hosting/raw/master/Github/E85060BF-54AE-41B0-B466-1BBBB715EF2C_1_105_c.4jnxukqbfx.webp)



### 模版

&emsp;&emsp;**发生什么**：内容

&emsp;&emsp;**发生什么**：内容

<br>

***

<br>
