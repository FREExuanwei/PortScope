# PortScope 1.0.0 distribution review / 发布审查

Review date: 2026-10-19. The owner authorized public binary distribution after the completed local 1.0.0 delivery. No application rebuild or runtime change was needed for publication; original installer and portable archive bytes/SHA-256 were preserved. Neither the application source archive nor private project/test data is published.

## Passed / 已通过

- Version metadata: npm/Cargo/Tauri and executable/installer PE report 1.0.0. Portable EXE matches the verified executable. ZIP CRC passes; its 476 dependency material files match local reviewed notices/sources.
- Reused evidence: 240 frontend tests, 79 native tests passed, one optional native test not run; actual IPv4/IPv6 TCP/UDP observations, real Node/npm Vite project recognition, history/identity/watch/favorite/workspace behavior, isolated JSON backup recovery and legacy compatibility.
- 150 details + 100 settings layout cases on actual WebView, five themes/scales, two languages and narrow/low viewports; viewport emulation, not physical DPI.
- Final-version targeted checks: 19 version-related frontend tests, nine tooling tests, frontend production build/typecheck/lint, path-remapped Windows production build and five desktop functional checks. The installed final EXE was also tested.
- Real namespaced production-template NSIS install 0.5.0 → upgrade 1.0.0 → rollback 0.5.0 → default uninstall, preserving isolated data and leaving production registration unchanged. Final payload SHA and all 476 installed third-party file hashes verified. This is not an unmodified clean-VM production install test.
- Same-day npm/RustSec audit: zero vulnerability entries; two off-Windows-closure warnings explicitly listed in KNOWN-LIMITATIONS.md. Dependency versions were not changed for publication.
- Binary/document path and common-secret checks, allowlisted public repository, no own source archive or private logs/data. Screenshots from real 1.0.0 controlled services were inspected; path-bearing text hidden, no fabricated native observations.
- Required notices, exact MPL component source archives, SDK/NSIS/plugin materials and source references provided. PortScope's own open-source license was not selected.

## Incomplete / 未完成

Full two-hour observation was removed as a gate by the owner. The baseline run recorded 61 resource samples across 3600 seconds (approximately 3628 seconds actual observation phase), 518 successful native collections, zero native failures, 34031 successful controlled connections and no fixture connection errors. Private memory first/last 494.6/564.6 MiB, range 448.6–564.6 MiB; one-core average CPU 4.85%. Memory increase does not prove stability or absence of a leak.

The original long-run result is **failed**, because its final harness assertion counted valid `observed` records as extra lifecycle transitions. The test-only assertion was fixed separately, preserving detection of duplicate transitions. The original result was not rewritten, and no replacement multi-hour run was started. Resource data came from the frozen 0.5.0 baseline, not a per-sample trace of the remapped 1.0.0 executable.

Unsigned binaries, clean-VM original installer/missing WebView2, real sleep/wake/network changes, physical DPI/touchpad and real Docker/WSL service attribution remain limitations. See KNOWN-LIMITATIONS.md. No claim of all-hardware certification, code signing or perpetual security is made.

## Public boundary / 公开范围

Only documentation, sanitized screenshots and required third-party materials are committed. Releases provide the installer, portable ZIP, third-party ZIP, public review report and public-scope SHA256SUMS. GitHub-generated source archives contain this distribution repository only, not PortScope application source. Local 0.5.0 and 1.0.0 rollback artifacts remain unchanged.

For reproducible publication evidence, the final post-publication check separately downloads public assets and compares their size and SHA-256, verifies public/latest/non-draft/non-prerelease status, tag, README image/download links and repository file allowlist. Results are retained by the publisher without exposing local logs or credentials.

中文：复用现有证据并保持安装包、便携包原始字节。公开边界限定为文档、脱敏实机截图、第三方履约材料和二进制资产，不包含自有源码或私人日志。完整两小时未完成且不计通过；原失败保留，观察到内存上升，不能声称无泄漏。其他未验证环境明确列出；公开后另行下载校验公开资产及仓库内容。
