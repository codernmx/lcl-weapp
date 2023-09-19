<!--
 * @Date: 2023-09-14 13:08:50
 * @LastEditTime: 2023-09-14 13:15:07
-->

<h3 align="center">可靠的小程序 UI 组件库</h3>

<p align="center">
  <img src="https://img.shields.io/npm/v/lcl-weapp.svg?style=for-the-badge" alt="npm version" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge&color=#4fc08d" />
  <img src="https://img.shields.io/npm/dt/lcl-weapp.svg?style=for-the-badge&color=#4fc08d" alt="downloads" />
  <img src="https://img.shields.io/npm/dm/lcl-weapp.svg?style=for-the-badge&color=#4fc08d" alt="downloads" />
</p>

---

### 介绍

lcl-weapp 是一个**可靠的移动端组件库**


## 使用之前

使用 lcl-weapp 前，请确保你已经学习过微信官方的 [小程序简易教程](https://developers.weixin.qq.com/miniprogram/dev/framework/) 和 [自定义组件介绍](https://developers.weixin.qq.com/miniprogram/dev/framework/custom-component/)。

## 安装

### 方式一. 通过 npm 安装 (推荐)

小程序已经支持使用 npm 安装第三方包，详见 [npm 支持](https://developers.weixin.qq.com/miniprogram/dev/devtools/npm.html?search-key=npm)

```bash
# 通过 npm 安装
npm i lcl-weapp -S --production

# 通过 yarn 安装
yarn add lcl-weapp --production

```

### 方式二. 下载代码

直接通过 git 下载  源代码，并将 `dist` 目录拷贝到自己的项目中。

```bash
git clone https://github.com/codernmx/lcl-weapp.git
```

## 使用组件

以tips组件为例，只需要在 json 文件中引入按钮对应的自定义组件即可

```json
{
  "usingComponents": {
    "lcl-tips": "lcl-weapp/tips"
  }
}
```

接着就可以在 wxml 中直接使用组件

```html
<lcl-tips  text="添加到我的小程" duration="12"></lcl-tips>
```


## 基础库版本

Vant Weapp 最低支持到小程序基础库 2.6.5 版本。


## 开源协议

本项目基于 [MIT](https://zh.wikipedia.org/wiki/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89)协议，请自由地享受和参与开源。