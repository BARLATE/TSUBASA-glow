# Instagram運用 AI社員チーム（28名）

> ステータス: **v1.0（ヒアリング完了・2026-11-10）**
> 残っている決めごとは `open-items.md` に一覧化。`【未確定】`・`【要確認】` の箇所に推測で値を入れることはしない。

## 運用の前提（ヒアリングで確定）
| 項目 | 内容 | ファイル |
|---|---|---|
| 発信内容 | Threadsをゼロから始めて副収入を目指す実践記録 | `rules/account-profile.md` |
| 媒体 | Instagram（リール週2〜3本）＋ Threads（毎日1〜2投稿） | `rules/platforms.md` |
| 収益化 | 自分のnote（段階型：無料で発信 → 月次レポートでオーナーが有料化を判断）。アフィリエイトはしない | `rules/note-product.md` |
| トーン | パターンA：等身大の実践者、一人称「僕」、尺30〜45秒、AI音声ナレーション、顔出しなし | `rules/tone-and-structure.md` |
| NG | NG表現5件、企画のNG条件6件 | `rules/ng-expressions.md`, `rules/ng-themes.md` |
| 指標 | フェーズ1の指標を、投稿の24時間後と7日後に計測 | `rules/kpi.md` |
| 承認 | G1テーマ／G2台本／G3完成動画／G4投稿＋GT（Threadsの週次）＋随時 | `rules/approval-policy.md` |
| 自動化 | 全工程。投稿はAPI連携（準備が整うまでは手動投稿） | `rules/automation-scope.md`, `rules/tech-stack.md` |
| 定例 | 週次は日曜日、月次は毎月1日 | `rules/schedule.md` |

## ルールの更新方法
「〇〇をNGに追加して」のように指示すると、該当する `rules/*.md` を更新し、`rules/CHANGELOG.md` に記録する。

## ディレクトリ構成

| パス | 内容 | 更新タイミング |
|---|---|---|
| `team/roles.md` | 28担当の定義（目的・入力・手順・出力・完了条件・引き継ぎ） | 担当の追加・変更時 |
| `team/responsibility-matrix.md` | 重複しやすい役割の責任範囲（RACI） | 担当の境界が変わったとき |
| `workflow/reel-production.md` | 「リールを1本作って」から投稿・分析までの流れ | 工程の変更時 |
| `rules/*.md` | 運用ルール（トーン・NG表現・NG企画・KPI・承認・品質） | オーナーの指示を受けたとき |
| `rules/CHANGELOG.md` | ルール変更履歴 | ルール変更のたび |
| `hearing/hearing-log.md` | ヒアリングの質問と回答の記録 | 質問するたび |
| `open-items.md` | 未決事項の一覧 | 決まるたび |
| `templates/` | 依頼票・引き継ぎ票・承認依頼のひな形 | 必要に応じて |
| `../.claude/skills/reel-production/SKILL.md` | Claude Code から「リールを1本作って」で起動するスキル | 工程・ルール変更時 |

## 基本原則（全担当共通）

1. **事実を作らない**: 出典のない数値・事実・引用は書かず、`【要確認】` と明記する。
2. **不明点は質問する**: 判断に必要な情報が足りないときは、推測で進めずにオーナーへ質問する。
3. **承認ゲートを守る**: `rules/approval-policy.md` にある作業（投稿・公開・費用の発生・外部への送信など）は、実行する前にオーナーの承認を得る。
4. **ルールは単一の情報源**: トーン・NG・KPIは `rules/` だけを正とし、各担当は作業前に必ず参照する。
5. **引き継ぎは票で行う**: 担当間の受け渡しは `templates/handoff.md` の形式で行う。
