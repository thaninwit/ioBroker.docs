---
translatedFrom: en
translatedWarning: 如果您想编辑此文档，请删除“translatedFrom”字段，否则此文档将再次自动翻译
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/zh-cn/adapterref/iobroker.milight-smart-light/README.md
title: ioBroker.milight-smart-light
hash: Zlq40cZEWbVrN2V3mGoB2N81zeVjLNLtZOra9pTZt38=
---
![milight-smart-light徽标](../../../en/adapterref/iobroker.milight-smart-light/admin/lib/images/milight-smart-light-md.png)

![NPM版本](http://img.shields.io/npm/v/iobroker.milight-smart-light.svg)
![资料下载](https://img.shields.io/npm/dm/iobroker.milight-smart-light.svg)
![测验](http://img.shields.io/travis/Steiger04/ioBroker.milight-smart-light/master.svg)
![稳定](http://iobroker.live/badges/milight-smart-light-stable.svg)
![已安装](http://iobroker.live/badges/milight-smart-light-installed.svg)
![NPM](https://nodei.co/npm/iobroker.milight-smart-light.png?downloads=true)

＃ioBroker.milight-smart-light
ioBroker的此适配器基于mwittig的节点模块控制Milight LED灯泡和LED灯带。

mwittig /[Node-milight-promise](https://github.com/mwittig/node-milight-promise)

使用适配器，您可以同时使用：** v6 Bridge **和** Legacy Bridge **。

** v6桥：**

-网桥（仅iBox1）
-白色
-rgb（w）
- 饱满的色彩
-fullColor8Zone

**旧桥：**

-白色
-rgb（w）

###版本
-** Node.js **：使用8.0.0或更高版本
-** iobroker.admin **：使用3.5.10版或更高版本

## Changelog
### 0.3.0 (2020-04-30)
- (steiger04): Optimizations, bug fixes and new app

### 0.2.7 (2019-04-15)
- (steiger04): Additions to the Stable Repository

### 0.2.6 (2019-04-11)
- (steiger04): Updated the CI test and some MaterialiseCSS optimizations

### 0.2.5 (2019-03-07)
- (steiger04): Core Files/Testing Update and introduce adapter-core

### 0.2.4 (2019-03-03)
- (steiger04): Bug for addDeviceButton fixed in Admin

### 0.2.3 (2019-03-02)
- (steiger04): Fixed a bug in configuration load and save

### 0.2.2 (2019-02-28)
- (steiger04): Optimization of the App

### 0.2.1 (2019-02-13)
- (steiger04): Integration of  node-milight-promise v0.3.2

### 0.2.0 (2019-01-16)
- (steiger04): Adaptation to Admin3, materialzeCSS, general revision, new app

### 0.1.9 (2018-03-13)
- (steiger04): Adaption for js-controller > v.1.2.5

### 0.1.8 (2018-01-21)
- (steiger04): some optimizations for Alexa

### 0.1.7 (2018-01-12)
- (steiger04): optimized: create states

### 0.1.6 (2018-01-08)
- (steiger04): Bug fix: rgbToHsv(...)

### 0.1.5 (2018-01-05)
- (steiger04): Info about required fields in tab Zones inserted

### 0.1.4 (2017-11-05)
- (steiger04): Set configuration option fullSync to false in milight instance

### 0.1.3 (2017-11-04)
- (steiger04): Added start image

### 0.1.2 (2017-11-04)
- (steiger04): Bug fix: socketio

### 0.1.1 (2017-11-02)
- (steiger04): Bug fix: Fixed EffectMode for Legacy

### 0.1.0 (2017-11-01)
- (steiger04): Added Small FE for milight-smart-light

### 0.0.6 (2017-10-18)
- (steiger04): Bug fix: All four zones can be created for the instance (via iobroker.admin) and remain after a reload. There are no more problems with umlauts.
- (steiger04): The types "RGB + White" and "RGB" were combined in the type "RGB (W)"

### 0.0.5 (2017-08-02)
- (bluefox): Added russian translation

### 0.0.4 (2017-07-28)
- (steiger04): Added basis-testing


### 0.0.3 (2017-07-24)
- (steiger04): on- /off- /onoff-states optimized for vis widgets

### 0.0.2 (2017-07-23)
- (steiger04): Bug fix: added parameter in effectMode(...)

### 0.0.1 (2017-07-16)
- (steiger04): Initial Version

## License

The MIT License (MIT)

Copyright (c) 2017-2020 Steiger04 <steiger04@posteo.de>