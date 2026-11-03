## v2.5.9

保留本地定制：移除应用更新、首页手册及设置页外链按钮和推广内容，继续提供 Windows x64、macOS Apple 芯片和 Linux x64 DEB 安装包。

<details>
<summary><strong> 🐞 修复问题 </strong></summary>

- 修复全局模式中代理组无法展开、GLOBAL 组已选节点显示错误的问题
- 修复规则列表含空项时，规则编辑器无法打开的问题
- 修复重启后自动备份计划不执行的问题
- 修复首页网站测速失败后，卡片仍停留在测速状态的问题
- 修复展开代理组后，节点延迟未刷新的问题
- 修复自定义 CSS 无法设置编辑器字体的问题
- 修复 WebDAV 配置清空后无法保存的问题
- 修复服务模式下使用 SSH 私钥文件时，内核无法启动的问题
- 修复内核更新 GEO 数据库后，规则验证仍使用旧数据库的问题
- 修复 DNS 覆写自动关闭后，开关状态和通知未同步的问题

**🍎 macOS**

- 修复 macOS Big Sur 首页延迟和流量信息显示空白的问题

**🐧 Linux**

- 修复 Linux 安装包中多余可执行文件导致应用识别异常的问题

</details>

<details>
<summary><strong> ✨ 新增功能 </strong></summary>

- 新增 TUN DNS 模式设置
- 新增首页 IP 信息自动刷新开关
- 新增 Muse AI 流媒体解锁检测

</details>

<details>
<summary><strong> 🚀 优化改进 </strong></summary>

- 优化 Mihomo 内核，更新至 1.19.33
- 优化链式代理操作，启用前增加确认提示
- 优化托盘测速入口，统一使用代理页面测试延迟

**🖥️ Windows**

- 优化 Windows 卸载和覆盖安装流程，提示先结束正在运行的应用

</details>
