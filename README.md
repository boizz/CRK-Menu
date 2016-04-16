# CRK-Menu

### 概述
自定义右键菜单
这个自定义右键菜单是基于我之前发布的 [custom-right-menu](https://github.com/BoizZ/custom-right-menu) (已删除)修改而来的，这次是写好开放的接口给大家，比之前的版本更易于使用，使用方法请看下文：

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
