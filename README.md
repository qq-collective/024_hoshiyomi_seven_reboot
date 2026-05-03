# 024 · Hoshiyomi Seven Reboot 🔮

**QuestQueries #024** — デイリーログ × 七人の星読みたち

毎日のコンディションを記録し、星読みたちにAI診断してもらうアプリ群。

## ファイル構成

| ファイル | 内容 |
|---|---|
| `024_form.html` | デイリーログ入力フォーム（毎日使う） |
| `024_hoshiyomi.html` | 星読みたちによるAI診断（週次） |

## 使い方

1. 毎日 `024_form.html` でその日のコンディションを記録
2. 週1でガーミンCSVをドロップして睡眠データを更新
3. 気が向いたら `024_hoshiyomi.html` で星読みたちに診断してもらう

## 技術スタック

- Vanilla JS / Single HTML files
- localStorage（データ保存）
- Anthropic Messages API（AI診断）
- GitHub Pages（ホスティング）

---
*QuestQueries — turning everyday moyamoya into apps through AI dialogue.*
