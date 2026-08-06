# WeType-Tool-Patch

WeType 输入法免 Root 内置版，将 WeType Tool 的 Legacy 模块直接内置到安装包中，无需额外安装模块或获取 Root 权限。

## 下载

请前往 [Releases](https://github.com/0x1e93d/WeType-Tool-Patch/releases) 下载最新版本。

每个正式版本包含两个 APK：

```text
WeType_Original_<WeType版本>(<versionCode>)_Tool_<Tool版本>.apk
WeType_Monet_<WeType版本>(<versionCode>)_Monet_<Monet版本>_Tool_<Tool版本>.apk
```

### Original

官方 WeType 输入法内置 Tool 的版本，适合希望保留原版界面的用户。

### Monet

基于 [WeType Monet](https://github.com/0x1e93d/WeType_Monet) 的版本，提供 Monet 风格界面，同时内置 WeType Tool。

## 版本说明

- 内置模块：WeType Tool Legacy
- 打包工具： [NPatch](https://github.com/7723mod/NPatch)
- 最低 Android 版本：Android 9（API 28）
- `SHA256SUMS.txt`：两个 APK 的 SHA-256 校验值

Release 正文会记录本次使用的 WeType 底包、Monet、Tool 和 NPatch 版本。

## 安装

1. 根据需要下载 Original 或 Monet APK。
2. 安装前备份重要数据，并卸载或覆盖旧版本。
3. 按 Android 系统提示完成安装。
4. 安装后重新启用或切换到微信输入法。

两个 APK 都是完整安装包，不需要另外安装 Tool 模块。

## Bug 反馈

请在 [Issues](https://github.com/0x1e93d/WeType-Tool-Patch/issues) 提交问题。为了方便定位，请尽量提供：

- 使用的 APK 完整文件名
- WeType 版本和 versionCode
- Monet 版本（如果使用 Monet）
- Tool 版本
- 手机型号和 Android 版本
- 问题复现步骤
- 是否使用其他模块或修改工具
- 日志和截图

上传日志前，请删除账号、设备标识、Token 以及其他隐私信息。日志文件可以直接拖入 GitHub Issue 编辑框上传，或使用附件按钮添加。

## 相关项目

- [WeType-Tool-Releases](https://github.com/0x1e93d/WeType-Tool-Releases)：Tool 模块安装包
- [WeType Monet](https://github.com/0x1e93d/WeType_Monet)：Monet 风格适配
- [NPatch](https://github.com/7723mod/NPatch)：APK 内置打包工具

## 免责声明

本项目为第三方功能扩展项目。WeType 输入法及相关品牌、软件和资源的权利归其各自权利人所有。
