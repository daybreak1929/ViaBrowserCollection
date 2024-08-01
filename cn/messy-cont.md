# 奇奇怪怪的推荐

## 💡广告拦截规则(Adblock)
使用方法：
将网址单独复制，然后进入via的设置＞通用＞广告拦截＞规则订阅，点击右上角添加符号(默认为“+”)，选择“自定义”，将下列网址粘贴进去

![输入图片说明](img/adblock.png)

✧部分规则无法更新新请先尝试 开科学/魔法，无果后再尝试反馈作者

主要推荐“[轻量广告拦截规则](https://raw.gitmirror.com/damengzhu/banad/main/jiekouAD.txt)”、"[白名单规则](https://mirror.ghproxy.com/raw.githubusercontent.com/8680/GOODBYEADS/master/allow.txt)"、“[混合规则精简版](https://lingeringsound.github.io/adblock_auto/Rules/adblock_auto_lite.txt)”和“[Ad-J](https://gcore.jsdelivr.net/gh/jk278/Ad-J/Ad-J.txt)”，不误杀就是最好的效果

<details><summary> ✧展开小型规则列表✧ </summary>

> Ad-J(300+规则) <br> https://gcore.jsdelivr.net/gh/jk278/Ad-J/Ad-J.txt

> 去除APP下载提醒(1000+规则) <br> https://cdn.jsdelivr.net/gh/Noyllopa/NoAppDownload@master/NoAppDownload.txt

> 白名单规则(4000+规则，唯一一个全部为避免误杀的订阅) <br> https://mirror.ghproxy.com/raw.githubusercontent.com/8680/GOODBYEADS/master/allow.txt

> 轻量广告拦截规则(酷安@大萌主，5000+规则) <br> https://raw.gitmirror.com/damengzhu/banad/main/jiekouAD.txt

> AdGuard Mobile Ads filter(7000+规则) <br> https://filters.adtidy.org/extension/ublock/filters/11.txt)

> adgk手机去广告规则(9000+规则，需开科学) <br> https://raw.githubusercontent.com/banbendalao/ADgk/master/ADgk.txt

> 屏蔽获取Cookie弹窗(近2w规则，可能需开科学) <br> https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_18_Annoyances_Cookies/filter.txt

> 混合规则精简版(酷安@夕阳醉歌，2w+规则) <br> https://lingeringsound.github.io/adblock_auto/Rules/adblock_auto_lite.txt

> XXKiller(2w+规则) <br> https://cdn.jsdelivr.net/gh/DoingDog/XXKiller@main/w.txt

</details>

<details><summary> ✧展开大型规则列表✧ </summary>

> AdKiller-Lite(3w+规则，包含“轻量广告拦截规则”和“去除APP下载提醒”) <br> https://raw.gitmirror.com/PhoenixLjw/AdRules/main/filter-lite.txt

> AdRules AdBlock List Lite(3w+规则，需开科学) <br> https://adrules.top/adblock_lite.txt

> ABP Merge Rules(5w+规则，包含“轻量广告拦截规则”) <br> https://raw.gitmirror.com/damengzhu/abpmerge/main/abpmerge.txt

> AdFilters(6w+规则) <br> https://cdn.jsdelivr.net/gh/o0HalfLife0o/list/ad3.txt

> AdBlock Filter(11w+规则，包含“adgk手机去广告规则”，需开科学) <br> https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/adblockfilters.txt

</details>

<details><summary> ✧自定义规则简易使用方法✧ </summary>

例如：隐藏百度首页自动播放的视频(因为不是广告，大多规则订阅并不会将其加入)

```
baidu.com##[data-video-play-type="true"]
```

进入via的设置＞通用＞广告拦截＞自定义规则，将规则粘贴进去即可

![输入图片说明](img/custom.png)

</details>

> 自定义规则一般很少用到，因为菜单中的“标记广告”功能(如果没找到就长按菜单中“设置”，将其添加进去)可以直接在页面上选中，但有些广告可能会无法标记可以寻求帮助

<br>

⚠注意

> 尽管via浏览器目前已经支持广告规则去重(4.5.0)，但重复的规则仍然会拖慢网页加载速度，请适量 <br> <details><summary> 了解详细 </summary>![输入图片说明](img/OOM.png)</details>

> via浏览器的“启用内建规则”建议开启，如遇误杀直接将问题反馈给官方即可 <br> <details><summary> 了解详细 </summary> ![输入图片说明](img/built-in.png) <br> ![输入图片说明](img/answer.png)</details>

*****

## 💡浏览器标识(User Agent)

浏览器标识(简称UA)可以使服务器能够识别客户使用的操作系统及版本、浏览器内核及版本、浏览器渲染引擎、浏览器语言等,让网页作出相应的适应(如识别电脑手机端、添加推送等)

⚠注意：因为Google及Cloudflare验证的特殊性，应尽量避免使用除默认以外的全局UA，不然可能出现Google安全认证未通过、Cloudflare频繁验证失败等问题

使用方法：设置＞通用＞浏览器标识，点击右上角的添加符号(默认为“+”)，将需添加到UA粘贴进“浏览器标识”框内即可

![输入图片说明](img/addUA.png)

<details><summary> ✧展开推荐UA列表✧ </summary>

1. 简单搜索UA旧版整合

> 优点：百度关自动播放(不缓存)、防拉💩、必应无下载提示 <br> 缺点：没有搜索框、内核可能有点旧

> Mozilla/5.0 (Linux; U; Android 10; zh-CN; 2014811 Build/QQ3A.200805.001) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/119.0.2564.116 Quark/3.8.2.126 Mobile Safari/537.36 T7/10.3 SearchCraft/2.6.3 (Baidu; P1 8.0.0) edge

2. 简单搜索UA新版 

> 优点：百度有AI、关自动播放、会自动翻页、防拉💩 <br> 缺点：没有搜索框、UI变动大、没有横栏切换、视频仍然会缓存

> Mozilla/5.0 (Linux; Android 12; PDKM00 Build/SP1A.210812.016; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/97.0.4692.98 Mobile Safari/537.36 T7/13.50 ChatSearch/1.0 SearchCraft/5.10.0.13 (Baidu; P1 12)

3. Edge浏览器默认UA 

> 优点：百度关自动播放(不缓存)、有搜索框；必应去除下载提醒 <br> 缺点：不防百度拉💩

> Mozilla/5.0 (Linux; Android 15; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/126.0.0.0 Mobile Safari/537.36 EdgA/126.0.0.0

4. 火狐/雨见浏览器默认UA `类似Edge的UA`

> Mozilla/5.0 (Android 14; Mobile; rv:120.0) Gecko/120.0 Firefox/120.0

5. 小米浏览器默认UA 

> 最好是给百度系的单独设置，其他网页可能会加广告

> Mozilla/5.0 (Linux; U; Android 13; zh-cn; 23013RK75C Build/TKQ1.220905.001) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/100.0.4896.127 Mobile Safari/537.36 XiaoMi/MiuiBrowser/17.3.5 swan-mibrowser

6. 8.0.49版本微信的UA

>最好是只给提醒“请用微信APP打开”的网站使用

>Mozilla/5.0 (Linux; Android 14; 22081212C Build/UKQ1.230917.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/116.0.0.0 Mobile Safari/537.36 XWEB/1160175 MMWEBSDK/20240404 MMWEBID/7962 MicroMessenger/8.0.49.2600(0x2800313D) WeChat/arm64 Weixin NetType/WIFI Language/zh_CN ABI/arm64

7. 酷安[ _@靈狐_ 自制的日用UA](https://www.coolapk.com/feed/39514762?shareKey=YTg2MDUwZTRhM2FmNjYwYWRhNTg~&shareUid=20596394)

因为自带介绍，而且大佬可能还在更新，这边就直接提供网址了，进去自行复制，[→戳这←](https://aifoxs.gitee.io/user-agent)

</details>

这边不打算更新更多了，提供一个检测UA的网站，也附带了一些常见浏览器的UA

[UA检测-在线工具](https://useragent.buyaocha.com)

*****

## 💡搜索引擎(Search Engines)

via在5.5.0更新后支持自定义多个搜索引擎，特此添加对应部分方便使用

使用方法：设置＞通用＞搜索引擎，点击右上角的添加符号(默认为“+”)

![输入图片说明](img/addEngines.png)

<details><summary>常规搜索引擎列表(暂收录15个)</summary>

> bing中国 <br> https://cn.bing.com/search?q= <br> via自带的为国际版，国内使用国际版会有一次重定向，或许可以规避一些加载慢的问题

> Oceanhero(德国的搜索引擎，称每五次搜索就收集一个海洋塑料瓶) <br> https://oceanhero.today/web?q= <br> 无广告，完美的自动翻页，会保留到上次阅读词条，自带一个能识别中文但不会中文回答的AI

> Whoogle(开源搜索引擎) <br> https://search.snine.nl/search?q= <br> 基于Google，无广告，[开源地址](https://github.com/benbusby/whoogle-search)

> 勾勾搜索(开源搜索引擎) <br> https://gogo.webbillion.cn/search?q= <br>基于Google，无广告，[开源地址](https://github.com/zenuo/gogo)

> SearXNG(开源搜索引擎) <br> https://searx.si/search?q= <br> 聚合搜索引擎，无广告，不收集或跟踪用户数据；国内能使用的站点不一定稳定

> Cynay(称是世界上第一个独立个体制作的搜索引擎) <br> https://cynay.com/search?q= <br> 基于Google，无广告，有点慢的自动翻页

> Qwant(法国搜索引擎) <br> https://www.qwant.com/?q= <br> 基于Bing，无广告，不收集或跟踪用户数据

> eFind(美国搜索引擎) <br> https://efind.com/search?q= <br> 目前无广告，时好时坏的自动翻页

> youcare(法国搜索引擎) <br> https://youcare.world/all?q= <br> 目前无广告，会保留到上次阅读页码

> Yandex(俄国搜索引擎) <br> https://www.yandex.com/search/touch/?text= <br> 有广告，但架不住美图多

> Swisscows(瑞士搜索引擎，称是“家庭友好型”，不包含色情和暴力) <br> https://swisscows.com/en/web?query= <br> 不收集或跟踪用户数据

> Ecosia(德国搜索引擎，称是最环保的搜索引擎，采用太阳能发电) <br> https://www.ecosia.org/search?q= <br> 基于Bing，且国内网络使用会被劫持到Bing

> Yahoo(日本搜索引擎，要挂梯) <br> https://search.yahoo.com/search?p=

> Brave(美国搜索引擎，要挂梯) <br> https://search.brave.com/search?q=

> StartPage(荷兰搜索引擎，称是世界上最私密的搜索引擎，要挂梯) <br> https://www.startpage.com/sp/search?q=

> Yep(新加坡搜索引擎，要挂梯) <br> https://yep.com/web?q=

</details>

<details><summary>AI搜索引擎列表(暂收录10个)</summary>

> 天工AI <br> https://www.tiangong.cn/result?q=

> 开搜AI <br> https://kaisouai.com?q=

> ThinkAnyAI <br> https://thinkany.so/zh/search?source=all&q=

> 360AI <br> https://www.sou.com/?q=

> 十号AI <br> https://retardphobia.moebh.org/ui/search?mode=1&q=

> iSouAI <br> https://isou.chat/search?q=

> PhindAI <br> https://phind-ai.com/zh/search?q=

> AndiAI <br> https://andisearch.com/?q=

> iAskAI <br> https://iask.ai/?q=

> PerplexityAI(要挂梯) <br> https://www.perplexity.ai/?q=

</details>

<details><summary>其他搜索引擎列表</summary>

> 百度百科 <br> https://baike.baidu.com/item/%s/

> 哔哩哔哩 <br> https://www.bilibili.com/search?keyword=

> 微博 <br> https://weibo.com/search?containerid=100103type=1&q=

> 小红书 <br> https://wap.sogou.com/web/xiaohongshu?keyword=

> 微信文章 <br> https://weixin.sogou.com/weixinwap?type=2&query=

> 知乎搜索(登录后才能使用，知乎网页限制) <br> https://www.zhihu.com/search?type=content&q=

> 抖音 <br> https://www.douyin.com/search/

> Gitee <br> https://so.gitee.com/?q=

> GitHub <br> https://github.com/search?q=

> Quora(俗称“美版知乎”，登录后才能使用，要挂梯) <br> https://www.quora.com/search?q=

> 维基百科中文(Wiki，要挂梯) <br> https://zh.wikipedia.org/w/index.php?search=

</details>

💧夸克搜索引擎其实就是神马搜索(via自带)的换皮并加广告(夸克内没广告是因为其UA可以去自己的广告)，没有必要添加进去

⚠注意：部分搜索引擎有电脑和手机网页的区分，站点可能会自行重定向导致进度条多加载一次，此为正常现象，如果觉得缓慢可以将对应部分换为移动网页样式

*****

## 💡via图标包(Skins)
使用方法：在地址栏输入v://skins即可进入，点击右上角的添加符号(默认为“+”)找到对应压缩包即可

![输入图片说明](img/addSkins.png)

<details><summary>酷安 @半烟半雨溪桥畔 的图标包合集</summary>

[酷安 _@半烟半雨溪桥畔_ 的图标包合集](https://www.lanzn.com/b0337qg1c)，密码：6666

![输入图片说明](img/myskins.png)

</details>

<details><summary>酷安 @million先森 的图标包合集</summary>

[酷安 _@million先森_ 的图标包合集](https://www.lanzn.com/b02dx028j)，密码：9sbt

![输入图片说明](img/skins2.png)

</details>

<details><summary>酷安 @大迈克 的魅族浏览器图标包</summary>

[酷安 _@大迈克_ 的魅族浏览器图标包](https://www.lanzn.com/b012evkxc)，密码：35ug

</details>

<details><summary>酷安 @hjiangs 的ViaRounded7.4图标包</summary>

[酷安 _@hjiangs_ 的ViaRounded7.4图标包](https://lanzoup.com/iaChK1nwib4f)

</details>

*****

## 💡via主页定制(Via-Home)
<details><summary> ✧完整主页推荐✧ </summary>

1. [自用via定制主页](https://www.lanzn.com/b033jzlxa)，内含使用方法，密码：6666

功能：屏蔽下滑聚焦地址栏，增加下滑聚焦搜索框、双击聚焦搜索框，支持切换搜索引擎，搜索框删中文按钮，简易书签抽屉，点击展示小书签窗口的渐变logo

支持自定义，如有问题可找[酷安@半烟半雨溪桥畔](http://www.coolapk.com/u/20596394)

<details><summary>具体自定义内容展开</summary>

![输入图片说明](img/myHomeCSS.png)

</details>

![输入图片说明](img/myHome.gif)

2. [酷安 _@腿短的二狗子_ 的主页](https://www.lanzn.com/b06eccgmd)，内含使用方法，密码：6666

功能：在主页设置里支持GIF、mp4格式背景，支持显示天气和时间、搜索框左侧切换搜索引擎，搜索框右侧扫描二维码按钮，搜索框上方显示搜索历史，搜索框聚焦下移，完美书签抽屉

支持自定义，如有问题可找[酷安@腿短的二狗子](http://www.coolapk.com/u/3632084)，

<details><summary>具体自定义内容展开</summary>

进入书签抽屉，右上角齿轮即是主页设置 

![输入图片说明](img/home2Custom.png)

</details>

![输入图片说明](img/home2.gif)

</details>

…………………………

单独的主页功能

- [酷安 _@耗子Sky_ 的主页搜索框历史记录](https://bitbucket.org/!api/2.0/snippets/lemon399/aqLxK4/4eeca77988a73c5cbb8a998bf89af21caacd67ae/files/hist.html)

进入链接，将代码全选，然后到设置＞定制＞Logo，选择“HTML代码”，将代码粘贴进去(代码前两行是via的自带logo，如果不需要可以删除)

- [酷安 _@undefined303_ 的主页搜索框提取链接](https://lanzoup.com/iXv4a1bj8uuf)

进入链接，将最新文件下载下来后，将里面的代码复制，然后到设置＞定制＞Logo，选择“HTML代码”，将代码粘贴进去

- [收集的功能(暂含显示时间、天气、诗句)](https://www.lanzn.com/b033s67ib)，密码：6666

*****

## 💡其他(Others)

1. [问答专区及使用技巧](FAQ.md)

2. 油猴脚本收藏夹([→戳这看介绍←](script-share.md))

- [→GreasyFork收藏夹(via浏览器可用)地址←](https://greasyfork.org/scripts?filter_locale=0&set=586537)

3. [via小功能或冷门知识](via-help.md)

4. [via浏览器各版本的拾穗整理](https://www.sgfox.cc/archives/via-shisui.html)

5. [via历史版本(官方版，豌豆荚链接)](https://m.wandoujia.com/apps/6609177/history)

6. [(via官方教程)使用webdav同步数据](https://viayoo.com/zh-cn/docs/sync-your-data-via-webdav.html)

*****

[返回主页](../README.md)