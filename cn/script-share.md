# via浏览器可用油猴脚本分享

*****

## 注意事项

> 本页仅提供脚本推荐，如果你想入门或完全了解使用方法，可查看→[脚本说明](baike/script.md)  
> 本页GF为GreasyFork(油叉)、GF镜像就是油叉的镜像(如失效可反馈)  
> 脚本名左侧默认无标注，即都可以一起用，有“ᵒʳ”意为不能或不推荐与相似功能脚本一起使用

<details>

  <summary> 近期收录/改动 </summary>

- 添加[优雅的搜索引擎助手](https://update.greasyfork.cc/scripts/12909.user.js)(没特地适配移动网页，但必应和谷歌都是可以正常用的，可用于拦截一些关键词或站点)[12.10]

- 添加[禁止网页双击放大](https://update.greasyfork.cc/scripts/466682.user.js)[12.31]

- 添加[网页加载分析](https://update.greasyfork.cc/scripts/522056.user.js)(测试网页加载速度并显示加载最慢的三个网址的域名)[12.31]

- 添加[移除广告内嵌脚本](https://scriptcat.org/scripts/code/2796/.user.js)(会移除网页内嵌的广告脚本，但网络请求类的还是用[广告拦截](messy-cont.md)才行)[12.31]

- 添加[http资源转https](https://update.greasyfork.cc/scripts/525948.user.js)(http资源不会显示在https网址中，用此脚本替换。可能是为方便考虑限定了域名，可自行修改至全网页)[2.8]

- 添加[网页笔记助手](https://update.greasyfork.cc/scripts/526070)[2.8]

- 添加[优化未登录情况下的BiliBili移动网页端](https://update.greasyfork.cc/scripts/497732.user.js)[2.8]

- 添加[磁力链接预览图片](https://scriptcat.org/scripts/code/2501/.user.js)[3.24]

- 添加[YanDex翻译](https://update.greasyfork.cc/scripts/490152.user.js)[3.29]

- 添加[已访问链接样式修改](https://scriptcat.org/scripts/code/2822/.user.js)[3.29]

- 添加[Css隐藏规则日志](https://scriptcat.org/scripts/code/2928/.user.js)[3.29]

- 添加[Adblock规则分析](https://scriptcat.org/scripts/code/3003/.user.js)[3.29]

</details>

## 脚本分类

分类跳转：[翻译/汉化/语言类(13个)](#%E7%BF%BB%E8%AF%91%E6%B1%89%E5%8C%96%E8%AF%AD%E8%A8%80%E7%B1%BB) | [网页浏览强化类(30个)](#%E7%BD%91%E9%A1%B5%E6%B5%8F%E8%A7%88%E5%BC%BA%E5%8C%96%E7%B1%BB) | [视频/图片/链接类(21个)](#%E8%A7%86%E9%A2%91%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5%E7%B1%BB) | [作用于特定站点类(47个)](#%E4%BD%9C%E7%94%A8%E4%BA%8E%E7%89%B9%E5%AE%9A%E7%AB%99%E7%82%B9%E7%B1%BB) | [需求小众类(18个)](#%E9%9C%80%E6%B1%82%E5%B0%8F%E4%BC%97%E7%B1%BB) | [不再推荐类(8个)](#%E4%B8%8D%E5%86%8D%E6%8E%A8%E8%8D%90%E7%B1%BB)

### 翻译/汉化/语言类

| <small>脚本名及安装</small> | <small>脚本内容介绍</small> |
| --- | --- |
| <small>简约翻译KISS Translator <br> [[GF]](https://update.greasyfork.org/scripts/472840.user.js) <br> [[备用]](https://fishjar.github.io/kiss-translator/kiss-translator.user.js)</small> | <small>[[发布地址]](https://github.com/fishjar/kiss-rules)，无依赖，大小1.7MB。功能齐全，翻译策略默认为先翻译当前视口 后续实时翻译(可更改)，翻译速度快。缺点就是不方便开盖即食，大多需要自己改</small> |  
| <small>沉浸式翻译 <br> [[安装]](https://download.immersivetranslate.com/immersive-translate.user.js)</small> | <small>[[反馈收集]](https://github.com/immersive-translate/immersive-translate/issues)¦[[更新日志]](https://immersivetranslate.com/docs/CHANGELOG)，单依赖，大小2MB+。功能齐全(相比kiss缺少划词翻译)，翻译策略为先翻译当前视口 后续实时翻译(可更改)，翻译速度适中</small> |  
| <small>网页中英双显互译 <br> [[GF]](https://update.greasyfork.org/scripts/469073.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/1116/.user.js)</small> | <small>[[发布地址]](https://scriptcat.org/script-show-page/1116)，多依赖/资源，大小128KB。功能齐全(相比kiss缺少划词翻译)，翻译策略为一整个网页同时翻译(不可更改)，所以在对待长网页时可能会出现卡顿的现象</small> |  
| <small>网页翻译—翻译为中文 <br> [[GF]](https://update.greasyfork.org/scripts/424966.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/424966.user.js)</small> | <small>[[发布地址]](https://gitee.com/Kaiter-Plus/TampermonkeyScript/)，无依赖，156KB。只有通过谷歌翻译将原文变为译文的功能，需要挂</small> |  
| <small>YanDex翻译 <br> [[GF]](https://update.greasyfork.org/scripts/490152.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/490152.user.js)</small> | <small>无依赖，2KB。只有通过Yandex v1翻译将原文变为译文的功能，不需要挂梯</small> |  
| <small>划词翻译:多词典查询 <br> [[GF]](https://update.greasyfork.org/scripts/376313.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/376313.user.js)</small> | <small>[[发布地址]](https://github.com/barrer/tampermonkey-script)，无依赖，大小66KB。仅划词翻译，选中文字后长按再点击翻译按钮即可，第一个按钮是聚合翻译展示多个结果，第二个按钮是谷歌翻译</small> |  
| <small>简繁自由切换 <br> [[GF]](https://update.greasyfork.org/scripts/24300.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/24300.user.js)</small> | <small>[[发布地址]](https://github.com/hoothin/UserScripts)¦[[配置页]](https://greasyfork.org/zh-CN/scripts/24300)，单资源，大小100KB+。目前见过最好且配置方便的替换脚本，进入配置页可自定义</small> |  
| <small>GitHub中文化插件 <br> [[GF]](https://update.greasyfork.org/scripts/435208.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/435208.user.js)</small> | <small>[[发布地址]](https://github.com/maboloshi/github-chinese)，单依赖，大小20KB。对GitHub站点的汉化</small> |  
| <small>E站注射器EhSyringe <br> [[GF]](https://update.greasyfork.org/scripts/407833.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/407833.user.js)</small> | <small>[[发布地址]](https://github.com/EhTagTranslation/EhSyringe)，无依赖，大小1.3MB。对E-Hentai站点的汉化</small> |  
| <small>ᵒʳYoutube双语字幕版 <br> [[GF]](https://update.greasyfork.org/scripts/504796.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/504796.user.js)</small> | <small>单依赖，大小11KB。油管字幕翻译支持任意语言翻译成中文或自行指定目标语言</small> |  
| <small>ᵒʳYoutube双语字幕全平台 <br> [[GF]](https://update.greasyfork.org/scripts/464879.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/464879.user.js)</small> | <small>[[发布地址]](https://github.com/fishjar/kiss-rules)，单依赖，大小5KB。油管字幕翻译支持任意语言翻译成默认语言</small> |  
| <small>朱紫蓝之圆盘汉化 <br> [[GF]](https://update.greasyfork.org/scripts/432623.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2701/.user.js)</small> | <small>[[发布地址]](https://www.smogon.com/forums/threads/3748292/)，单依赖，大小918KB。[网页游戏“宝可梦对战”](https://dex.pokemonshowdown.com/pokemon/)的汉化</small> |  

### 网页浏览强化类

|  |  |
| --- | --- |
| <small>去除链接重定向 <br> [[GF]](https://update.greasyfork.org/scripts/483475.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/483475.user.js)</small> | <small>[[反馈地址]](https://github.com/zhangfangzhou01/remove-link-redirects/issues)，无依赖，大小40KB。将网页内部的链接进行精简，方便快速进入</small> |  
| <small>跳转链接修复 <br> [[GF]](https://update.greasyfork.org/scripts/395970.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/395970.user.js)</small> | <small>[[发布地址]](https://github.com/maomao1996/tampermonkey-scripts)，无依赖，大小27KB。免去拦截页面点击步骤，拦截页面自动跳转</small> |  
| <small>外链自动重定向 <br> [[GF]](https://update.greasyfork.org/scripts/462796.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/462796.user.js)</small> | <small>[[发布地址]](https://github.com/uiliugang/external-link-auto-redirect)，无依赖，大小4KB。默认无行为，在脚本菜单对域名启用后可以免去拦截页面点击步骤</small> |  
| <small>自动无缝翻页 <br> [[GF]](https://update.greasyfork.org/scripts/419215.user.js) <br> [[备用]](https://bitbucket.org/xiu2/userscript/raw/master/Autopage.user.js)</small> | <small>[[发布地址]](https://github.com/XIU2/UserScript)，无依赖，大小178KB。用对应规则给脚本翻页，外置规则可在脚本菜单中更新</small> |  
| <small>东方永页机 <br> [[GF]](https://update.greasyfork.org/scripts/438684.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/438684.user.js)</small> | <small>[[发布地址]](https://github.com/hoothin/UserScripts)¦[[配置页]](https://hoothin.github.io/UserScripts/Pagetual/)，无依赖，大小515KB。用通用规则给网页自动翻页，对应规则得在配置页更新</small> |  
| <small>复制限制解除(本地版) <br> [[GF]](https://update.greasyfork.org/scripts/487607.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/487607.user.js)</small> | <small>无依赖，大小4KB。一定程度上解除网页对选择文本复制的限制</small> |  
| <small>强制复制 <br> [[GF]](https://update.greasyfork.org/scripts/458145.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/458145.user.js)</small> | <small>无依赖，大小1KB。一定程度上解除文本复制限制</small> |  
| <small>网页瞬间加载 <br> [[GF]](https://update.greasyfork.org/scripts/493851.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/493851.user.js)</small> | <small>无依赖，大小131KB。打开网页后开始预加载页内链接，如遇卡顿或闪退可在脚本菜单中配置</small> |  
| <small>网页加速器 <br> [[油小猴]](https://www.youxiaohou.com/instantpage.user.js)</small> | <small>[[发布地址]](https://github.com/syhyz1990/instantpage)，单依赖/资源，大小27KB。悬停在链接上后开始预加载网页，可在脚本菜单中查看加速次数</small> |  
| <small>手机浏览器触摸手势 <br> [[GF]](https://update.greasyfork.org/scripts/375806.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/375806.user.js)</small> | <small>无依赖，大小59KB。手势齐全也支持自定义，缺点可能就是脚本持续活跃，占用和网络消耗大一些</small> |  
| <small>手机助手 <br> [[GF]](https://update.greasyfork.org/scripts/471432.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/471432.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/471432)，无依赖，90KB。网页上会显示，建议看介绍了解</small> |  
| <small>自动展开全文阅读更多 <br> [[GF]](https://update.greasyfork.org/scripts/440400.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/440400.user.js)</small> | <small>[[发布地址]](https://github.com/vicrack/tempermonkey-script)，无依赖，大小80KB。将不完整的文章或网页完全展开</small> |  
| <small>自动展开 <br> [[GF]](https://update.greasyfork.org/scripts/438656.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/725/.user.js) <br> [[备用]](https://cdn.jsdelivr.net/gh/AirBashX/UserScript@master/AutoUnfold.user.js)</small> | <small>[[发布地址]](https://github.com/airbashX/UserScript/)，无依赖，大小30KB。将不完整的文章或网页完全展开</small> |  
| <small>骚扰拦截 <br> [[GF]](https://update.greasyfork.org/scripts/440871.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/724/.user.js) <br> [[备用]](https://cdn.jsdelivr.net/gh/AirBashX/UserScript@master/AnnoyancesInterception.user.js)</small> | <small>[[发布地址]](https://github.com/airbashX/UserScript/)，无依赖，大小36KB。自动拦截或删除下载弹窗、悬浮按钮等元素</small> |  
| <small>移除广告内嵌脚本 <br> [[GF]](https://update.greasyfork.org/scripts/521454.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2796/.user.js)</small> | <small>[[发布地址]](https://www.coolapk.com/feed/61641615?shareKey=MDAwNDI2ZjdjYjUwNjc3M2ZlYzk~)，无依赖，大小19KB。移除网页内嵌的广告、拦截自动跳转</small> |  
| <small>防止未经授权的自动复制 <br> [[GF]](https://update.greasyfork.org/scripts/461625.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/461625.user.js)</small> | <small>无依赖，大小5KB。网页有复制请求时显示小红点提示用户，尽可能拦截某些站点频繁写入剪贴板的行为</small> |  
| <small>ᵒʳ网页调试 <br> [[GF]](https://update.greasyfork.org/scripts/475228.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2537/user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小121KB。支持用Erdua、VConsole、PageSpy、Chii调试网页(脚本菜单中切换)，相当于电脑浏览器的控制台</small> |  
| <small>ᵒʳEruda控制台 <br> [[GF]](https://update.greasyfork.org/scripts/463452.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/1124/.user.js)</small> | <small>无依赖，大小2KB。仅支持使用Erdua调试网页，相当于上方脚本的最简易形态</small> |  
| <small>搜索引擎去广告 <br> [[GF]](https://update.greasyfork.org/scripts/437351.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/437351.user.js)</small> | <small>无依赖，大小138KB。屏蔽、拦截搜索引擎的广告</small> |  
| <small>网站综合去元素框架 <br> [[GF]](https://update.greasyfork.org/scripts/498122.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/498122.user.js)</small> | <small>无依赖，大小281KB。用于其他常用网站，添加站点可在[脚本反馈区](https://greasyfork.org/scripts/498122/feedback)询问</small> |  
| <small>【移动端】百度系优化 <br> [[GF]](https://update.greasyfork.org/scripts/418349.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2529/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91%E7%99%BE%E5%BA%A6%E7%B3%BB%E4%BC%98%E5%8C%96/dist/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91%E7%99%BE%E5%BA%A6%E7%B3%BB%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小1.1MB。对百度系列的所有网站进行处理，功能丰富，可在脚本菜单自定义</small> |  
| <small>优雅的搜索引擎助手 <br> [[GF]](https://update.greasyfork.org/scripts/12909.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/12909.user.js)</small> | <small>[[发布地址]](https://github.com/F9y4ng/GreasyFork-Scripts)，无依赖，大小230KB。主要用于电脑网页，手机网页上必应谷歌可用，主要可用于拦截关键词或站点</small> |  
| <small>HTTP重定向至HTTPS <br> [[GF]](https://update.greasyfork.org/scripts/495629.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/495629.user.js)</small> | <small>无依赖，大小5KB。将HTTP协议的网址自动转为HTTPS</small> |  
| <small>边缘下滑刷新•改 <br> [[GF]](https://update.greasyfork.org/scripts/482126.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/482126.user.js)</small> | <small>无依赖，大小5KB。在页面两侧边缘(距左右边缘各42像素)且在屏幕40%以上的地方，下滑出的刷新标志变蓝后松手即可刷新</small> |  
| <small>记录页面滚动 <br> [[GF]](https://update.greasyfork.org/scripts/499828.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/499828.user.js)</small> | <small>无依赖，大小18KB。记录页面滚动容器和位置，下次页面加载完成时恢复</small> |  
| <small>中英文之间加空白 <br> [[GF]](https://update.greasyfork.org/scripts/470865.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/470865.user.js)</small> | <small>单依赖，大小5KB。在中文与英文/数字间穿插空格，让页面布局更符合直观感受</small> |  
| <small>滚动到顶/底 <br> [[GF]](https://update.greasyfork.org/scripts/482125.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/482125.user.js)</small> | <small>无依赖，大小5KB。一个按钮满足直达网站顶部或底部</small> |  
| <small>黑白网页恢复彩色 <br> [[GF]](https://update.greasyfork.org/scripts/455684.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/455684.user.js)</small> | <small>无依赖，大小10KB。不是不尊重，而是希望能有所选择</small> |  
| <small>强制缩放与桌面模式 <br> [[GF]](https://update.greasyfork.org/scripts/450368.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/450368.user.js)</small> | <small>无依赖，大小5KB。浏览器UA为手机时启用强制缩放，浏览器UA非手机时启用桌面模式，脚本菜单可以单独设置桌面模式宽度或全局宽度</small> |  
| <small>字体渲染(自用脚本) <br> [[GF]](https://update.greasyfork.org/scripts/416688.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/416688.user.js)</small> | <small>[[发布地址]](https://github.com/F9y4ng/GreasyFork-Scripts)，单依赖，大小363KB。将字体渲染的更为清晰，可在脚本菜单中自定义</small> |  
| <small>Mactype助手 <br> [[GF]](https://update.greasyfork.org/scripts/436451.user.js) <br> [[油小猴]](https://www.youxiaohou.com/mactype.user.js)</small> | <small>[[发布地址]](https://github.com/syhyz1990/mactype)，双依赖/资源，大小8KB。将字体加粗、变清晰</small> |  
| <small>网页文字编辑 <br> [[GF]](https://update.greasyfork.org/scripts/490902.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/490902.user.js)</small> | <small>无依赖，大小1KB。脚本菜单中更改网页的可编辑状态，在无法复制的网页效果更佳</small> |  

### 视频/图片/链接类

|  |  |
| --- | --- |
| <small>ᵒʳ俺的手机视频脚本 <br> [[GF]](https://update.greasyfork.org/scripts/456542.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/456542.user.js)</small> | <small>无依赖，大小40KB。专门用于视频功能的脚本，和"手机浏览器触摸手势"、"触摸屏视频优化"一起使用时注意手势冲突问题</small> |  
| <small>ᵒʳ触摸屏视频优化 <br> [[GF]](https://update.greasyfork.org/scripts/405897.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/405897.user.js)</small> | <small>[[发布地址]](https://github.com/HeroChan0330/TouchGesture-For-TamperMonkey)，无依赖，大小49KB。视频中单指左右滑调整进度，单指左侧调整亮度/右侧调整音量，双指长按四倍速…</small> |  
| <small>在线看图工具PicviewerCE+ <br> [[GF]](https://update.greasyfork.org/scripts/24204.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/24204.user.js)</small> | <small>[[发布地址]](https://github.com/hoothin/UserScripts)，三依赖，大小1.1MB。点开图片后支持图片翻转、旋转、缩放、弹出大图、批量保存</small> |  
| <small>图片全载Next <br> [[GF]](https://update.greasyfork.org/scripts/463305.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/463305.user.js)</small> | <small>[[发布地址]](https://github.com/skofkyo/AutoPager/tree/main/CustomPictureDownload)，多依赖/资源，大小1.7MB。主要用于方便看漫画、下载打包图片</small> |  
| <small>漫画织机 <br> [[GF]](https://update.greasyfork.org/scripts/397848.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/397848.user.js)</small> | <small>[[发布地址]](https://github.com/MapoMagpie/eh-view-enhance)，三依赖，大小491KB。漫画阅读+下载，注重体验和对站点的负载控制</small> |  
| <small>ComicRead <br> [[GF]](https://update.greasyfork.org/scripts/374903.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/374903.user.js)</small> | <small>[[发布地址]](https://github.com/hymbz/ComicReadScript)，多资源，大小591KB。主要用于宽屏场景阅读漫画</small> |  
| <small>Adblock规则分析 <br> [[GF]](https://update.greasyfork.org/scripts/530516.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/3003/.user.js)</small> | <small>[[发布地址]](https://scriptcat.org/script-show-page/3003)，无依赖，大小13.2KB。用于分析订阅规则链接是否适合via浏览器</small> |  
| <small>Css隐藏规则日志 <br> [[GF]](https://update.greasyfork.cc/scripts/529261.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2928/.user.js)</small> | <small>[[发布地址]](https://scriptcat.org/script-show-page/2928)，无依赖，大小9KB。用于查看当前站点有哪些规则生效</small> |  
| <small>链接助手 <br> [[GF]](https://update.greasyfork.org/scripts/464541.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/464541.user.js)</small> | <small>[[发布地址]](https://github.com/utags/links-helper)，无依赖，大小75KB。强制新标签页打开链接，让符合条件的链接文本变为超链接</small> |  
| <small>链接地址洗白白 <br> [[GF]](https://update.greasyfork.org/scripts/373270.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/373270.user.js)</small> | <small>[[发布地址]](https://meta.appinn.net/t/topic/7363)，无依赖，大小75KB。将链接缩短为最小可用状态、复制链接、带标题的复制链接…</small> |  
| <small>让链接可点击 <br> [[GF]](https://update.greasyfork.org/scripts/473068.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/473068.user.js)</small> | <small>无依赖，大小5KB。如其名</small> |  
| <small>Linkify Plus Plus <br> [[GF]](https://update.greasyfork.org/scripts/4255.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/4255.user.js)</small> | <small>[[发布地址]](https://github.com/eight04/linkify-plus-plus)，无依赖，大小75KB。只把悬停过的链接变为可点击</small> |  
| <small>网盘链接识别 <br> [[GF]](https://update.greasyfork.org/scripts/445489.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2536/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E7%BD%91%E7%9B%98%E9%93%BE%E6%8E%A5%E8%AF%86%E5%88%AB/dist/%E7%BD%91%E7%9B%98%E9%93%BE%E6%8E%A5%E8%AF%86%E5%88%AB.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖，大小652KB。网页中存在相应网盘链接时出现提醒，几乎支持所有常用网盘</small> |  
| <small>网盘自动填写访问码via <br> [[GF]](https://update.greasyfork.org/scripts/493360.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/493360.user.js)</small> | <small>双依赖，大小72KB。修改自网盘有效性检查，兼容性更好</small> |  
| <small>链接管理 <br> [[GF]](https://update.greasyfork.org/scripts/443670.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/776/.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/443670.user.js)</small> | <small>[[发布地址]](https://github.com/AirBashX/UserScript)，无依赖，大小24KB。让指定站点重定向到正确的链接，支持部分直达中文站点</small> |  
| <small>地址精简 <br> [[GF]](https://update.greasyfork.org/scripts/429294.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/429294.user.js)</small> | <small>无依赖，大小2KB。去除适配站点链接中的冗余部分，缩短链接</small> |  
| <small>ᵒʳ新标签页打开链接 <br> [[GF]](https://update.greasyfork.org/scripts/429714.user.js) <br> [[备用]](https://bitbucket.org/xiu2/userscript/raw/master/TargetBlank.user.js)</small> | <small>[[发布地址]](https://github.com/XIU2/UserScript)，无依赖，大小7KB。强制让链接以新标签形式打开</small> |  
| <small>ᵒʳ智能新标签页打开 <br> [[GF]](https://update.greasyfork.org/scripts/518319.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/518319.user.js)</small> | <small>无依赖，大小8KB。大多数链接新标签打开、导航栏内当前页面打开</small> |  
| <small>ᵒʳ在当前标签页中打开链接 <br> [[GF]](https://update.greasyfork.org/scripts/461352.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/461352.user.js)</small> | <small>无依赖，大小3KB。强制让链接在当前标签打开链接</small> |  
| <small>已访问链接样式修改 <br> [[脚本猫]](https://scriptcat.org/scripts/code/2822/.user.js)</small> | <small>无依赖，大小5KB。让已访问过的链接样式变为红色带下划线，可在脚本菜单中更改</small> |  
| <small>图片样式屏蔽器 <br> [[GF]](https://update.greasyfork.org/scripts/487681.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/487681.user.js)</small> | <small>无依赖，大小4KB。默认无效果，需在脚本菜单中启用，相比"无图模式"多屏蔽了图片的样式</small> |  
| <small>FloatingPlayer悬浮窗播放器 <br> [[GF]](https://update.greasyfork.org/scripts/449323.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/449323.user.js)</small> | <small>无依赖，大小35KB。网页上的悬浮窗视频，但不支持双指缩放、关闭视频、退回网页，个人觉得不太好使</small> |  
| <small>🔐密码填充 <br> [[GF]](https://update.greasyfork.org/scripts/511297.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2379/.user.js)</small> | <small>无依赖，大小16KB。密码自动保存/填充脚本</small> |  
| <small>via浏览器本地密码填充 <br> [[GF]](https://update.greasyfork.org/scripts/476252.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/476252.user.js)</small> | <small>无依赖，大小3KB。</small> |  

### 作用于特定站点类

|  |  |
| --- | --- |
| <small>ᵒʳ蓝奏云重定向+记住密码 <br> [[GF]](https://update.greasyfork.org/scripts/488847.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/488847.user.js)</small> | <small>单依赖，大小13KB。蓝奏云链接重定向至lanzn.com、自动记住并填写蓝奏云密码、直接下载APK文件</small> |  
| <small>ᵒʳ蓝奏云自动点击下载 <br> [[GF]](https://update.greasyfork.org/scripts/489281.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/489281.user.js)</small> | <small>无依赖，大小7KB。类似前者，但前者更适合via</small> |  
| <small>123盘自动填写提取码 <br> [[GF]](https://update.greasyfork.org/scripts/489660.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/489660.user.js)</small> | <small>无依赖，大小2KB。如其名和下面这个脚本合用基本上就是完美体验了</small> |  
| <small>隐藏123云盘广告并调整下载按钮位置 <br> [[GF]](https://update.greasyfork.org/scripts/489267.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/489267.user.js)</small> | <small>无依赖，大小2KB。</small> |  
| <small>知乎修改器移动版 <br> [[GF]](https://update.greasyfork.org/scripts/488508.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/488508.user.js)</small> | <small>[[发布地址]](https://github.com/liuyubing233/zhihu-custom-mobile)，无依赖，大小146KB。知乎为了不让未登录的用户查看文章，已经改过三次了，想看必须登录，此脚本主起辅助作用</small> |  
| <small>【移动端】微博优化 <br> [[GF]](https://update.greasyfork.org/scripts/480094.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2530/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91%E5%BE%AE%E5%8D%9A%E4%BC%98%E5%8C%96/dist/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91%E5%BE%AE%E5%8D%9A%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小109KB。劫持登录，解锁视频清晰度...</small> |  
| <small>简书优化 <br> [[GF]](https://update.greasyfork.org/scripts/485483.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2535/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E7%AE%80%E4%B9%A6%E4%BC%98%E5%8C%96/dist/%E7%AE%80%E4%B9%A6%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小49KB。自动展开全文、允许复制文字、劫持唤醒APP...</small> |  
| <small>CSDN优化 <br> [[GF]](https://update.greasyfork.org/scripts/406136.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2531/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/CSDN%E4%BC%98%E5%8C%96/dist/CSDN%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小122KB。屏蔽登录弹窗、自动展开全文、允许复制...</small> |  
| <small>CSDN超强防护 <br> [[GF]](https://update.greasyfork.org/scripts/458601.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/458601.user.js)</small> | <small>无依赖，大小4KB。自动展开内容，免登录任意复制，去除广告，增加搜索框</small> |  
| <small>GreasyFork优化 <br> [[GF]](https://update.greasyfork.org/scripts/475722.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2532/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/GreasyFork%E4%BC%98%E5%8C%96/dist/GreasyFork%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小527KB。自动登录账号、美化页面、脚本列表双列...</small> |  
| <small>大人的Greasyfork <br> [[GF]](https://update.greasyfork.org/scripts/23840.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/23840.user.js)</small> | <small>[[发布地址]](https://github.com/hoothin/UserScripts)，无依赖，大小28KB。Greasyfork搜索结果中添加Sleazyfork、增加评分与版本号、访问匿名不可用脚本时跳转至Sleazyfork</small> |  
| <small>移动百度优化 <br> [[GF]](https://update.greasyfork.org/scripts/436841.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/436841.user.js)</small> | <small>单依赖，大小12KB。只在百度引擎里加了一个搜索框，避免因为UA没有搜索框的尴尬</small> |  
| <small>ᵒʳ手机百度搜索净化 <br> [[GF]](https://update.greasyfork.org/scripts/467204.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/467204.user.js)</small> | <small>无依赖，大小3KB。隐藏广告和推荐内容、禁止搜索结果自动播放、禁止复制粘贴板口令</small> |  
| <small>ᵒʳ禁止百度搜索自动播放视频和禁止粘贴板口令 <br> [[GF]](https://update.greasyfork.org/scripts/470469.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/470469.user.js)</small> | <small>无依赖，大小1.4KB。禁止搜索结果自动播放、禁止复制粘贴板口令</small> |  
| <small>ᵒʳ【移动端】bilibili优化 <br> [[GF]](https://update.greasyfork.org/scripts/494644.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2523/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91bilibili%E4%BC%98%E5%8C%96/dist/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91bilibili%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小624KB。播放器优化、推荐视频、美化显示、番剧解锁...</small> |  
| <small>ᵒʳ优化未登录情况下的BiliBili移动网页端 <br> [[GF]](https://update.greasyfork.org/scripts/497732.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/497732.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/497732)，多依赖，大小61KB。主要是优化未登录情况下的体验</small> |  
| <small>ᵒʳbilibili移动端Lite <br> [[GF]](https://update.greasyfork.org/scripts/468246.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/468246.user.js)</small> | <small>[[发布地址]](https://github.com/jk278/bilibili-mobile)，无依赖，大小10KB。适用移动端网页，功能少点</small> |  
| <small>bilibili移动端 <br> [[GF]](https://update.greasyfork.org/scripts/490548.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/490548.user.js)</small> | <small>[[发布地址]](https://github.com/jk278/bilibili-mobile)，单依赖，大小177KB。将电脑网页变为适配移动网页的样式，与上一个脚本配套</small> |  
| <small>抖音优化 <br> [[GF]](https://update.greasyfork.org/scripts/494643.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2534/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E6%8A%96%E9%9F%B3%E4%BC%98%E5%8C%96/dist/%E6%8A%96%E9%9F%B3%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小366KB。伪装登录、视频过滤、禁止自动播放...</small> |  
| <small>【移动端】小红书优化 <br> [[GF]](https://update.greasyfork.org/scripts/483960.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2538/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%98%E5%8C%96/dist/%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小105KB。允许复制、禁止唤醒App、修复正确跳转...</small> |  
| <small>手机网页版IT之家去除广告和干扰 <br> [[GF]](https://update.greasyfork.org/scripts/396190.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/396190.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/396190)，无依赖，大小2KB。去除广告、文章页去除分享、评分相关文章等</small> |  
| <small>💡WebPreview-信息直达 <br> [[GF]](https://update.greasyfork.org/scripts/462463.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2085/.user.js)</small> | <small>三依赖，大小20KB。主要适合电脑网页，手机网页上有给谷歌、必应添加预览网页内容按钮</small> |  
| <small>Xbox CLoud Gaming 优化整合 <br> [[GF]](https://update.greasyfork.org/scripts/455741.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/455741.user.js)</small> | <small>单依赖，大小162KB。[Xbox云游戏](https://www.xbox.com/en-us/play)在线玩</small> |  
| <small>【移动端】MT论坛优化 <br> [[GF]](https://update.greasyfork.org/scripts/513866.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2524/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91MT%E8%AE%BA%E5%9D%9B%E4%BC%98%E5%8C%96/dist/%E3%80%90%E7%A7%BB%E5%8A%A8%E7%AB%AF%E3%80%91MT%E8%AE%BA%E5%9D%9B%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小548KB。仅移动网页自动签到、动态头像上传、评论过滤器、拦截附件...</small> |  
| <small>MT论坛优化 <br> [[GF]](https://update.greasyfork.org/scripts/513868.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2533/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/MT%E8%AE%BA%E5%9D%9B%E4%BC%98%E5%8C%96/dist/MT%E8%AE%BA%E5%9D%9B%E4%BC%98%E5%8C%96.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，多依赖/资源，大小235KB。仅电脑网页自动签到、动态头像上传、评论过滤器、拦截附件...</small> |  
| <small>移动端微软Rewards每日任务脚本 <br> [[GF]](https://update.greasyfork.org/scripts/480355.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/480355.user.js)</small> | <small>[[发布地址]](https://github.com/huaisha1224/Microsoft-Rewards)，无依赖，大小9KB。适用移动网页完成微软Rewards每日搜索任务</small> |  
| <small>Microsoft每日任务脚本 <br> [[GF]](https://update.greasyfork.org/scripts/477107.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/477107.user.js)</small> | <small>[[发布地址]](https://github.com/huaisha1224/Microsoft-Rewards)，无依赖，大小10KB。适用电脑网页完成微软Rewards每日搜索任务</small> |  
| <small>V2Next-Mobile <br> [[GF]](https://update.greasyfork.org/scripts/485356.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/485356.user.js)</small> | <small>[[发布地址]](https://github.com/zyronon/V2Next)，双依赖，大小341KB。V2EX论坛移动网页优化</small> |  
| <small>V2Next <br> [[GF]](https://update.greasyfork.org/scripts/458024.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/458024.user.js)</small> | <small>[[发布地址]](https://github.com/zyronon/V2Next)，三依赖，大小382KB。V2EX论坛电脑网页优化</small> |  
| <small>Pixiv增强 <br> [[GF]](https://update.greasyfork.org/scripts/34153.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/34153.user.js)</small> | <small>[[发布地址]](https://github.com/Ahaochan/Tampermonkey)，多依赖，大小64KB。</small> |  
| <small>Github搜索净化 <br> [[GF]](https://update.greasyfork.org/scripts/473912.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/473912.user.js)</small> | <small>[[发布地址]](https://github.com/BonjourFeng/Github-Search-Purification)，无依赖，大小37KB。去除400+敏感仓库，清净页面</small> |  
| <small>YouTube视频&音乐&儿童广告拦截 <br> [[GF]](https://update.greasyfork.org/scripts/480192.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2169/.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/480192)，无依赖，大小251KB。全面、体量大</small> |  
| <small>YouTube去广告 <br> [[GF]](https://update.greasyfork.org/scripts/459541.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/459541.user.js)</small> | <small>[[发布地址]](https://github.com/iamfugui/youtube-adb)，无依赖，大小12KB。简洁、仅移除广告</small> |  
| <small>Twitterᴾˡᵘˢ <br> [[GF]](https://update.greasyfork.org/scripts/387969.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/387969.user.js)</small> | <small>[[发布地址]](https://github.com/Pixmi/twitter-plus)，单依赖，大小6KB。移除广告，图片恢复原清晰度</small> |  
| <small>Twitter/X媒体下载 <br> [[GF]](https://update.greasyfork.org/scripts/495368.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/495368.user.js)</small> | <small>无依赖，大小28KB。帖子右下角添加下载按钮</small> |  
| <small>Twitter/X移除敏感内容提醒 <br> [[GF]](https://update.greasyfork.org/scripts/492130.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/492130.user.js)</small> | <small>无依赖，大小1KB。</small> |  
| <small>ColaManga浏览增强 <br> [[GF]](https://update.greasyfork.org/scripts/488622.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/488622.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/488622)，单依赖，大小25KB。</small> |  
| <small>DeepL翻译文件 <br> [[安装]](https://doc.deeplx.net/deepl-translator/deepl-translator.user.js)</small> | <small>双依赖，大小201KB。初次进入[Deepl翻译页面](https://www.deepl.com)会提示会话过期，刷新再进即可激活无限翻译</small> |  
| <small>南加北加论坛强化脚本(凛+) <br> [[GF]](https://update.greasyfork.org/scripts/454120.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/454120.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/454120)，无依赖，大小692KB。</small> |  
| <small>水木社区web转APP <br> [[GF]](https://update.greasyfork.org/scripts/466317.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/466317.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/466317)，无依赖，大小1KB。将网页端适配为手机形态</small> |  
| <small>Atcoder Better! <br> [[GF]](https://update.greasyfork.org/scripts/471106.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/471106.user.js)</small> | <small>[[发布地址]](https://github.com/beijixiaohu/OJBetter)，多依赖/资源，大小543KB。</small> |  
| <small>AcWing Better! <br> [[GF]](https://update.greasyfork.org/scripts/464981.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/464981.user.js)</small> | <small>[[发布地址]](https://github.com/beijixiaohu/OJBetter)，单依赖，大小42KB。</small> |  
| <small>Codeforces Better! <br> [[GF]](https://update.greasyfork.org/scripts/465777.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/465777.user.js)</small> | <small>[[发布地址]](https://github.com/beijixiaohu/OJBetter)，多依赖/资源，大小529KB。</small> |  
| <small>追放社区宽屏页面适配 <br> [[GF]](https://update.greasyfork.org/scripts/505037.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/505037.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/505037)，无依赖，大小6KB。仅适合平板等宽屏场景</small> |  
| <small>妖火网增强脚本Plus <br> [[GF]](https://update.greasyfork.org/scripts/504289.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/504289.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/504289)，无依赖，大小90KB。</small> |  
| <small>Steam、Epic历史价格查询 <br> [[GF]](https://update.greasyfork.org/scripts/471532.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/471532.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/471532)，无依赖，大小7KB。</small> |  
| <small>为Gitee页面生成菜单 <br> [[GF]](https://update.greasyfork.org/scripts/513028.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/513028.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/513028)，无依赖，大小6KB。</small> |  
| <small>夸克书签导出 <br> [[Gitee]](https://gitee.com/mulingLHY/shared_sources/raw/master/convertBookmark_Quark2Via.user.js)</small> | <small>[视频演示](https://m.bilibili.com/video/BV1DM411R7vP)，无依赖，大小6KB。通过夸克的书签同步记录将书签导出</small> |  
| <small>谷歌下载修复 <br> [[本地下载]](https://www.lanzn.com/tp/i7qKP2qab3yh)</small> | <small>[[发布地址]](https://www.coolapk.com/feed/60701316?shareKey=Y2VhYzEwYzkxYzdlNjc2ZjlhMDQ~)，无依赖，大小3KB。修复[谷歌字体](https://fonts.google.com/)和[谷歌联系人](https://contacts.google.com/)无法下载的问题</small> |  

### 需求小众类

|  |  |
| --- | --- |
| <small>护眼模式 <br> [[GF]](https://update.greasyfork.org/scripts/426377.user.js) <br> [[备用]](https://bitbucket.org/xiu2/userscript/raw/master/DarkMode.user.js)</small> | <small>[[发布地址]](https://github.com/XIU2/UserScript)，无依赖，大小32KB。</small> |  
| <small>🌙 高级定制网页护眼模式🌙 <br> [[GF]](https://update.greasyfork.org/scripts/485513.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/485513.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/485513)，无依赖，大小544KB。</small> |  
| <small>GM Api Test <br> [[GF]](https://update.greasyfork.org/scripts/520327.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/2539/.user.js) <br> [[备用]](https://fastly.jsdelivr.net/gh/WhiteSevs/TamperMonkeyScript/scripts-vite/%E6%B2%B9%E7%8C%B4Api%E6%B5%8B%E8%AF%95/dist/GM%20Api%20Test.user.js)</small> | <small>[[发布地址]](https://github.com/WhiteSevs/TamperMonkeyScript)，单依赖/资源，大小1.1MB。测试脚本管理器对油猴Api支持情况</small> |  
| <small>双指缩放网页 <br> [[GF]](https://update.greasyfork.org/scripts/507136.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/507136.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/507136)，无依赖，大小4KB。通过缩放元素大小规避禁止缩放限制</small> |  
| <small>http资源转https <br> [[GF]](https://update.greasyfork.org/scripts/525948.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/525948.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/525948)，无依赖，大小1KB。默认只适配酷安，需脚本设置中自行修改至全网页</small> |  
| <small>仿via资源嗅探 <br> [[GF]](https://update.greasyfork.org/scripts/471390.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/471390.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/471390)，无依赖，大小10KB。可在资源嗅探白名单网页或者iOS版上使用</small> |  
| <small>禁止网页双击放大 <br> [[GF]](https://update.greasyfork.org/scripts/466682.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/466682.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/466682)，无依赖，大小3KB。</small> |  
| <small>磁力链接预览图片 <br> [[脚本猫]](https://scriptcat.org/scripts/code/2501/.user.js)</small> | <small>[[发布地址]](https://scriptcat.org/script-show-page/2501)，无依赖，大小17KB。</small> |  
| <small>网页笔记助手 <br> [[GF]](https://update.greasyfork.org/scripts/526070.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/526070.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/526070)，无依赖，大小18KB。</small> |  
| <small>浏览器背景 <br> [[GF]](https://update.greasyfork.org/scripts/493937.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/493937.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/493937)，无依赖，大小5KB。将浏览器的背景变成某只笨蛋~，可以按注释自行更换图片</small> |  
| <small>网页加载分析 <br> [[GF]](https://update.greasyfork.org/scripts/522056.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/522056.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/522056)，无依赖，大小3KB。测试网页加载速度并显示加载最慢的三个域名</small> |  
| <small>Userscript+-- <br> [[GF]](https://update.greasyfork.org/scripts/409727.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/409727.user.js)</small> | <small>单资源，大小3KB。在脚本菜单中显示当前站点的可能适用脚本数，点击可跳转GreasyFork搜索</small> |  
| <small>网页看板娘 <br> [[GF]](https://update.greasyfork.org/scripts/483088.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/483088.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/483088)，无依赖，大小2KB。在浏览器窗口上养一只赛博老婆</small> |  
| <small>自动滚动：双击切换滚动状态 <br> [[GF]](https://update.greasyfork.org/scripts/492138.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/492138.user.js)</small> | <small>，无依赖大小3KB。适合看小说时使用</small> |  
| <small>保持屏幕常亮：唤醒锁定 <br> [[GF]](https://update.greasyfork.org/scripts/494378.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/494378.user.js)</small> | <small>无依赖，大小2KB。</small> |  
| <small>自动滚动配置 <br> [[GF]](https://update.greasyfork.org/scripts/487297.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/487297.user.js)</small> | <small>无依赖，大小9KB。在页面上添加可配置自动滚动的设置</small> |  
| <small>点击波纹特效 <br> [[GF]](https://update.greasyfork.org/scripts/482952.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/482952.user.js)</small> | <small>无依赖，大小6KB。更直观的触屏点击效果，可在脚本菜单自定义</small> |  
| <small>帧率FPS显示 <br> [[GF]](https://update.greasyfork.org/scripts/498194.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/1918/.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/498194)，无依赖，大小3KB。</small> |  
| <small>ip信息检测ip-checker <br> [[GF]](https://update.greasyfork.org/scripts/497045.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/497045.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/497045)，无依赖，大小25KB。</small> |  

### 不再推荐类

|  |  |
| --- | --- |
| <small>MutliQRCode扫描页内二维码 <br> [[GF]](https://update.greasyfork.org/scripts/467200.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/467200.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/467200)，单依赖，大小23KB。Android版5.2.0及以后，长按任意图片，点击"扫描二维码"</small> |  
| <small>大声朗读-TTS辅助阅读 <br> [[GF]](https://update.greasyfork.org/scripts/429810.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/429810.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/429810)，三依赖，大小49KB。Android版5.3.0及以后，长按菜单中的"设置"将"朗读网页"移入</small> |  
| <small>通用阅读器 <br> [[GF]](https://update.greasyfork.org/scripts/377230.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/377230.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/377230)，无依赖，大小21KB。Android版5.4.0及以后，长按菜单中的"设置"将"阅读模式"移入 或 点击地址栏左侧图标再点击"打开阅读模式"</small> |  
| <small>Circle阅读助手脚本版 <br> [[GF]](https://update.greasyfork.org/scripts/440132.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/440132.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/440132)，无依赖，大小46KB。</small> |  
| <small>滚动条-新 <br> [[GF]](https://update.greasyfork.org/scripts/465037.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/465037.user.js)</small> | <small>无依赖，大小6KB。Android版5.6.0及以后，默认在网页右侧</small> |  
| <small>聚合搜索引擎切换导航[手机版][移动端] <br> [[GF]](https://update.greasyfork.org/scripts/462130.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/462130.user.js)</small> | <small>[[发布地址]](https://greasyfork.org/scripts/462130)，无依赖，大小25KB。Android版5.8.0及以后，默认开启，设置＞通用＞搜索设置＞搜索工具栏</small> |  
| <small>搜索引擎切换器2(侧栏版) <br> [[GF]](https://update.greasyfork.org/scripts/489235.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/489235.user.js)</small> | <small>无依赖，大小18KB。</small> |  
| <small>all-search全搜 <br> [[GF]](https://update.greasyfork.org/scripts/397993.user.js) <br> [[脚本猫]](https://scriptcat.org/scripts/code/477/.user.js)</small> | <small>[[发布地址]](https://github.com/all-search/all-search)，双依赖，大小156KB。</small> |  
| <small>WebRTC禁用脚本 <br> [[GF]](https://update.greasyfork.org/scripts/495166.user.js) <br> [[GF镜像]](https://update.greasyfork.cc/scripts/495166.user.js)</small> | <small>无依赖，大小1KB。Android版5.9.0及以后，默认关闭，设置＞隐私＞禁用webRTC</small> |  

*****

[返回脚本介绍](baike/script.md)|[返回主页](../README.md)