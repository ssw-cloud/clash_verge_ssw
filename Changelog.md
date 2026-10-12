## v2.5.8

保留本地定制：移除应用更新、首页手册及设置页外链按钮和推广内容，继续提供 Windows x64、macOS Apple 芯片和 Linux x64 DEB 安装包。

<details>
<summary><strong> 🐞 修复问题 </strong></summary>

- 修复托盘代理组延迟缺失、超时与未测速状态混淆的问题
- 修复多个代理集合含同名节点时，节点无法选择、测速和延迟显示指向错误节点的问题
- 修复端口设置混淆保存值与运行值、无效输入缺少提示的问题
- 修复已有内核进程阻止启动时缺少多语言说明和处理建议的问题
- 修复退出、注销或关机时，应用可能长时间卡住的问题
- 修复宽窗口下订阅卡片过多，导致配置名称被截断的问题
- 修复通过 URL 导入未使用的订阅时，当前配置被重新加载的问题

**🖥️ Windows**

- 修复 Windows 服务启动类型被改为手动后，应用长时间卡住的问题，并提供一键修复
- 修复 Windows 长时间运行后，托盘菜单点击无响应的问题

**🍎 macOS**

- 修复 macOS 关闭 TUN 或退出后，系统 DNS 未恢复导致无法解析域名的问题

**🖥️/🍎 Windows/macOS**

- 修复 Windows/macOS 打开托盘菜单时，节点延迟与自动选择状态未刷新的问题

</details>

<details>
<summary><strong> ✨ 新增功能 </strong></summary>

- 新增托盘代理组中的「测试延迟」菜单项
- 新增巴西葡萄牙语界面

</details>

<details>
<summary><strong> 🚀 优化改进 </strong></summary>

- 优化德语界面翻译，补全残留英文内容

**🖥️ Windows**

- 优化 Windows 系统代理默认绕过规则，支持直接访问 `*.local` 局域网设备

</details>
