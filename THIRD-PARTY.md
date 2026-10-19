# Third-party notices and source availability / 第三方通知与源码

PortScope's own application source is not published and no project-wide open-source license is selected. These notices and source rights concern third-party components only. PortScope's binary-distribution status does not restrict recipients' rights under those components' licenses.

The `third-party/` directory contains **476 exact files**, covering the resolved **259 npm/Rust Windows normal/build dependencies**, supplemental notices, NSIS and its helper plugin, the Microsoft WebView2 SDK loader, and source availability. Some dual-licensed dependencies carry both upstream notice files. No GPL/AGPL/LGPL-only application dependency was found in this Windows inventory.

The same 476 files are in the verified portable ZIP and installed package. The separate `PortScope_1.0.0_third-party.zip` asset provides them without downloading the application. The public Git repository also preserves them. Original upstream copyrights/licenses are retained.

## MPL-2.0 covered sources

The following **unmodified exact source archives** are publicly available in [third-party/supplemental/sources](third-party/supplemental/sources) and in the third-party Release ZIP. They match the locked build checksums. These covered sources remain available under MPL-2.0, with original file notices and license texts preserved inside their archives. They contain third-party dependency code, not PortScope application source.

| Component | Version |
| --- | --- |
| cssparser | 0.37.0 |
| cssparser-macros | 0.7.1 |
| dtoa-short | 0.3.5 |
| option-ext | 0.2.0 |
| selectors | 0.38.0 |

Official source URLs and SHA-256 values are in [supplemental/provenance.json](third-party/supplemental/provenance.json). MPL permits a larger work to contain separately licensed files; the covered components' source obligations remain fulfilled. See the [MPL text](https://www.mozilla.org/en-US/MPL/2.0/) and [Mozilla FAQ](https://www.mozilla.org/en-US/MPL/2.0/FAQ/).

## Packaging components

- Microsoft.Web.WebView2 SDK **1.0.3800.47**: the linked static loader matched the official package byte-for-byte. Its SDK license and provenance are in `third-party/supplemental/microsoft-webview2-sdk/`. The WebView2 browser runtime is not bundled or installed by these packages.
- NSIS **3.11**: original `third-party/NSIS-COPYING.txt` includes zlib/bzip2/CPL notices and the LZMA linking exception. Unmodified corresponding upstream source: [NSIS 3.11 source distribution](https://sourceforge.net/projects/nsis/files/NSIS%203/3.11/). No NSIS component sources were modified; generated installer configuration is not a modification of those component source files.
- `nsis_tauri_utils.dll` **0.5.3**: original MIT/Apache texts and provenance are in `third-party/supplemental/nsis-tauri-utils/`; its bytes matched the official bundler's pinned checksum. The MIT text comes from the exact upstream release tag.

Original primary guidance: [NSIS license and exception](https://nsis.sourceforge.io/Docs/AppendixI.html). The source review and all-file byte comparisons found no unresolved distribution-material blocker. This statement is not a legal certification or a license grant for PortScope's own code.

中文：476 份原始材料与安装包、便携包逐文件一致，公开仓库和单独第三方 ZIP 均可获取。259 项 Windows 正常/构建依赖通知保留；五份 MPL 依赖的精确未修改源码以原授权公开，不含自有应用源码。WebView2 SDK、NSIS、辅助 DLL 通知及来源一并提供。闭源分发不削减第三方权利，也不表示整个 PortScope 采用 MIT/MPL/CPL 等许可证。
