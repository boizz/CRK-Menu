# CRK-Menu

### 概述
这个右键菜单本是写给自己用的，但是发布在自己的微博后发现很多朋友都在问起这个右键菜单怎么写，其实很简单，这次我写好了开放的接口给大家使用，调用也很简单，详情可以查看插件主页。

### 调用
在jQuery后面引入 `right-menu-min.js` 文件，或直接使用下面的代码：
```
<script src="http://cdn.ccwebsite.com/crk-menu/1.1.0/right-menu-min.js"></script>
```

### API
```
var customNav = {
	//增加自定义菜单
    "customLink" : [["Link","Name"],["Link","Name"]],
    //增加自定义二维码
    "qrCode" : ["ImgLink","ButtonName"];
};
```
