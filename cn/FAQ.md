# 问答专区与使用技巧

本页目录：[❓问答专区](#%E9%97%AE%E7%AD%94%E4%B8%93%E5%8C%BA)¦[📏使用技巧](#%E4%BD%BF%E7%94%A8%E6%8A%80%E5%B7%A7)¦[🔦玩机技巧](#%E7%8E%A9%E6%9C%BA%E6%8A%80%E5%B7%A7)¦[📚其他](#%E5%85%B6%E4%BB%96)¦[💡其他推荐](#%E6%9C%89%E5%85%B3via%E7%9A%84%E5%85%B6%E4%BB%96%E6%8E%A8%E8%8D%90)

## ❓问答专区

#### 1.官方问答和隐蔽功能镇楼
> [Android版via常见问题文档](https://viayoo.com/zh-cn/docs/via-for-android-faq.html)  
> [via小功能或冷门知识](via-help.md)

#### 2.via浏览器触发异常问题？ && 屏幕底部弹出乱码怎么解决？

> [官方问答](https://viayoo.com/zh-cn/docs/via-for-android-faq.html#org8abacb3)中也有相应解释，可将相应截图反馈到[[QQ频道 ](https://pd.qq.com/s/142yif2dj)| [TG群组 ](https://t.me/+bMMIgOk0cnA3YjI9)]  
> 设置＞关于，点击via的logo，滑到最底下查看最新的log报错  
> 如果滑不到底可以在关于页面的右上角点击分享，用其他软件查看 _log.txt_

#### 3.如何查询系统webview版本号？怎么更新系统webview？

> ❶查询版本:①设置＞关于，点击via的logo，第十行的“WebView Version”后面就是版本号
> 
>> ⚠注意：华为鸿蒙系统的最新的[15版本HUAWEI Webview](https://www.123pan.com/s/OuOKVv-Q2I63.html)可类似Android Webview的114版本
> 
> ②设置＞关于，如果不是华为鸿蒙系统，长按via的logo就可以打开webview的开发者工具，如下图所示就是webview版本号  
> ![输入图片说明](img/webviewVersion.png)  
> ❷更新版本:①最稳妥的方法 就是到谷歌Play商店里，进入[系统webview](https://play.google.com/store/apps/details?id=com.google.android.webview)链接，点击菜单中“其他应用打开”或者长按菜单中“分享”，然后选择[Play商店](http://m.3673.com/down/17484.html)即可开始下载安装  
> 如果因为某些原因实在进不了Play商店，可选择[国内下载站](https://m.downkuai.com/android/167450.html)，然后安装，如遇安装失败，可参考下方玩机技巧更换系统安装器

#### 4.网页版式出现错误？

> <small>长按菜单中的“网站设定”(如没有此按钮，就长按菜单中“设置”添加，返回菜单后再长按“网站设定”)，将JavaScript设为允许，查看网页是否正常</small>  
> ①如此前有允许JavaScript，则再尝试关闭脚本、关闭广告拦截、关闭返回不重载、关闭电脑模式、字体大小设为100%、浏览器标识换为默认，查看网页是否正常，  
> ②如正常，再细化排查即可；如不正常，可再尝试关闭模块、更新webview(上面有提到)，如果仍然不能解决，可以按照“2.via浏览器触发异常问题？”提供的渠道去反馈，并说明上述流程已经尝试过

#### 5.via刷新不出网页？无法使用？

> <small>请先确保自己网速正常，网络配置无误</small>  
> ❶浏览器的默认主页无法加载:说明系统内核webview被影响了，一般来说只会是模块问题，自行排查  
> ❷浏览器的默认主页正常: ①回忆自己此前是否在启用/关闭🅅🄿🄽的瞬间仍然让via处于后台或小窗状态，如是，退掉via当前的后台或小窗，重新进入Via，出现原因参考如下  
> ![输入图片说明](img/fakeip.png)  
> ②如不是或按照上述方法不能解决，尝试启用🅅🄿🄽后再进入via，如能解决说明是dns污染问题(类似GitHub软件能用，网站不能进)  
> ③如仍然无法进入，按照“4.网页版式出现错误？”的流程走一遍(应该主要是webview版本或者模块)

#### 6.Google安全验证提示“不安全”？Cloudflare人机验证频繁失败？知乎文章出现乱码？

> 关闭“电脑模式”，然后将浏览器标识换成“默认”  
> 最近知乎加强了反爬虫，可能需要登录后才能不乱码，其他类似情况也可如此尝试  
> 如仍然有问题，可尝试使用“4.网页版式出现错误？”中的方案

#### 7.总是提示有不安全弹窗，能否关闭？

> 触发情况类似下图  
> ![输入图片说明](img/SSLwarn.png)  
> 设置＞高级＞忽略SSL证书警告，该功能主要是用于提醒站点证书是否有效，出现的情况不多，一是网站证书过期或未生效，如有可能应向网站方反馈；二是证书不受信任，可能是系统版本过低，没有内置根证书，也有可能是网站或者其他软件自签了证书  
> 忽略后仍然可以在地址栏左侧图标中查看(如下图)  
> ![输入图片说明](img/SSL.png)

#### 8.via浏览器的隐私保护如何？

>  ![输入图片说明](img/Security.png)  
> 浏览器本身隐私保护没有问题，但对于有“无痕”状态需求的用户来说，via的隐身模式仅能保证本地不保留浏览的相关记录，网页中记录的历史、登录状态等仍然会保留

#### 9.夜间模式失效？网页没有变暗？

> 先长按菜单中的“夜间模式”，启用“强制网页暗色”，如果仍然如此，可能是：
> ①网页使用图片或视频作为背景，这类网页背景不能暗色，可以尝试使用菜单中的“标记广告”(没有就长按菜单中“设置”，将标记广告移入)屏蔽背景  
> ②系统不支持强制暗色。可能是webview版本过低或者模块影响，需自行排查

#### 10.打开方式误选了总是/默认选择此项怎么恢复？

> 以HyperOS为例，系统设置＞应用设置＞右上角三个点＞其他设置＞重置应用偏好设置(是的，澎湃只能全部应用重置) <br> ![输入图片说明](img/setapp.png)  
> 其他系统可参考能否找到/搜到对应设置，如果能单应用偏好重置自然最好，实在找不到就只能[导出/导入数据](baike/data.md)然后卸载重装喽~

#### 11.各种同步方式有什么差异？
 
> 因markdown语法限制，现已转移至新页面→[数据管理](baike/data.md)

#### 12.怎么装脚本？为什么脚本安装失败？

> 为保证更多外部问题能写入问答区，现已迁移至新页面→[脚本说明](baike/script.md)

*****

## 📏使用技巧

#### 1.打开脚本设置/脚本菜单

> 为保证能更详细阐述此部分，现已迁移至新页面→[脚本说明](baike/script.md)

#### 2.批量下载图片

> via目前没有这个功能，可以使用脚本[Picviewer CE+](https://greasyfork.org/zh-CN/scripts/24204)(悬停在图片上，图片左上角会出现脚本的半透明悬浮窗，进入即可选择图片批量下载)或[通用图片下载器](https://greasyfork.org/zh-CN/scripts/501400)(界面左下角按钮用于保存此页面所有图片)

#### 3.嗅探视频下载

> via虽然自带这个功能，但总体体验不太适合懒人，也没有合适的教程，这边推荐用脚本[仿via资源嗅探](https://greasyfork.org/zh-CN/scripts/471390)  
> 使用方法：打开有视频资源的网页，并播放视频；打开脚本菜单，找到此脚本，点击“资源嗅探①”，后续一般就没问题了直接下。目前试的大部分mp4都可以直接下载  
> m3u8格式的视频就用via自动展示的嗅探按钮，选择第三方下载器来解决吧，毕竟via没有[m3u8转mp4](https://anyconv.com/tw/m3u8-zhuan-mp4/)功能

#### 4.单独清理网站数据

> via暂未自带此功能，可以使用[网页调试](https://greasyfork.org/scripts/475228)脚本来实现  
> 使用方法：打开网页，默认会有一个图标(即图中的①)，点击后再点击栏中的Resources(即图中的②)，将Local Storage、Session Storage、Cookie清空(即点击图中③的图标)  
> 使用场景一般是网页出现异常或者需要单独去除登录状态之类的情况，如：Bing网页显示异常  
> ![输入图片说明](img/erudaClear.png)

#### 5.清理占用过多的存储数据(其他浏览器可能同理)

> 正常情况下via的存储占用不会超过1G，查看webview版本是否在105上下(具体区间不明)，如果是那就有可能是webview的bug，更新webview然后清除缓存(设置＞通用＞清除数据，单选“缓存”，点击确定)即可  
> ![输入图片说明](img/BrowserMetrics.png)  
> 如果不是，可在清除数据中选择缓存、历史、最近关闭的标签页、应用缓存，确定后一般就恢复正常了。相应的，在“退出时清除数据”设置中你也可以选择相关数据自动清理一下，不会影响设置规则脚本网站数据那些

*****

## 🔦玩机技巧

⚠说明：此技巧不提供解bl和获取root权限教程，太麻烦也有点超出本收藏涵盖内容

> 提前罗列可能需要用到的东西，如果GitHub不会进就用另一个

MT管理器[[官网](https://mt2.cn/download/)]、Shizuku[[GitHub](https://github.com/RikkaApps/Shizuku/releases)|[安卓网](http://m.2265.com/down/308553.html)]、InstallerX[[GitHub](https://github.com/iamr0s/InstallerX/releases)|[安卓网](http://m.2265.com/down/504743.html)]、HyperCeiler[[官网](https://cemiuiler.sevtinge.cc/Download.html)]

#### 1.Shizuku授权教程

> ⚠华为鸿蒙系统阉割掉了开发者选项中的无线调试功能，只能连接电脑借助adb授权，可参考[adb权限激活(B站视频教程)](https://www.bilibili.com/video/BV1cfVxeiE8T)，工具在视频简介  
> 无线调试方案可参考[Shizuku授权软件教程](https://mp.weixin.qq.com/s/V1k1uH6r0cp5DD9P8v46Cw)。原先via内测支持莫奈色的时候就想搞此部分了，结果砍了……还是先留着，毕竟换安装器也用得到

#### 2.规避HyperOS自带安装器的禁止安装(含如何更换系统安装器)

> 触发情况类似下图  
> ![输入图片说明](img/sbmi.png)  
> 事先声明：此为小米系统的限制，via作者已反馈但无回应，所以还请遇到的用户能向小米社区方反馈  
> 解决方案：  
> ①无额外授权、无root权限：下载[国际版via](https://viayoo.com/en/)，小米暂未屏蔽此版本的via。缺点是后续可能被补上  
> ②无root权限：用Shizuku授权第三方安装器(个人使用的是InstallerX)，在软件设置中锁定为默认安装器，替换掉系统自带安装器，来为第三方安装器提供权限  
> ③有root权限：HyperOS系统的手机使用HyperCeiler模块，禁用频繁安装应用检查。另提一嘴，HyperOS遇到的限制问题一般都可以通过这个解决

#### 3.访问via浏览器本地文件夹

> ①国内版：/sdcard/Android/data/mark.via/  
> ②国际版：/sdcard/Android/data/mark.via.gp/  
> (差异自行查看[官方问答](https://viayoo.com/zh-cn/docs/via-for-android-faq.html#orgc5c99e0)) 将上述对应来源的本地文件地址复制，粘贴到MT管理器地址栏上，如果提示无法访问文件夹，使用Shizuku为MT管理器授权即可  
> ![输入图片说明](img/mt.png)  
> 本地可查看的文件  
> ![输入图片说明](img/viafile.png)

*****

## 📚其他

#### 1.套壳浏览器在默认情况下不支持许多Chrome/Chromium原生特性，以下举例重要但via没有实现的部分:

> - [ ] CRX | 浏览器插件/扩展系统 <small>(无法解决，技术不支持)</small> 
> - [ ] PasswordSave | 保存网站密码 <small>(不考虑，详见[官方问答](https://viayoo.com/zh-cn/docs/via-for-android-faq.html#org0e103bd)，可以用第三方密码管理器或脚本)</small>
> - [ ] Devtools | 开发者工具 <small>(似乎无计划，可使用脚本[网页调试](https://greasyfork.org/scripts/475228))</small>
> - [ ] ChromeCast | Google投屏协议 <small>(听说有计划搞投屏，但可能与这个不同)</small>
> - [ ] MaterialYou | 莫奈设计 <small>(曾内测但现暂不考虑，因为似乎无法实现开关)</small>
> - [x] PIP | 原生画中画 <small>(Android版6.0.0版本已基于系统画中画权限实现，不过功能较少)</small>

#### 2.历代webview存在的问题(以AndroidWebview版号为准)

> `100及以前` 存在link引用的css可能无法正确加载的问题，例如百度百科排版异常  
> `105前后(具体不明)` 搜索记录缓存重复写入BrowserMetrics文件夹导致软件占用异常大的问题，在“💡使用技巧”中的4有提及  
> `108至今` Client Hints信息中的操作系统暴露为Android，导致部分网站电脑模式怪异，例如必应Bing  
> `[118,132)` 系统长按菜单的中文缺失问题，例如：Share/Web Search缺失翻译  
> `[126,128)` 系统字体异常问题，例如字体无故变粗/变细  
> `[132,134)` 默认启用基于Vulkan的HWUI渲染引擎，导致主页模糊失效

#### 3.via的白名单网站

> <small>前车之鉴：[猎豹(2013)](https://m.ithome.com/html/066346.htm)/[UC(2015)](http://www.msweekly.com/mobile/show.html?id=40898)/[桔子(2017)](https://m.sohu.com/a/213016655_114760)/[遨游(2018)](https://m.sohu.com/a/253821367_221481/?pvid=000115_3w_a)/[世界之窗(2019)](https://tech.sina.cn/i/gn/2019-01-04/detail-ihqfskcn4151847.d.html)/[双核、极速、小白、星辰(2020)](https://tech.ifeng.com/c/7vJHVsuJ1WS)/[星尘(2021)](https://baijiahao.baidu.com/s?id=1691743082915677777)/[X浏览器(2021)](https://baijiahao.baidu.com/s?id=1706950075530202644)/[傲游(2021)](https://baijiahao.baidu.com/s?id=1711945942788642414)/[雨见(2022)](https://www.ghxi.com/new2022071903.html)/[星愿(2022)](https://baijiahao.baidu.com/s?id=1744181482261724312)</small>  
> Android版4.4.1版本及以后内置了白名单，主要用于规避法律风险，白名单网址仅含以下域名  
> ①资源嗅探白名单  
> v.qq.com,youku.com,iqiyi.com,mgtv.com,bilibili.com,ximalaya.com,film.qq.com  
> ②广告拦截白名单  
> youku.com,iqiyi.com,mgtv.com,qq.com(这个单独说明一下，所有带此部分的域名均是，如：微信文章、腾讯网、腾讯视频)  
> ③脚本白名单  
> v.qq.com,film.qq.com

*****

## 💡有关via的其他推荐

1. [油猴脚本收集列表](script-share.md)([脚本说明](baike/script.md))

2. [广告拦截规则+浏览器标识+搜索引擎等](messy-cont.md)

3. [via小功能或冷门知识](via-help.md)

4. [数据管理(百科中间页)](baike/data.md)

5. [via浏览器各版本的拾穗整理](https://www.sgfox.cc/archives/via-shisui.html)

6. [(via官方教程)使用webdav同步数据](https://viayoo.com/zh-cn/docs/sync-your-data-via-webdav.html)

*****

[返回主页](../README.md)