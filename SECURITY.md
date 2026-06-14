# Security Policy

## 回報安全問題

如果你發現疑似安全問題，請不要把實際 token、密碼、私鑰或可用 exploit 直接貼進公開 issue。

這個 repository 目前是私人 repository。一般安全改善可以開 GitHub issue；如果內容包含敏感資訊，請先聯絡 GitHub owner `@GongYuanCaiJi`，再提供最小必要重現資訊。

## 支援範圍

目前支援範圍是 `main` branch 以及正在準備合併進 `main` 的 pull request。

## 合併前防線

這個 repository 以 GitHub ruleset 和 GitHub Actions 作為合併前防線。若 GitHub 原生安全功能因 repository plan 不可用，會以 mainstream OSS 掃描工具作為 pull request fallback。
