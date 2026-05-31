# Options Level Pro 下载仓库 / Options Level Pro Download Repository

这里是 Options Level Pro 的公开下载仓库，面向使用者提供 ATAS 7.x / 8.x 正式版 DLL、安装说明、使用教程和用户版更新记录。本仓库不包含商业源码、服务器数据生成脚本、受保护 API 源码或生产密钥。

This is the public download repository for Options Level Pro. It provides ATAS 7.x / 8.x stable DLLs, installation notes, the user guide, and user-facing changelogs. This repository does not contain commercial source code, server-side data generation scripts, protected API source code, or production secrets.

Options Level Pro 是 Trading Hub 的 ATAS 指标，用于在图表上绘制服务器端生成的期权关键位水平线。

Options Level Pro is a Trading Hub ATAS indicator that draws server-generated options key levels as horizontal chart levels.

## 快速下载 / Quick Download

请选择与自己 ATAS 大版本一致的 DLL。ATAS 7.x 和 ATAS 8.x 的 DLL 不能混用。

Choose the DLL that matches your ATAS major version. DLLs for ATAS 7.x and ATAS 8.x are not interchangeable.

| 推荐版本 / Recommended | ATAS 版本 / ATAS Version | DLL | 使用教程 / User Guide | 发布说明 / Release Notes |
| --- | --- | --- | --- | --- |
| 0.6.0 | ATAS 8.x | [Options-Level-Pro-0.6.0-ATAS-8.x.dll](正式版/8.x/Options-Level-Pro-0.6.0/Options-Level-Pro-0.6.0-ATAS-8.x.dll) | [使用教程 / User Guide](docs/使用教程.md) | [发布说明 / Release Notes](正式版/8.x/Options-Level-Pro-0.6.0/RELEASE_NOTES-0.6.0.md) |
| 0.6.0 | ATAS 7.x | [Options-Level-Pro-0.6.0-ATAS-7.x.dll](正式版/7.x/Options-Level-Pro-0.6.0/Options-Level-Pro-0.6.0-ATAS-7.x.dll) | [使用教程 / User Guide](docs/使用教程.md) | [发布说明 / Release Notes](正式版/7.x/Options-Level-Pro-0.6.0/RELEASE_NOTES-0.6.0.md) |

## 安装方法 / Installation

1. 关闭 ATAS。
   Close ATAS.
2. 下载与你 ATAS 大版本匹配的 DLL。
   Download the DLL that matches your ATAS major version.
3. 将 DLL 复制到 ATAS Indicators 目录。
   Copy the DLL into the ATAS Indicators folder.

```text
%AppData%\ATAS\Indicators\
```

4. 重新启动 ATAS。
   Restart ATAS.
5. 打开图表，将 Options Level Pro 添加为 Indicator。
   Open a chart and add Options Level Pro as an Indicator.
6. 在指标设置中填写 License Key，并确认数据接口地址符合当前环境。
   Enter the License Key in indicator settings and confirm that the data API endpoint matches the current environment.

## 使用者文档 / User Documents

- [完整使用教程 / Full User Guide](docs/使用教程.md)
- [用户版更新日志 / User Changelog](docs/用户版更新日志.md)

## 正式版下载 / Stable Downloads

| 版本 / Version | ATAS | DLL | 发布说明 / Release Notes | 说明文件 / README | 构建信息 / Build Info |
| --- | --- | --- | --- | --- | --- |
| 0.6.0 | 8.x | [DLL](正式版/8.x/Options-Level-Pro-0.6.0/Options-Level-Pro-0.6.0-ATAS-8.x.dll) | [发布说明 / Release Notes](正式版/8.x/Options-Level-Pro-0.6.0/RELEASE_NOTES-0.6.0.md) | [说明文件 / README](正式版/8.x/Options-Level-Pro-0.6.0/README-0.6.0.md) | [构建信息 / Build Info](正式版/8.x/Options-Level-Pro-0.6.0/BUILD_INFO-0.6.0.md) |
| 0.6.0 | 7.x | [DLL](正式版/7.x/Options-Level-Pro-0.6.0/Options-Level-Pro-0.6.0-ATAS-7.x.dll) | [发布说明 / Release Notes](正式版/7.x/Options-Level-Pro-0.6.0/RELEASE_NOTES-0.6.0.md) | [说明文件 / README](正式版/7.x/Options-Level-Pro-0.6.0/README-0.6.0.md) | [构建信息 / Build Info](正式版/7.x/Options-Level-Pro-0.6.0/BUILD_INFO-0.6.0.md) |

## 风险提示 / Risk Notice

Options Level Pro 是交易辅助指标，不提供交易信号、投资建议或盈利保证。实盘使用前必须先在模拟账户或回放环境中完整测试，并确认你理解每一条关键位数据的来源和限制。

Options Level Pro is a trading-assistance indicator. It does not provide trading signals, investment advice, or any profit guarantee. Before live trading, test it thoroughly in simulation or replay and make sure you understand the source and limitations of each key-level data point.
