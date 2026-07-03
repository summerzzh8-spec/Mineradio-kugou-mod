# Mineradio Modified

本仓库是基于 [XxHuberrr/Mineradio](https://github.com/XxHuberrr/Mineradio) 修改的非官方版本。

原项目作者：XxHuberrr  
原项目地址：https://github.com/XxHuberrr/Mineradio  
原项目许可证：GPL-3.0

## 说明

这是个人修改版，不代表原项目官方版本。原项目的名称、Logo、界面视觉设计与原创视觉表达归原作者所有；第三方依赖和第三方音乐服务分别遵循其各自授权与服务条款。

## 本修改版内容

- 新增酷狗音乐单曲搜索。
- 新增酷狗音乐歌单搜索。
- 支持 QQ 音乐 / 酷狗音乐歌单搜索结果展示。
- 支持加载酷狗歌单到播放队列。
- 接入酷狗播放地址、歌词、登录状态与网页登录入口。
- 调整前端搜索入口和多平台登录状态展示。

## 使用方式

如果下载 Release 中的便携版压缩包：

1. 下载 `Mineradio-1.2.0-kugou-portable.zip`。
2. 解压到任意文件夹。
3. 运行 `Mineradio.exe`。

## 源码说明

当前源码来自已安装 Electron 应用的 `resources/app` 目录，主要修改文件包括：

- `resources/app/server.js`
- `resources/app/public/index.html`
- `resources/app/desktop/main.js`

本仓库不包含 `node_modules`。依赖请根据 `resources/app/package.json` 安装。

## 授权

本修改版继承原项目 GPL-3.0 许可证发布。详见 [LICENSE](./LICENSE)。

