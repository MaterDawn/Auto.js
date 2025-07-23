# ✨ Auto.js-Pro 项目说明

本项目提供 **Auto.js Pro 9.3.11** 和 **8.4.1** 的自搭建优化版本，致力于为脚本开发者提供一个免 Root、免 VPN、稳定高效的自动化平台。

---

## 🔥 Auto.js 高级版 9.3.11 - 全网完美版

此版本经过深度优化，实现以下特性：

- 🚫 **无需开启 VPN：** 省去繁琐网络配置。
- ✅ **打包不闪退：** 告别脚本打包后闪退问题。
- 🌍 **不限制设备：** 邀请码支持多设备通用，灵活切换。
- 🚀 **完美直装体验：** 一键安装，快速上手。

---

## 🚀 快速上手指南

1. 打开应用，点击 **“登录”** 按钮。
2. 输入你的 **邀请码** 即可使用所有功能。

---

## 💬 交流与支持

- **QQ群：** [1053378738](https://qm.qq.com/q/LdzINeYf2C)（点击加入）

---

## ✨ 核心功能特性

### 🔗 与官方 API 无缝对接

- 支持所有 Auto.js 原生 API。
- 可发布源码与插件，支持第三方扩展。
- 内置完整 OCR 插件，满足图像识别需求。

### 🛡️ 免 Root & 免 Host 转发

- 源码级优化，实现后台直连。
- 内建流量转发机制，真正实现免 Root/Host。
- 安装即用，无需任何额外权限设置。

### 🔓 解锁功能限制

- 自动解除主流 App 控件点击限制，提升兼容性与可控性。

### 🔒 加密与安全

- 提供全面的代码加密保护：
  - **增强型离线加密**
  - **快照加密**
- 安全保障脚本核心逻辑不被泄露。

### 🔄 邀请码支持多设备使用

- 同一个邀请码可在多设备之间自由切换使用。
- ⚠️ 注意：跨 IP 使用可能导致账号被挤出，请合理安排使用策略。

---

## ⚙️ 特色亮点

1. **基于 Auto.js Pro 9.3.11 深度优化：**
   - 功能完整，打包不闪退。
   - 免 VPN、免 HOST，即装即用。
2. **兼容最新版微信混淆控件识别与点击：**
   - 针对复杂界面适配，提升自动化执行成功率。
3. **支持打包脚本开机启动功能：**

```js
$settings.setEnabled('boot_restart', true);
```

> 💡 **提示：** 需卸载旧版本并安装本高级版后生效。

---

## 🌐 运行网络代码资源

高级版支持直接运行本地或远程的 JS、快照、工程 Zip 文件，极大提升部署与热更新灵活性。

### 📂 运行本地快照文件

```js
engines.execScriptFile("/sdcard/Pictures/xxxx.snapshot"); // 后缀必须为 .snapshot
```

### ☁️ 运行网络资源文件

以下三种网络资源类型均支持：

#### 📄 JS 文件（JavaScript 脚本）

```js
engines.execScriptFile("https://xxxbeijing.aliyuncs.com/PMTT3.js");
```

#### 📦 快照文件（.snapshot）

```js
engines.execScriptFile("https://xxxxxxg.aliyuncs.com/PMTT3.snapshot");
```

#### 🧳 Project.zip 工程包

```js
engines.execScriptFile("https://xxxxxxg.aliyuncs.com/PMTT3.zip");
```

#### 💡 自动判断文件类型（示例：蓝奏云解析）

```js
engines.execScriptFile("https://lz.qaiu.top/parser?url=https://apkxxxxxx.lanzouo.com/iPuxxxxxmkmkj");
```

> ⚠️ **注意事项：**  
> - 调试阶段：Zip 包中 JS 文件需为明文。  
> - 打包后：支持全加密的 Project Zip，保障逻辑安全的同时实现热更新！

---

## 📜 版权与声明

- 本项目仅供学习与研究使用，**严禁用于任何商业或非法用途**。
- 所有资源整理自互联网，版权归原作者所有。
- 如有侵权或问题，请联系维护者及时处理。
