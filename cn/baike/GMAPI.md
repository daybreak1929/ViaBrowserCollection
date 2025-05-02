# 油猴脚本API参考

本文整理了大部分油猴API的使用方法，并且附上了每个方法的代码示例。除此之外您可以安装油猴脚本API示例脚本在支持用户脚本的浏览器中进行测试。

> 本文照搬自 [油猴脚本API参考|X浏览器]-[[官网](https://www.xbext.com/docs/user-script-api-reference.html)|[GitHub](https://github.com/examplecode/tampermonkey-api-reference)]，因为写的好又全，这里仅做删改无关信息

<br>

本页目录：[元数据 ](#%E5%85%83%E6%95%B0%E6%8D%AEmeta) | [ 油猴API](#%E6%B2%B9%E7%8C%B4api) <br>
[GM_addStyle](#gm_addstyle) | [ GM_addElement](#gm_addelement) | [ GM_setValue](#gm_setvalue) | [ GM_getValue](#gm_getvalue) | [ GM_listValues](#gm_listvalues) | [ GM_deleteValue](#gm_deletevalue) | [ GM_addValueChangeListener](#gm_addvaluechangelistener) | [ GM_removeValueChangeListener](#gm_removevaluechangelistener)|
[GM_notification](#gm_notification) | [ GM_setClipboard](#gm_setclipboard) | [ GM_registerMenuCommand](#gm_registermenucommand) | [ GM_unregisterMenuCommand](#gm_unregistermenucommand) | [ GM_openInTab](#gm_openintab) | [ GM_download](#gm_download) | [ GM_getResourceText](#gm_getresourcetext) | [ GM_getResourceURL](#gm_getresourceurl)|
[GM_xmlhttpRequest](#gm_xmlhttprequest) | [ urlchange](#urlchange) | [ GM_cookie](#gm_cookie) | [ GM_info](#gm_info)

## 元数据(Meta)

元数据通常放置在整个脚本的开头，主要包括脚本名称、简介、作者、版本号、运行方式、所依赖的库文件声明等。

下面是一个脚本的元数据声明的例子。

```javascript
// ==UserScript==
// @name         Say hello
// @namespace    com.example.hello
// @version      0.1
// @description  When you open the site example.com it says "HELLO"
// @author       You
// @match        www.example.com
// ==/UserScript==
```

| 信息 | 描述 |
| ------ | ------ |
| @name | 脚本的名称 |
| @namespace | 脚本的的命名空间，可以是一个唯一标识或则网址 |
| @description | 脚本的简介，描述脚本的用法及功能等 |
| @icon | 为脚本定制一个图标，显示在脚本列表以及浏览器扩展菜单中的图标。可以是一个url图标资源或者Base64编码的 Data URI。 |
| @author | 脚本的作者姓名或昵称 |
| @version | 当前脚本的版本号 |
| @match | 定义脚本的作用域，只在匹配的网址或域名才执行脚本，此标记在元数据中可以有多行声明。即[脚本编辑设置](script.md#%E8%84%9A%E6%9C%AC%E7%BC%96%E8%BE%91%E8%AE%BE%E7%BD%AE)中的匹配 |
| @include | 和@match类似，用来描述脚本的作用域，可以在元数据中存在多行声明。 |
| @exclude | 用于排除一些URL, 即使@match和@incluide已经指定匹配，可以在元数据中存在多行声明。即[脚本编辑设置](script.md#%E8%84%9A%E6%9C%AC%E7%BC%96%E8%BE%91%E8%AE%BE%E7%BD%AE)中的排除 |
| @require | 该脚本执行前，需要依赖第三方的库，可以在元数据中存在多行声明。即[脚本编辑设置](script.md#%E8%84%9A%E6%9C%AC%E7%BC%96%E8%BE%91%E8%AE%BE%E7%BD%AE)中的“依赖” |
| @resource | 该脚本执行需要依赖的一些资源文件，如CSS、图片资源等，可以在元数据中存在多行声明。即[脚本编辑设置](script.md#%E8%84%9A%E6%9C%AC%E7%BC%96%E8%BE%91%E8%AE%BE%E7%BD%AE)中的“资源” |
| @run-at | 指定脚本的执行时机，不同的应用场景可能需要不同的执行时机，即[脚本编辑设置](script.md#%E8%84%9A%E6%9C%AC%E7%BC%96%E8%BE%91%E8%AE%BE%E7%BD%AE)中的“运行时机”。@run-at的取值可以参见下表 |
| @grant | 在元数据中声明使用了哪些API函数 |

@run-at的取值如下

| 取值 | 描述 |
| ------ | ------ |
| document-start | 指定脚本在DOM树开始的时候执行，需要脚本尽早执行的时候添加此声明。 |
| document-end | 指定脚本在DOM数据加载完毕的时候执行 |
| document-idle | 页面加载完毕的时候执行。当元数据没有@run-at声明时，脚本默认在此时机执行 |

## 油猴API 

### GM_addStyle

#### 描述

为页面添加样式一段CSS样式。

#### 语法

```javascript
function GM_addStyle (cssString)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| cssString | 字符串 | 字符串样式表 |

#### 示例
```javascript
 GM.addStyle('#note{color: white; background: #3385ff!important;border-bottom: 1px solid #2d7');
```
*****

### GM_addElement

#### 描述

增加一个页面元素，可以指定父节点，不指定父节点其节点为根元素。

#### 语法

```javascript
function GM_addElement(tagName, attributes)
```

或者

```javascript
function GM_addElement(parentNode,tagName, attributes)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| tagName | 字符串 | 元素名称 |
| attributes | 对象 | 属性名称/数值对 |
| parentNode | 对象 | 新建元素的父节点 |

#### 示例

```javascript

GM_addElement('script', {
  textContent: 'window.foo = "bar";'
});

GM_addElement('script', {
  src: 'https://example.com/script.js',
  type: 'text/javascript'
});

GM_addElement(document.getElementsByTagName('div')[0], 'img', {
  src: 'https://example.com/image.png'
});

GM_addElement(shadowDOM, 'style', {
  textContent: 'div { color: black; };'
});
```

*****

### GM_setValue

#### 描述

通过指定的键值保存数据到浏览器本地存储中。

#### 语法

```javascript
function GM_setValue(name,value)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| name | 字符串 | 字符串键值 |
| value | 任意类型 | 可以是整数、字符串、布尔类型、对象等任意数据 |

#### 示例

```javascript
GM_setValue("foo", "bar");
GM_setValue("count", 100);
GM_setValue("active", true);
GM_setValue("data", {
  name: 'Andy',
  age: 18
});
```

### GM_getValue

#### 描述

从浏览器的本地存储获取一个值。

#### 语法

```javascript
function GM_getValue(name, defaultValue)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------| ------| ------ |
| name | 字符串 | 字符串键值 |
| defaultValue | 任意类型 | 可选项，如果键值从没有被设置过，返回默认值 |

#### 返回值

如果键值被设置过，返回当初设置的数据类型。

#### 示例

```javascript
GM_setValue("foo", "bar");
GM_setValue("count", 100);
GM_setValue("active", true);
GM_setValue("data", {
  name: 'Andy',
  age: 18
});

var info = `foo = ${GM_getValue("foo")}
          count = ${GM_getValue("count")}
          active = ${GM_getValue("active")}
          data.name =  ${GM_getValue("data").name}`;                   
alert(info);
```
*****

### GM_listValues

#### 描述

返回使用所以GM_setValue 设置的键值列表。

#### 语法

```javascript
function GM_listValues()
```

#### 示例

```javascript
GM_setValue("foo", "bar");
GM_setValue("count", 100);
GM_setValue("active", true);
GM_setValue("data", {
name: 'Andy',
age: 18
});
alert(GM_listValues());
```
*****

### GM_deleteValue

#### 描述

删除通过GM_setValue 方法设置的键值。

#### 语法

```javascript
function GM_deleteValue(name)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| name | 字符串 | 字符串键值 |

#### 示例
```javascript 
GM_deleteValue("foo");
```

``` javascript
let keys =  GM_listValues();
for (let key of keys) {
  GM_deleteValue(key);
}
```

*****

### GM_addValueChangeListener

#### 描述

用来监听通过GM_setValue设置的键值对的改变

#### 语法

```javascript
function GM_addValueChangeListener(name,callback);

```

#### 参数   

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| name | 字符串 | 字符串键值 |
| callback | 回调函数 | 当指定的键值改变时回调此函数 |

##### callback 参数列表

- **name** - 字符串类型，键值名称
- **oldValue** - 任意类型 ，以前的键值
- **newValue** - 任意类型 ，新的键值。
- **remote** - 布尔类型，来自当前标签的回调还是垮标签的回调（目前没有实现跨标签回调）

#### 返回值

返回监听的回调函数的id,用于以后通过GM_removeValueChangeListener 方法删除回调函数。

#### 示例

``` javascript
   listener_id = GM_addValueChangeListener("foo",function(name,old_value,new_value,remote) {
        alert("Value Changed:" + name + ":" + old_value + "=>" + new_value);
    });
```
*****

### GM_removeValueChangeListener

#### 描述

用来删除通过GM_addValueChangeListener添加的监听回调

#### 语法

```javascript
function GM_removeValueChangeListener(listener_id);

```

#### 参数   

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| listener_id | 回调函数Id | GM_removeValueChangeListener返回的回调函数id |

#### 示例

``` javascript
 GM_removeValueChangeListener(listener_id);
```

*****

### GM_notification

#### 描述
显示一条通知消息

#### 语法

```javascript
function GM_notification(details)
```
或者

```javascript
function GM_notification(text, title, image, onclick )
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| details | 对象 | 一个包含text字段和ondone,onclick回调函数字段的对象 |
| text | 字符串 | 文本内容 |
| title | 字符串 | 参数为了兼容，手机端目前未实现 |
| Image | 对象 | 参数为了兼容，手机端目前未实现 |
| onclick | 回调函数 | 当用户点击了确定按钮的回调函数 |



#### 示例

```javascript
GM_notification("Hello!");

GM.notification({
  text: 'This is a message with callback',
  onclick: function() {
    alert("you click message ok button");
  },
  ondone: function() {
    alert("message bar closed");
  }
});

GM_notification("Hello","","",function() {
  alert("you click message ok button");
})

```

*****

### GM_setClipboard

#### 描述
写入字符串数据到剪贴板

#### 语法

```
function GM_setClipboard(data)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| data | 字符串 | 字符串内容 |

#### 示例
```javascript
GM_setClipboard('this is test data');
```

*****

### GM_registerMenuCommand

#### 描述

注册一个菜单选项，会显示在[脚本菜单](script.md#%E8%84%9A%E6%9C%AC%E8%8F%9C%E5%8D%95)中

#### 语法
```javascript
	function GM_registerMenuCommand(title,callback) 
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| title | 字符串 | 菜单名称 |
| callback | 回调函数 | 点击菜单项执行的回调函数 |

#### 返回值

返回菜单项的命令ID, 注销菜单的时候会用到

#### 示例

```javascript
GM_registerMenuCommand("click me",function() {
	alert("You click menu item");
});
```

*****

### GM_unregisterMenuCommand

#### 描述

注销之前注册的菜单项

#### 语法

```javascript
function GM_unregisterMenuCommand(commandId) 
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| commandId | 字符串 | 菜单项的命令id |

#### 示例

```javascript
GM_unregisterMenuCommand(commandId);
```

*****

### GM_openInTab

#### 描述
在新标签中打开一个页面

#### 语法
```javascript
function GM_openInTab(url,background) 
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| url | 字符串 | 新标签页面的网址 |
| background | 布尔类型 | 是否在后台打开标签,默认为false|

#### 示例

```javascript
GM_openInTab("https://www.example.com");
GM_openInTab("https://www.example.com",true);
```

*****

### GM_download

#### 描述
调用浏览器的默认下载器进行下载

#### 语法
```javascript
function GM_download(url,name) 
```
或者

```javascript
function GM_download(detail) 
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| url | 字符串 | 要下载资源的网址 |
| name | 字符串 | 下载文件保存的名称|
| detail | 对象 | 通过对象配置下载参数|

##### detail 参数属性列表

- **url**  - 字符串类型，表示要下载的网址
- **name** - 字符串类型，下载文件保存的名称
- **hedaers** - 对象类型，HTTP请求头
- **onload** - 回调函数，下载完成.
- **onerror** - 回调函数，下载出错

#### 示例

```javascript
GM_download("https://www.xbext.com/download/xbrowser-release.apk") 
```

```javascript
//指定下载保存文件名称
GM_download("https://www.xbext.com/download/xbrowser-release.apk,"xbrowser.apk")
```

```javascript
let urls = ["https://www.dundeecity.gov.uk/sites/default/files/publications/civic_renewal_forms.zip",
  "https://www.dundeecity.gov.uk/sites/default/files/publications/civic_renewal_forms.zip",
  "https://www.dundeecity.gov.uk/sites/default/files/publications/civic_renewal_forms.zip",
];
var i = 0;
for (let url of urls) {
  GM_download({
    url: `${url}`,
    name: `test-file${++i}.zip`,
    headers:{
        Referer:"https://www.example.com/"
    },
    onload: function() {
      console.log("download completed !");
    }
  });
}
```

*****

### GM_getResourceText

#### 描述

获取元数据标记@resource指向资源的文本内容。

#### 语法
```javascript
function GM_getResourceText(name)
```
#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| name | 字符串 | 标记@resource 定义的用于引用资源的键值名称 |

#### 示例

```javascript
// @resource     main-content https://www.example.com/res/main-content.txt
var text = GM_getResourceText("main-content");
```

#### 返回值

返回资源URL的文本内容。

*****

### GM_getResourceURL

#### 描述

获取元数据标记@resource  指向资源的内容， 内容以Base64编码，格式为Data URI格式。

#### 语法

```javascript
function GM_getResourceURL(name)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| name | 字符串 | 标记@resource 定义的用于引用资源的键值名称 |

#### 示例

```javascript
 var img = document.querySelector("#avatar")
 //@resource     avatar01 https://api.multiavatar.com/avatar01.svg
 img.src = GM_getResourceURL("avatar01");
```

#### 返回值

返回以Base64编码的Data URI。

*****

### GM_xmlhttpRequest

#### 描述

这个方法类似于[XMLHttpRequest](http://developer.mozilla.org/en/docs/XMLHttpRequest) 对象, 不同的是此方法支持跨域请求，突破了对象[同源访问策略](https://developer.mozilla.org/En/Same_origin_policy_for_JavaScript),使用起来更加灵活。

#### 语法

```javascript
function GM_xmlhttpRequest(details)
```

#### 参数

这个方法只有对象类型的参数details ，对象的属性列表和含义如下：

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| details | 对象 | 包含一系列属性作为控制参数 |

#####  details 属性说明

- **method** -  Http请求方法，GET、POST、HEAD等。
- **url** - 字符串，目标请求URL。
- **headers** - 可选项，字符串，HTTP协议头，User-Agent，Referer等。
- **data** - 可选项，字符串，通过POST方法发送的数据
- **responseType** - 可选项，字符串，设置响应类型，可以为arraybuffer, blob, json 和 stream 之一。
- **onabort**- 可选项，回调函数，当HTTP请求被终止时调用。
- **onerror**- 可选项，回调函数，HTTP请求出现异常时被调用
- **onloadstart** - 可选项，回调函数，HTTP请求开始被调用
- **onreadystatechange** - 可选项，回调函数，HTTP请求状态变化被调用
- **onload** - 可选项，回调函数，当HTTP请求完成时被调用，回调函数参数携带的几个属性如下
  - **finalUrl** - HTTP 最终请求的URL地址，比如最后重定向的网址。
  - **readyState** -  数据状态
  - **status** - HTTP请求状态
  - **statusText** - HTTP请求状态文本
  - **responseHeaders** - HTTP响应头
  - **response** - HTTP响应返回的对象类型数据，当 *details.responseType* 被设置返回相应类型的对象。
  - **responseText** - 返回文本类型的数据

#### 示例

```javascript
//发起一个get请求
GM_xmlhttpRequest({
  method: "GET",
  url: "http://www.example.com/",
  onload: function(response) {
    alert(response.responseText);
  }
});
```

```javascript
//发起一个post请求
GM.xmlHttpRequest({
  method: "POST",
  url: "https://www.example.net/login",
  data: "username=johndoe&password=xyz123",
  headers: {
    "Content-Type": "application/x-www-form-urlencoded"
  },
  onload: function(response) {
    if (response.responseText.indexOf("Logged in as") > -1) {
      location.href = "http://www.example.net/dashboard";
    }
  }
});
```
*****

### urlchange 

这是扩展的一个事件函数，常用于单页面应用监听浏览器url变化。

#### 示例

```javascript
    window.addEventListener('urlchange', () => {
       alert("urlchange");
    });
   //当页面跳转到一个新的锚点会触发urlchange事件
   window.location = "#test"
```
*****

### GM_cookie

#### 描述

该方法可以突破浏览器对Cookie的跨域限制，对某个网站下的Cookie进行操作，包括获取、设置、删除Cookie。此方法存在安全隐患，可能会导致用户隐私信息泄露。目前主要为了兼容一些脚本，暂时支持这个方法，后续可能会限制这个方法的使用。

#### 语法

```javascript
function GM_cookie(action,details,callback)
```

#### 参数

| 名称 | 类型 | 描述 |
| ------ | ------ | ------ |
| action |  字符串 | 对Cookie的操作方式 [list,set,delete] |
| details | 对象 | 包含一系列属性作为参数 |
| callback |  回调函数 | 返回对Cookie操作的结果 |

#####  action 可选项

- **list** - 获取某个域名下的Cookies 列表
- **set** - 设置某个域名下的Cookie
- **delete** - 删除某个域名下的Cookie

#####  details 属性说明

- **url** - 页面网址
- **domain** - Cookie域名。
- **name** - 字符串，Cookie键值
- **value** -字符串，Cookie内容。

#### 示例

获取某个域名下的Cookies 列表

```javascript
    GM_cookie('list', {
      url: "https://www.example.com",
    }, function (result) {
        console.log(result);
    });
```

删除某个域名下的Cookie

```javascript
      GM_cookie('delete', {
        url: "https://www.example.com",
        name: "test"
  
      }, function (result) {
          console.log(result);
      });
```

设置某个域名下的Cookie
```javascript
    GM_cookie('set', {
      url: "https://www.example.com",
      name: "test",
      value: "test",
    }, function (result) {
        console.log(result);
    });
```

> 为了兼容一些其它脚本GM_cookie函数同时也支持下面的调用方式

``` javascript
    //获取某个域名下的cookies
    GM_cookie.list({
      url: "https://www.example.com",
    }, function (result) {
        console.log(result);
    });

    //设置某个域名下的Cookie
      GM_cookie.set({
      url: "https://www.example.com",
      name: "test",
      value: "test",
    }, function (result) {
        console.log(result);
    });

    //删除某个域名下的Cookie
    GM_cookie.delete({
        url: "https://www.example.com",
        name: "test"
  
      }, function (result) {
          console.log(result);
      });

```

*****

###  GM_info

这是一个对象，用来保存每个脚本的相关环境变量，比如脚本的版本、作者、介绍等，对象属性列表如下：

- **script** - 对象类型，包含下面一些属性。
  - **author** - 脚本作者
  - **name** - 脚本名称
  - **description** - 脚本介绍
  - **version** - 版本
  - **copyright** - 版权信息
  - **includes** - 数组类型，包含匹配页面的列表
  - **matches** - 数组类型，和includes类似，包含匹配页面的列表
  - **excludes** -数组类型，排除匹配网址列表
  - **resources** - 数组类型，所有资源列表
- **version** - 脚本管理器的版本
- **scriptHandler** - 脚本管理器的名称
- **scriptMetaStr** - 脚本管理器元数据字符串

#### 示例

```javascript
var info = "Script Name: "  + GM_info.script.name + 
    "\nVersion: " + GM_info.script.version + 
    "\nVersion: " + GM_info.script.version + 
    "\nScriptHandler: " + GM_info.scriptHandler + 
    "\nScript Handler Version : " + GM_info.version ;

alert(info);
```

*****

[返回脚本说明](script.md) | [返回脚本列表](../script-share.md) | [返回主页](../../README.md)