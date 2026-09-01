# KeibaCloud1

競馬予想（回収率最優先）用のリポジトリ。

## 使い方

新規チャット（PC / スマホどちらでも）で `/keiba` と打つと、実戦ソロ版 v8 の分析フローが起動します。
netkeiba の **出馬表URL 1本**（または各ページのスクショ/コピペ）を渡すと、
出馬表・タイム指数・馬柱(5走)を読んで買い目まで出します。

- スキル本体: [`.claude/skills/keiba/SKILL.md`](.claude/skills/keiba/SKILL.md)
- プロンプト全文: [`docs/keiba-yosou-prompt-v8.md`](docs/keiba-yosou-prompt-v8.md)

## メモ

- クラウド/スマホ環境ではネットワーク制限やプレミアム(ログイン必須)のため
  netkeiba を自動取得できないことがあります。その場合はスクショ/コピペで渡してください。
- 娯楽の範囲で。馬券は自己責任で。
