# Privacy and local data / 隐私与本地数据

PortScope has no account system, telemetry, analytics, cloud sync or automatic upload of process/project data. Application processing and storage remain local. This describes PortScope's behavior; Windows and WebView2 platform services have their own policies.

Read-only native observation includes protocol/address/port, PID and accessible process creation/command information. Evidence-related project files may be inspected without scanning all disks or executing project scripts. Protected information is unavailable rather than bypassed. A local URL opens only on an explicit user action. Optional Docker/WSL inspection is limited to documented read-only metadata.

History stores minimized listener/binding observations, process identity and recognized service information. It excludes full command lines, environment variables and detected project paths. Retention/capacity are bounded; recording can be disabled and history cleared. Manual user labels are separate from current recognition. User-created workspace bindings do not persist detected project paths or commands.

Versioned JSON exports are user-triggered; history is off by default. An export can contain local addresses, PID/creation identifiers, custom names, labels and private notes. Review it before sharing. Sanitized diagnostic export excludes record identities, addresses, names, detected paths and notes. No export is automatically sent to the publisher.

No user backups, history databases, watch settings, project files or raw logs are included in this repository or the Release. Screenshots show controlled fixtures and hide path-bearing text. Releases contain no PortScope application source archive.

中文：无账户、遥测、统计、云同步或自动上传；处理及应用数据留在本机，系统/WebView 组件仍遵循其平台策略。只读读取可访问的进程信息与直接相关配置，不绕过权限，不执行项目脚本。历史不保存完整命令、环境变量或检测路径，可关闭和清空，保存期限与容量有界。备份由用户主动导出，默认不含历史，但可能含地址、标识和私人备注，分享前检查。公开仓库不含个人备份、数据库、关注设置、项目文件或原始日志；截图来自受控服务并隐藏路径。
