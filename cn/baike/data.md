# 数据管理

*****

本页目录: [🌐Webdav同步](#Webdav%E5%90%8C%E6%AD%A5) | [ 🔄跨浏览器备份](#%E8%B7%A8%E6%B5%8F%E8%A7%88%E5%99%A8%E5%A4%87%E4%BB%BD) | [🤔备份差异](#%E5%A4%87%E4%BB%BD%E5%B7%AE%E5%BC%82) | [🌀其他同步相关问题](#%E5%85%B6%E4%BB%96%E5%90%8C%E6%AD%A5%E7%9B%B8%E5%85%B3%E9%97%AE%E9%A2%98)

## 🌐Webdav同步

> 使用方法：设置＞通用＞同步，点击右上角“WEBDAV”，当右上角是“云同步”时，则可根据教程开始

自Android版via4.7.0(iOS版暂不支持)更新到现在，webdav同步是完全可以替代via自身的云同步，可参考[→Via官方教程←](https://viayoo.com/zh-cn/docs/sync-your-data-via-webdav.html)以及尝试跨浏览器同步[chrome与via同步书签](https://blog.qianxun.site/%E6%95%99%E7%A8%8B/pc%E7%AB%AFchrome%E4%BD%BF%E7%94%A8floccus%E6%89%A9%E5%B1%95%E5%92%8C%E7%A7%BB%E5%8A%A8%E7%AB%AFvia%E5%90%8C%E6%AD%A5%E4%B9%A6%E7%AD%BE/)

## 🔄跨浏览器备份

在[chrome与via同步书签](https://blog.qianxun.site/%E6%95%99%E7%A8%8B/pc%E7%AB%AFchrome%E4%BD%BF%E7%94%A8floccus%E6%89%A9%E5%B1%95%E5%92%8C%E7%A7%BB%E5%8A%A8%E7%AB%AFvia%E5%90%8C%E6%AD%A5%E4%B9%A6%E7%AD%BE/)中已经有展示webdav同步的能力。对于不支持webdav的浏览器，备份书签还是可以轻易做到的，在 设置＞通用＞导入/备份书签 中，via可以导入/导出书签(格式为兼容性强的html)  

例如：使用[夸克书签导出脚本](https://gitee.com/mulingLHY/shared_sources/raw/master/convertBookmark_Quark2Via.user.js)演示的[B站视频教程](https://www.bilibili.com/video/BV1DM411R7vP/)

## 🤔备份差异

仅via自身支持的备份数据来说：导入/导出数据＞webdav同步＞via的云同步。下方表格展示详细数据
 
| <small>数 据 ＼ 类 型</small> | <small>导出/导入<br>数据</small> | <small>WEBDAV<br>同步</small> | <small>Via云<br>同步</small>      |
|---------------|----------------|---------------|------------------|
| <small>设置项开关</small> | <small>✅支持</small> | <small>✅支持</small> | <small>✅支持</small>        |
| <small>操作设定</small> | <small>✅支持</small> | <small>✅支持</small> | <small>✅支持</small>        |
| <small>阅读模式设置</small> | <small>✅支持</small> | <small>✅支持</small> | <small>✅支持</small>        |
| <small>主页定制代码</small> | <small>✅支持</small> | <small>✅支持</small> | <small>✅支持</small>        |
| <small>自定搜索引擎</small> | <small>✅支持</small> | <small>✅支持</small> | <small>❓仅当前</small>       |
| <small>自定标识(UA)</small> | <small>✅支持</small> | <small>✅支持</small> | <small>❓仅当前</small>       |
| <small>书签</small> | <small>✅支持</small> | <small>✅支持</small> | <small>⚠️限三百</small>     |
| <small>规则订阅</small> | <small>✅支持</small> | <small>❓仅链接</small> | <small>❓仅链接</small>       |
| <small>主页收藏</small> | <small>✅支持</small> | <small>✅支持</small> | <small>❌不支持</small>       |
| <small>用户脚本</small> | <small>✅支持¹</small> | <small>❓支持²</small> | <small>❌不支持</small>       |
| <small>历史</small> | <small>✅支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |
| <small>自定义规则</small> | <small>✅支持</small> | <small>❌不支持</small> | <small>✅支持</small>       |
| <small>关闭的标签页</small> | <small>✅支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |
| <small>主页背景图</small> | <small>✅支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |
| <small>主页图片Logo</small> | <small>✅支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |
| <small>主页收藏图标</small> | <small>✅支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |
| <small>皮肤/图标包</small> | <small>❌不支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |
| <small>离线页面</small> | <small>❌不支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |
| <small>下载记录</small> | <small>❌不支持</small> | <small>❌不支持</small> | <small>❌不支持</small>       |

> 支持¹：可以本地文件完整备份脚本，但如果脚本有依赖部分，则需要手动更新一次脚本才能正常使用  
> 支持²：脚本自身有更新链接的，仅恢复链接(脚本显示为灰色)，需手动更新一次脚本才能正常使用；脚本自身无更新链接的，可以完整备份无依赖的脚本

## 🌀其他同步相关问题

在[官方问答](https://viayoo.com/zh-cn/docs/via-for-android-faq.html#orgbd26542)中也有相关部分，这里仅做补充

1.在[Via云网址](https://app.viayoo.com)中可以测试账号密码是否正确及修改密码
> 毕竟via设置中的云同步如果账号不存在会新建账号，对于不太记忆账号或账号多了的用户容易起到误导

2.iOS版via暂不支持iCloud同步以外的同步方式且本人无iOS设备，所以备份差异并未展示iCloud同步，如有人辅助我完成，自然是乐意至极

*****

[返回问答](../FAQ.md) | [返回主页](../../README.md)