# GitHub_-Diary
Star，93项目
日常，已写4天

夜猫子视角，大部分凌晨3点之前都算上一天。





### 5月28日

&emsp;&emsp;**http和https**：SSH配置，之前只是用http先跑起来，把SSH证书添加进去有些功能才真正可以用，现在前后端都是走的https协议了

&emsp;&emsp;**图床配置**：[picx](https://github.com/XPoet/picx)比另一个开源项目PicGo好用很多，毕竟专门弄GitHub图床代理



<p></p><p></p><p></p>

***

<p></p><p></p><p></p>

### 5月27日
GitHub玩得太沉迷了这两天导致没空写

&emsp;&emsp;**01 公网与局域网**：凌晨2点天花板发呆，还是跑不起来，想通，我局域网，要发布互联网，反向代理的前提是在服务器。所以代理之后就可以直接访问，大佬教程基于服务器。随机问GPT4o，产生思路，爬起尝试用自带公网IP看能不能跑通，跑不通，大败

&emsp;&emsp;**02 家庭宽带自带公网IP**：域名解析到家庭IPV4公网地址，不出意外的话一定出意外了，无法访问，需要找运营商开通，再配置DDNS，放弃，内网穿透简单很多

&emsp;&emsp;**03 Linux重装**：下了太多东西，破防重装系统，顺便把系统盘多分150G，许多教程说主硬盘只分一点，别信，作者Win用多了，Unix都是一个分区包干的，swap和EFI分配一下，其他全部分到主硬盘最好

&emsp;&emsp;**04 内网穿透**：采用内网穿透（本地与公网连接，类似代理吧）  跟着[Sakura Frp](https://www.natfrp.com/)网站配置，选择穿透到外国服务器绕过备案，将本地东西穿透到后端域名，满足需求，希望[Sakura Frp](https://www.natfrp.com/)能稳定下去，后端免费流量基本用不完

&emsp;&emsp;**05微小而致命的失误**：前端跑不起来，浪费大量时间，主题配置文件没有复制。成功运行sorrow233.cn，很开心

总结：自己很笨，应该站在一个高的角度把这些事想明白，再去实践，会快许多，但谁知道呢，多花的时间不可能赚回来

<p></p>

<p></p>

<p></p>

***

<p></p>

<p></p>

<p></p>

### 5月26日

[Shiro](https://github.com/Innei/Shiro)这个开源项目实在太好看，令人难以拒绝，而且站长使用的是自己的后端，这样作者未来设计新页面页依旧可以直接迁移

**接触前后端分离网站**：白天起来想了想，还是要把那个个人博客配置好，因为好看，难以拒绝。下午把后端和前端成功配置好了。之后就去弄反向代理，一直弄到晚上，结果才发现我不是服务器，反向代理弄了也白搭，之所以不能托管和反向代理没关系。到了深夜才发现



<p></p>

<p></p>

<p></p>

### 5月25日  Linux  脚本配置

&emsp;&emsp;忍受着垃圾Linux的垃圾输入法写下第一天日记，这是我第一次使用Linux写diary也是最后一次。

&emsp;&emsp;Nvidia，今天下载了显卡驱动，导致网卡掉了，我一个linux小白看着无法上网的系统，嗯，再平静的心在此刻也会变得焦躁，最后不得不重装一遍，系统安装技能得到了锻炼，让我想起一个很有趣的视频[Nvidia Love you！](https://www.bilibili.com/video/BV1rY4y1576M)

&emsp;&emsp;很早之前我就知道RSS，但一直没有去配置，一想，如果一个习惯理性上来说比之前的习惯更好，那么我就有必要尝试去养成这个习惯，抱着这个想法，我找到了Mac上的开源[NetNewsWire](https://github.com/Ranchero-Software/NetNewsWire)，之后又去找了一些订阅源[RSSHub](https://github.com/DIYgod/RSSHub)，但找订阅源的时候，看到了很多吸引人的新闻，导致新闻订阅源没找，全部花时间看新闻去了

&emsp;&emsp;之后想使用linux配置一些自动化脚本，成功在配置好了两个开源项目[B站自动化](https://github.com/lkeme/BiliHelper-personal.git)和[米哈游自动签到](https://github.com/Womsxd/MihoyoBBSTools.git) b站只用了10分钟，主要因为升级PHP 8.3包的问题，米游社因为代码不支持社区活动，但readme.md没写出来，导致我配置了一个半小时，还是不能成功运行，最后退而求其次，只弄了简单的每天早上6点自动运行签到脚本，同时我也在更多可以24小时不间断运行的脚本，**计算机最大的魅力之一就是能自动化**。![Linux-main](https://github.com/sorrow233/picx-images-hosting/raw/master/Linux-main.5j4169nbbv.webp)
