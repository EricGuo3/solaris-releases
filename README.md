# Solaris

Solaris 是一款本地优先的轻量项目管理 macOS 应用。

本仓库仅用于提供 Solaris 官方安装包和发布说明，不包含源代码。

## 当前版本

Solaris v0.9.11

## 系统要求

- macOS 15.7 或更高版本
- Apple Silicon（arm64）

目前不支持 Intel Mac。

## 下载与安装

正式发布后，请前往本仓库的 [Releases 页面](https://github.com/EricGuo3/solaris-releases/releases) 下载：

`Solaris_0.9.11_arm64.dmg`

安装方法：

1. 下载并打开 DMG。
2. 将 Solaris 拖入“应用程序”文件夹。
3. 从“应用程序”文件夹启动 Solaris。

## 安全验证

安装包已经过 Developer ID 签名和 Apple 公证。

Solaris v0.9.11 DMG 的 SHA-256：

```text
96640067b948ba5e68a1314cb484a04fbffe459feeb41c6e54d7cbce7059acc3
```

下载后，可以在终端中执行：

```bash
shasum -a 256 Solaris_0.9.11_arm64.dmg
```

终端输出的 SHA-256 应与上面的值完全一致。

## 数据说明

Solaris 的工作数据保存在用户选择的本地工作区中。请自行维护重要数据和备份。

## 使用与源码

Solaris 目前可以免费下载和使用，但不是开源软件。

本仓库不提供 Solaris 源代码。


## 使用许可与源码

Solaris 允许个人和公司免费使用，包括工作和商业场景中的内部使用。

Solaris 不是开源软件。本仓库不提供源代码，也不授权第三方转售、公开重新分发或发布修改版本。

完整条款请参阅 [Solaris 软件使用许可](LICENSE.md)。


隐私说明请参阅 [Solaris 隐私说明](PRIVACY.md)。
