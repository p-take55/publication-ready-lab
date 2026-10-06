---
name: "meeting-summary"
description: "会議の記録から決定事項と次のアクションを整理する。"
metadata:
  aachat.headline.ja: "会議の決定とアクションを整理する"
  aachat.headline.en: "Summarize meeting decisions and actions"
  aachat.description.ja: "会議記録から決定事項、未解決の論点、担当と期日を整理し、不明な内容は推測しない。"
  aachat.description.en: "Extract decisions, open issues, owners, and deadlines from meeting records without inventing missing details."
  aachat.discovery.listed: "false"
---

# 会議を振り返る

1. 提供された記録を読み、決定事項、未解決の論点、次のアクションを分ける。
2. 各アクションに担当と期日を添える。書かれていない場合は「未定」とし、推測で埋めない。
3. Agentルートの `knowledge/report-format.md` に沿って要点、根拠、次のアクションをまとめる。提案を決定事項として扱わない。
