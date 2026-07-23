<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# Danny Markdown 编辑器 1.70

- 首次安装、更新或降级到当前版本后，第一次打开会立即静默检查更新，不再等待 24 小时。
- 首次检查失败时会在下次启动立即重试；成功检查后恢复每 24 小时一次的自动检查频率。
- 发现新版本后继续在后台静默下载并验证，准备完成才在所有页面的标签栏右侧显示“更新”。
- 点击“更新”会退出、覆盖安装并自动重新打开；启动后展示本次 GitHub 更新内容。
- 更新包继续使用 Sparkle EdDSA 签名验证。
