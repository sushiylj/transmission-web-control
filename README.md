### 目前项目已恢复正常维护，感谢 @DarkAlexWang 支持 :)
-----
关于
-----
本项目主要目的是想加强[Transmission](https://www.transmissionbt.com/) Web的操作能力，本项目原本在[Google Code](https://code.google.com/p/transmission-control/)托管，现迁移至GitHub。
本项目设计之初仅针对PT站，因此增加了 Tracker 服务器分组及状态，但这不并适用于普通BT种子。

#### [English Introduction](#introduction)

### 支持的Transmission版本(Support Transmission Version)
 - Transmission 2.40 及以上版本（RPC版本：14及以上）
 - Transmission 2.40 and above (RPC version: 14 and above)

### 已修复问题
现在已经修改的问题如下：
 - 更新了源程序的tar文件
 - 修复英文界面的一些笔误
 - 添加了http的安装方法
 - 更新了install.sh的英文注释
 - 更新了easyui到1.5.1和jquery到1.12.4 By -- @balonik
 - 修复问题#20，#21，#23，#39，#40，#43，#44, #53 By -- @balonik
 - 替换了一些中文注释为英文注释.
 - 修复问题#77，#81 （如果载入错误，请清空cookies。） By -- @balonik
 - 种子列表数修改为最多300，同时也可修改config.js中的"pagination:true" 为"pagination:false"来显示所有种子。 By -- @balonik

### 功能介绍
 - 在线查看Transmission当前工作情况；
 - 在线添加新的种子文件或连接；
 - 在线修改Transmission参数；
 - 分页浏览方式加载种子；
 - 多语言环境支持；
 - 文件拖放添加种子；
 - 删除指定的种子；
 - 批量修改 Tracker；
 - 移动指定种子的数据存放目录；
 - 可按 Trackers 分组浏览；
 - 增加对群晖downloadstation的支持；By - @hitechbeijing
 - 其他……

### 浏览器支持
 - 所有支持HTML5的浏览器(Chrome 15.0.874，Firefox 8.0.1，IE 9.0.8112，Opera 11.52)

### 安装方法
 - 可通过以下地址获取最新版的程序：
~~~
  https://github.com/ronggang/transmission-web-control/raw/master/release/transmission-control-full.tar.gz
~~~
 - 或到下载安装脚本，此脚本只需要下载一次，以后只需要执行即可:
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/tr-control-easy-install.sh
  sudo bash tr-control-easy-install.sh
~~~
 - 如果需要http而不是https，请使用以下命令:
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/tr-control-easy-install-en-http.sh --no-check-certificate
  sudo bash tr-control-easy-install-en-http.sh
~~~
 - 如果需要安装到群晖downloadstation,请下载下列安装脚本并运行：
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/ds-control-easy-install.sh
  sudo bash ds-control-easy-install-en-http.sh
~~~

### 关于多语言(Multi-language)
系统使用多语言的方式构建，所以可以支持其他任何语言；但，由于本人水平有限，只会中文，所以需要懂其他语言的您的帮助，如果您已经翻译好了一个语言版本，请同时发给我一份，我会打包在一起，分享给更多的用户，谢谢。

#### 当前已支持的语言(Currently supported languages)：
 - `2013-04-22` [简体中文(Simplified Chinese)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/zh-CN.js) @栽培者
 - `2014-02-09` [正體中文(Traditional Chinese)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/zh-TW.js) @Sean
 - `2013-04-22` [英文(English)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/en.js) @栽培者
 - `2014-02-09` [俄语(Russian)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/ru.js) @Oleksandr Gureiev & @irherder
 - `2013-04-17` [西班牙语(Spanish)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/es.js) @Adrián González
 - `2013-02-05` [波兰语(Polish)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/pl.js) @Daniel Kolek
 - `2013-11-11` [匈牙利语(Hungarian)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/hu.js) @Swartzy
 - `2013-05-18` [罗马尼亚(Romanian)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/ro.js) @Laurentiu Dinulescu
 - `2013-05-28` [意大利(Italian)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/it.js) @Daniele Buccilli
 - `2014-02-12` [葡萄牙语（巴西）(Brazilian Portuguese)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/pt-BR.js) @Dudu Maroja & @pcgaldo
 - `2013-08-20` [荷兰语 (Dutch/Flemmisch)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/nl.js) @Alwin Hummels
 - `2013-09-12` [法语 (French)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/fr.js) @Amaury Aubry
 - `2013-12-05` [韩语 (Korean)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/ko.js) @kdsz330
 - `2014-02-12` [葡萄牙语(European Portuguese)](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/pt-PT.js) @pcgaldo


Introduction
-------------------
Transmission Web Control is a custom web UI. The project began in [Goolge Code](https://code.google.com/p/transmission-control/).Welcome to give me any feedback or submit a Pull Request.

### Support Transmission Version
 - Transmission 2.40 and above (RPC version: 14 and above)

### Fixed issues
I will do my best to fix the issues in this repo.
 - Updated the install tar file
 - Fixed several typos in English interface
 - Added http install script
 - Added install.sh with English comments
 - Updated easyui to 1.5.1 and jquery to 1.12.4 By -- @balonik
 - Fixed issue #20, #21, #23, #39, #40, #43, #44 #53 By -- @balonik
 - Replaced some Chinese comments to English
 - Fixed issue #77，#81 (Please clear your cookies if you encounter any error) By -- @balonik
 - Now the maximum number of torrents per page is 300，meanwhile, you can still modify the file config.js "pagination:true" to "pagination:false" in order to show ALL the torrents. By -- @balonik

### Features
 - Add torrent files or URLs
 - Drag-and-drop to add torrent files
 - Online modify the Transmission setting (Download folder,Speed ​​limit,Port,etc.)
 - Pause / resume / recheck selected or all torrents
 - View the current torrents status (Files,Peers,Trackers,etc.)
 - View Statistics(Cumulative/Current)
 - The pagination torrents
 - Set files priority
 - Change the torrent download directory
 - Trackers list
 - Add support for Synology NAS downloadstation；By - @hitechbeijing
 - ...

### Browsers support
 - All browsers support HTML5. (Chrome 15.0.874，Firefox 8.0.1，IE 9.0.8112，Opera 11.52 etc.)

### Multi-language
#### How to use the language pack:
 - All language files are needed to put in the "lang" directory, format refer "lang/en.js";
 - Translated language file naming, and then copied to the lang directory, note that necessary ".js" suffix, such as: en.js;
 - Modify the the "lang/`_`languages.js" file, the new language format to add a line;
 - Regain access to the TR, if your browser's default configuration language "`_`languages.js" where it will automatically display the current language, if not, please manually select the language or the end of the page plus "?lang=language"; such as: 192.168.1.1/transmission/web/?lang=en

#### Currently supported languages：
 - `2013-04-22` [Simplified Chinese](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/zh-CN.js) @ronggang
 - `2014-02-09` [Traditional Chinese](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/zh-TW.js) @Sean
 - `2013-04-22` [English](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/en.js) @ronggang
 - `2014-02-09` [Russian](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/ru.js) @Oleksandr Gureiev & @irherder
 - `2013-04-17` [Spanish](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/es.js) @Adrián González
 - `2013-02-05` [Polish](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/pl.js) @Daniel Kolek
 - `2013-11-11` [Hungarian](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/hu.js) @Swartzy
 - `2013-05-18` [Romanian](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/ro.js) @Laurentiu Dinulescu
 - `2013-05-28` [Italian](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/it.js) @Daniele Buccilli
 - `2014-02-12` [Brazilian Portuguese](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/pt-BR.js) @Dudu Maroja & @pcgaldo
 - `2013-08-20` [Dutch/Flemmisch](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/nl.js) @Alwin Hummels
 - `2013-09-12` [French](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/fr.js) @Amaury Aubry
 - `2013-12-05` [Korean](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/ko.js) @kdsz330
 - `2014-02-12` [European Portuguese](https://github.com/ronggang/transmission-web-control/raw/master/src/tr-web-control/lang/pt-PT.js) @pcgaldo
 - If you have translated a language pack, please upload it here issue 9

#### [How to install](https://code.google.com/p/transmission-control/wiki/Install#1._Automatic_Installation_(Linux))

### Download
 - You can get the latest version of the program for this address:
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/transmission-control-full.tar.gz
~~~
 - Or download easy install script:
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/tr-control-easy-install.sh
  sudo bash tr-control-easy-install.sh
~~~
 - If you need to install into Synology NAS downloadstation, please download the following script:
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/ds-control-easy-install.sh
  sudo bash ds-control-easy-install-en-http.sh
~~~
 - If you need http download instead of https, please use the following
     commands:
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/tr-control-easy-install-en-http.sh --no-check-certificate
  sudo bash tr-control-easy-install-en-http.sh
~~~
 - install.sh script with english comments:
~~~
  wget https://github.com/ronggang/transmission-web-control/raw/master/release/tr-control-easy-install-en.sh
~~~

###### 创建于(Create): 2012.12.18；更新于(Update): 2014.10.13 By 栽培者(ronggang); Updated: 03-31-2017 by DarkAlexWang  ######
