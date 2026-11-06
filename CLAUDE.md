# CLAUDE.md

## Instagram スキル（.claude/skills/ig-*）

- 話し方の設定（voice.md）は、このリポジトリの `.claude/instagram/voice.md` にある。
  ig-* スキルが `~/.claude/instagram/voice.md` を探して見つからない時は、こちらを読むこと。
- voice.md を更新したら、`.claude/instagram/voice.md` のほうを直してコミットする。

## Instagram AI 社員チーム（28人）

- 「リールを1本作って」などの依頼は `/ig-team`（.claude/skills/ig-team）で進める。
- 担当の定義: `.claude/agents/ig-01-*.md` 〜 `ig-28-producer.md`
- 運用ルール: `.claude/instagram/rules/`（goals・tone・ng-expressions・plan-ng・quality・metrics・workflow）。
  ユーザーが条件を足したら、該当ファイルの表に1行足し、履歴に日付を書いてコミットする。
- 根拠のない数字・事実は作らない。承認ゲート（テーマ・台本・投稿前）は必ずユーザーに確認する。
