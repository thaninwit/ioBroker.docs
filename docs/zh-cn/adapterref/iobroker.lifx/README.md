---
translatedFrom: en
translatedWarning: 如果您想编辑此文档，请删除“translatedFrom”字段，否则此文档将再次自动翻译
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/zh-cn/adapterref/iobroker.lifx/README.md
title: ioBroker.lifx
hash: Dq1R7yqzh6tng4JyujLCfbpyWc1Q6H2oRCzS2Uv4Jcw=
---
![商标](../../../en/adapterref/iobroker.lifx/admin/lifx_logo.png)

![安装数量](http://iobroker.live/badges/lifx-stable.svg)
![NPM版本](http://img.shields.io/npm/v/iobroker.lifx.svg)
![资料下载](https://img.shields.io/npm/dm/iobroker.lifx.svg)
![建立状态](https://travis-ci.org/foxthefox/ioBroker.lifx.svg?branch=master)
![NPM](https://nodei.co/npm/iobroker.lifx.png?downloads=true)

＃ioBroker.lifx
适用于ioBroker的Lifx适配器

##安装：
正式发布版本

```javascript
npm install iobroker.lifx
```

来自github的实际版本：

```javascript
npm install https://github.com/foxthefox/ioBroker.lifx/tarball/master --production
```

##设置/配置：
-无需设置或配置，适配器会自动检测到指示灯

### Metro小部件无法访问状态
-Metro小部件中无法访问状态的小图标是通知的第一个对象
-object_id [0]是指标。无法访问
-代替预设“ true”，应写入“ false”
-图标应为wifiColorRed.png
-水平偏移6应该可以正常工作

##可视化：
-使用Lifx小部件

##个对象
|对象|值|可设置|描述|
|--------|-------|:-:|--------|
| Bulb.state | boolean | x | true / false-> ON / OFF |
|灯泡颜色模式|布尔值| x |颜色，白色|
|灯泡温度|值| x |色温2500 ... 9000 K |
| Bulb.hue |值| x |颜色0 ... 360 |
| Bulb.sat |值| x |饱和度0 ... 100％|
|灯泡亮度|值| x |亮度0 ... 100％|
| Bulb.online | boolean |-| true / false |
| Bulb.label |值|-|名称/标签|
|灯泡供应商|值|-|供应商信息|
|灯泡产品|值|-|产品信息|
| Bulb.colorLamp |值|-|| colorLamp信息|
| Bulb.infraredLamp |值|-| infraredLamp信息|
| Bulb.multizoneLamp |值|-| multizoneLamp信息|
|灯泡区域温度|值| x |色温2500 ... 9000 K |
| Bulb.Zone.hue |值| x |颜色0 ... 360 |
| Bull.Zone.sat |值| x |饱和度0 ... 100％|
|灯泡区域亮度|值| x |亮度0 ... 100％|

＃＃ 去做：
-使用所有现有设置进行色彩值调整（亮度调整具有固定的80％饱和度并保持以前的色相设置；饱和度调整和色调调整具有固定的80％亮度）
-过渡时间
-波形

＃＃ 已知的问题
-超出范围的值会导致适配器崩溃

## Changelog
### 0.2.0
- lifx-lan-client library instead node-lifx
- states for vendor, product, version, product features
- multizone support
- cyclic polling

### 0.1.1
- logo quadratic

### 0.1.0
- compact mode

### 0.0.5
- adminv3
- noConfig -> no admin page anymore

### 0.0.4
- jqui widget with interactive colored slider

### 0.0.3
- metro widget
- jqui widget

### 0.0.2 
- change to node-lifx
- successful tested with 2 lamps and firmware 2.1

### 0.0.1 
- initial setup with lifx

## License

The MIT License (MIT)

Copyright (c) 2016-2020 foxthefox <foxthefox@wysiwis.net>