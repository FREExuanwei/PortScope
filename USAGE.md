# Install, verify and use / 安装、校验与使用

Download only from [https://github.com/FREExuanwei/PortScope/releases/tag/v1.0.0](https://github.com/FREExuanwei/PortScope/releases/tag/v1.0.0).

1. Choose the current-user x64 installer, or extract the complete portable ZIP and run `PortScope.exe`. Preserve third-party materials. Existing Edge WebView2 Runtime is required; this package does not install or download it.
2. Compare the downloaded file with `SHA256SUMS.txt`, for example in PowerShell: `Get-FileHash -Algorithm SHA256 .\PortScope_1.0.0_portable.zip`. The installer command is the same with its filename.
3. Both packages are unsigned. Keep Windows protection enabled. Do not bypass organizational controls. Matching hashes prove integrity against this release's checksum file, not a signed publisher identity.
4. In Live ports, select listeners/bindings or TCP connections, search by port/process and filter protocol, family or binding scope. Use Check port occupancy with the address/protocol you intend to bind. A matching port number alone is not a conflict.
5. Select a row for full scrollable details and identification evidence. Use the bell for watch rules and the star for favorites; manage advanced rules and notes in Watch & favorites. User labels do not become verified process identities.
6. Development services focuses on evidence-based candidates. If evidence is inaccessible, keep the unknown result or use a clearly user-defined project association in Project workspaces.
7. History displays samples, events and observation gaps. It cannot prove exact start/stop times between samples or while the app was closed. Alerts are in-app and require PortScope to be running.
8. Settings & data provides themes, language, scale and versioned JSON backup. Validate/preview before import and choose merge or replace deliberately. History export is opt-in. Never share an unreviewed personal backup.

## Data and rollback / 数据与回退

Portable and installed versions use the same application identifier/profile. Typical Windows storage is `%LOCALAPPDATA%\local.portscope.desktop\EBWebView`; Windows/WebView configuration can affect the exact location. Moving the EXE does not move data. Default uninstall preserves data; any explicit delete-data choice must be deliberate.

Close other instances, export JSON, and back up the complete profile while PortScope is closed before changing versions. Versions 0.5.0 and 1.0.0 use the same v2 workspace format. Earlier 0.4.0 treats that newer workspace format as read-only; rolling back the EXE is not a data downgrade. Do not use an older recovery action to overwrite newer data.

中文：从本仓库 Release 下载，核对 SHA-256 后安装或完整解压；保持系统防护开启。实时列表搜索端口，点击详情查看依据，铃铛和星星相互独立；项目分组不代表自动验证。历史只证明观察时的状态。备份分享前检查，恢复先验证与预览。免安装与安装版共享本机数据，回退前关闭实例、导出 JSON 并备份完整数据目录。
