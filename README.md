# bblabu-notice

bblabu 通知：本机开机时由本机发，本机离线时由 GitHub Actions 接替。

- `.github/workflows/bblabu-notice.yml` —— 云端接替发通知的工作流（由 GitHub侦探 提供）
- `state.json` —— 通知状态（lastHash / lastSentAt / heartbeatAt）

收件人与 SMTP 凭据只存仓库 Secrets，不写进文件。
