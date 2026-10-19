# 群聊活动助手 · Windows

免费提供的本地聊天事项整理工具。可导出 QQ 群聊与好友私聊，按日期整理事项、提取“我的事项”，并回到原始消息查看依据。

## 下载与使用

在 [最新版本](https://github.com/XinR-985/groupchat-assistant-releases/releases/latest) 的附件中下载 `GroupChatAssistant-Windows-v1.2.1.zip`，完整解压到可写目录（建议 D 盘），运行“启动群聊活动助手.cmd”。请保留整个文件夹，不能只复制 EXE。

分享包包含 Electron、Node.js 运行环境和干净的 QQ Chat Exporter / NapCat 导出引擎。QQ 客户端需自行安装并登录自己的账号。AI 可选择本地规则、ChatGPT 订阅、OpenAI API、DeepSeek 或兼容接口，相关登录和密钥由使用者自行配置。

聊天记录、导出的图片文件、QQ 登录资料和 AI 密钥保存在使用者本机。本发布包不含开发者的聊天、令牌、密钥或登录状态。

## 软件内更新

本版本预置此仓库的固定更新源。App 可在启动后及每 4 小时检查更新，按设置自动下载，并由使用者点击“重启并安装”。更新保留聊天、已选事项、AI 设置及 QQ 导出引擎的用户资料。QQ 导出引擎需运行才能导出；更新文件仍需可访问 GitHub 的网络。

`update.json` 与 `GroupChatAssistant-update-1.2.1.zip` 用于软件内更新；首次使用请下载完整 Windows 包。

## 第三方软件与源码

QCE 6.3.2、NapCatQQ 4.18.28、Electron 44.9.0、Node.js 24.19.0 及各依赖分别按其原许可证提供。本次发行计划为免费、非商业分享，不以此缩减 GPL 代码原本的修改、再分发等权利。

完整 Windows 包内的“第三方源码”目录包含对应版本的上游源码归档，以及 QCE 修改后的源文件、补丁和相关集成脚本。另提供 `ThirdPartySources-v1.2.1.zip` 方便单独获取。GitHub 自动生成的 “Source code” ZIP 仅是本发布仓库的文档归档，请通过上述附件获取第三方源码材料。

本项目不是腾讯、QQ、QCE、NapCat 或其作者提供的官方产品。尚未确认的原生组件授权链、图标分发权和 GPL 组合边界在 `license-audit-report.md` 中列明；附带许可证与源码不代表全部法律问题已获确认。

- [QQ Chat Exporter](https://github.com/shuakami/qq-chat-exporter/tree/v6.3.2)
- [NapCatQQ](https://github.com/NapNeko/NapCatQQ/tree/v4.18.28)
- [Electron](https://github.com/electron/electron/releases/tag/v44.9.0)
- [Node.js](https://github.com/nodejs/node/tree/v24.19.0)
