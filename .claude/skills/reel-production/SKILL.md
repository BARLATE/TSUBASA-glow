---
name: reel-production
description: Instagramリールを1本制作するときに使う。「リールを1本作って」「リール作成」などの依頼で起動し、instagram-ai-team の28担当ワークフローに沿って、受付→リサーチ→企画→台本→レビュー→素材→編集→品質確認→投稿→分析→改善提案の順に進める。Threads投稿文もセットで作る。
---

# リール制作スキル（v1.0）

## 開始前
1. `instagram-ai-team/rules/` をすべて読み込む（トーン・NG・KPI・承認・法令・媒体・実行環境）。
2. `instagram-ai-team/open-items.md` を確認し、今回の作業を止める未決事項があれば、オーナーに1問ずつ質問する。

## 受付（R28 進行管理）
3. `instagram-ai-team/workflow/reel-production.md` の「受付時の確認項目」で不足している項目だけを、1問ずつ質問する。確定済みの前提（トーンA・一人称「僕」・尺30〜45秒・AI音声・顔出しなし）は聞き直さない。
4. 案件IDを発行し、`projects/<id>/status.md` に工程表を作る。

## 制作
5. `instagram-ai-team/team/roles.md` の各担当の手順・出力・完了条件に従って、①〜⑨の順に進める。担当の境界は `team/responsibility-matrix.md` に従う。
6. 承認ゲート（G1・G2・G3・G4）と `rules/approval-policy.md` にある作業は、実行前に必ず止めて承認を依頼する。返事がないことを承認と見なさない。
7. 出典のない数値・事実・体験談は作らず、`【要確認】` と明記する。実践記録は、オーナーへの聞き取りの内容だけを使う。

## ルールの更新
8. オーナーからルールの指示を受けたら、該当する `rules/*.md` を更新し、`rules/CHANGELOG.md` と、必要に応じて `hearing/hearing-log.md` に記録する。
