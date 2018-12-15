
# ushare-editor

## 介绍

**ushareEditor** —— 基于wangEditor@3.1.1开发的富文本编辑器,轻量级，配置方便，使用简单。支持 IE10+ 浏览器。

- 源码：[https://github.com/HEJIN2016/ushare-editor](https://github.com/HEJIN2016/ushare-editor) （欢迎 star）

![image.png](https://xuanwuyun.com/FlLolaDWYAm4x577-uVx0hZhESjc?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




## 下载

- 直接下载：[https://github.com/HEJIN2016/ushare-editor](https://github.com/HEJIN2016/ushare-editor)
- 使用`npm`下载：`npm install ushare-editor`


## 优化
针对wangeditor
1. 部分UI重新设计；
2. 增加分割线功能；
3. 支持生成图片介绍文字功能，开启该功能时图片将居中显示；
4. 支持第三方平台拷贝文字时去除字体、去除字体大小等过滤；
5. 增加代码链接判空校验、链接自动插入http协议头；
6. 支持qq、微信等截图然后直接拷贝图片功能（该功能需后台支持图片上传功能或者配置七牛等第三方存储）；
7. 抽离css样式，用户可自行替换样式；
8. 修复了部分bug


## 使用


```javascript
<link rel='stylesheet' href='usharerEditor.css'>
<script src='ushareEditor.js'></script>


const E = window.ushareEditor
const editor = new E('#div')
editor.create()
```


webpack

```javascript
const ushareEditor = require('ushare-editor');
require('ushare-editor/ushareEditor.css');

const editor = new ushareEditor('#div');
editor.create();
```


## 运行 demo

- 可查看[wangeditor](http://www.wangeditor.com)相关demo，使用方式基本一致
- 用于 React、vue 或者 angular 可查阅[文档](http://www.kancloud.cn/wangfupeng/wangeditor3/332599)中[其他](https://www.kancloud.cn/wangfupeng/wangeditor3/335783)章节中的相关介绍

