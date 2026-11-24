# DevAssist · 组件清理

> Windows 桌面工具：通过 USB 调试，扫描并停用 / 卸载安卓机里的常见预置组件。  
> **单文件分发** · ADB 已内置 · 无需安装

[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue)](#)
[![Size](https://img.shields.io/badge/size-~22%20MB-lightgrey)](#)
[![ADB](https://img.shields.io/badge/ADB-bundled-success)](#)

---

## 下载

| 文件 | 说明 |
|------|------|
| [`DevAssist.exe`](./DevAssist.exe) | 主程序（双击运行，约 22MB） |
| [`DevAssist-v1.0.0-windows-x64.zip`](./DevAssist-v1.0.0-windows-x64.zip) | 压缩包（同内容） |

也可到 [Releases](../../releases) 下载发布版。

---

## 功能

- 按厂商浏览常见预置 / 采集类组件（小米、一加、OPPO、vivo、华为、荣耀等）
- 扫描本机：已装 / 运行中 / 已停用
- 停用或卸载（当前用户）
- 操作日志；支持恢复所选组件

---

## 使用前准备

1. 电脑：Windows 10 / 11  
2. 手机：用数据线连接电脑  
3. 打开 **开发人员选项**（设置 → 关于手机 → 连点版本号）  
4. 开启 **USB 调试**，手机上允许本机调试  

---

## 使用步骤

1. 双击 `DevAssist.exe`  
2. **刷新设备** → **扫描本机**  
3. 勾选组件 → **按推荐停用** 或卸载  
4. 需要时用 **恢复所选**

---

## 注意事项

- 新机 / 刚换卡时，部分登记类组件勿动  
- 「卸载」比「停用」更彻底，恢复也更麻烦  
- 不建议更新系统  
- 删除本软件：删除 `DevAssist.exe` 即可；日志目录 `%LOCALAPPDATA%\DevAssist`

---

## 系统要求

Windows 10 / 11（64 位）· 数据线 · 已开启 USB 调试的安卓手机 · 无额外依赖（ADB 已内置）


