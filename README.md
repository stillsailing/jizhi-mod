# 浮生梦

<p align="center">
  <a
    rel="noreferrer noopener" target="_blank" target="_blank"
    href="https://github.com/xxnuo/jizhi-mod"
    ><img
      alt="Github"
      src="https://img.shields.io/badge/Github-141e24.svg?style=for-the-badge&logo=github&logoColor=white"
  /></a>
  <a
    rel="noreferrer noopener" target="_blank" target="_blank"
    href="https://chromewebstore.google.com/detail/%E5%87%A0%E6%9E%9D%E5%A4%8F/aihpjpjndpdkbmdjghjglbmippnjlkcp"
    ><img
      alt="Chrome Web Store"
      src="https://img.shields.io/badge/Chrome-141e24.svg?&style=for-the-badge&logo=google-chrome&logoColor=white"
  /></a>
  <a rel="noreferrer noopener" target="_blank" href="https://addons.mozilla.org/en-US/firefox/addon/jizhi-mod/"
    ><img
      alt="Firefox Add-ons"
      src="https://img.shields.io/badge/Firefox-141e24.svg?&style=for-the-badge&logo=firefox-browser&logoColor=white"
  /></a>
</p>

## 介绍

支持自定义新标签页的跨浏览器扩展，浮生梦将在新标签页上展示中国经典诗词。

### 目前已完成的功能

- 点击诗句自动朗读
- 具有多种风格迥异的字体
- 支持自动切换明暗主题

有空会持续更新新功能，目前只是基础 1.0 版本。

## 预览

![LightTheme](preview/light.png)

<!-- https://i.imgur.com/qc5QtNM.png -->

![DarkTheme](preview/dark.png)

<!-- https://i.imgur.com/Z8A47Rd.png -->

![FirefoxPreview](preview/Firefox.png)

<!-- https://i.imgur.com/fQgS52Q.png -->

![SafariPreview](preview/Safari.png)

<!-- https://i.imgur.com/ucGvozQ.png -->

## 特性

- 使用完全离线的数据，无需联网
- 保持设计风格：简洁美观第一，速度性能第一（针对低功耗设备优化）
- 使用 WXT + React + Tailwindcss + Daisyui 开发

### 下载安装

#### 商店下载链接：

> Chrome、Firefox、Edge 等浏览器商店点击下面链接或标题的图标下载，也可以直接在浏览器拓展商店搜索 “浮生梦” 安装。

- [Chrome Web Store](https://chrome.google.com/webstore/detail/aihpjpjndpdkbmdjghjglbmippnjlkcp)（Chrome、Edge、Opera、Brave、360、Safari 等使用）

- [Firefox Addons](https://addons.mozilla.org/zh-CN/firefox/addon/%E5%87%A0%E6%9E%9D%E5%A4%8F/)（Firefox、Waterfox 等使用）

> 注：若无法访问 Chrome Web Store
>
> 可在国内 Chrome Web Store 克隆站下载安装：
> [浮生梦 | Chrome扩展 - Crx搜搜](https://www.crxsoso.com/webstore/detail/aihpjpjndpdkbmdjghjglbmippnjlkcp)

#### Releases 预构建下载：

[Releases](https://github.com/xxnuo/jizhi-mod/releases)

#### 本地构建

> 依赖：Node.js、pnpm

```bash
git clone https://github.com/xxnuo/jizhi-mod.git
cd jizhi-mod
pnpm install
pnpm run zip:all
```

构建成功后浏览器直接加载 .output 文件夹下对应浏览器的拓展文件为 “加载解压缩的拓展”即可使用。

## 待办

- [x] 朗诵功能
- [ ] 美丽的视频动态背景功能 😁 [Working]
- [ ] 自定义背景功能
- [ ] 添加搜索框功能
- [ ] 添加自定义字体功能

## 鸣谢

界面样式模仿了 [unicar9/jizhi](https://github.com/unicar9/jizhi)（作者已不再维护），且并非简单模仿，而是完全重写。感谢作者的优秀作品。

字体来自 [中文网字计划](https://chinese-font.netlify.app/)，有许多优秀的中文字体。
