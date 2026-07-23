<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# Danny Markdown 编辑器 1.71

- 修复覆盖更新后的第一次打开 Markdown 文件时错误停留在主页的问题。
- 启动阶段会优先缓存并处理 macOS 传入的文件，主页不再覆盖待打开文档。
- 每个新版本安装后会重新登记 `.md` 和 `.markdown` 默认打开关联。
- 更新说明只在版本真正升级后显示，手动安装旧版本时不再误报“已更新”。
- 首次打开新版本会立即静默检查更新，之后恢复每 24 小时检查一次。
- 发现新版本后继续后台静默下载，所有窗口和文档页准备完成后显示“更新”按钮。
- 点击“更新”会退出、覆盖安装并自动重新打开；更新包继续使用 Sparkle EdDSA 签名验证。
