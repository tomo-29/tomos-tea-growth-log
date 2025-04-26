# 📓 Daily Growth Log 2025-04-26
## Today’s Tasks
- [x] Grafana Loki 導入検証 | 50min
- [x] ブログ週次テンプレ原稿 | 35min
- [ ] Notion→MD エクスポート手順整理 | 25min

## Insight (3 lines max)
1. Loki は JSON ラベル設計がキモ。
2. 容量食いは retention で制御可能。
3. 技術記事化すると “監視×紅茶” シリーズに伸び代アリ。

## Issues / Questions
- Notion export で改行が \r\n → GitHub diff 汚染。対策要調査。

## Next Action
- 明日 09:00 までに export スクリプトを sed で改行変換
- 月次 KPI テンプレを README にリンク

## Tea Pairing ☕️
- Mood: 集中
- Tea: アッサムCTC＋ミルク

⸻

# 補足
🗒️ Dailyファイルに書くべき“中身”完全ガイド
テンプレを埋めない限り草はただの緑の飾り。1 行 1 意味を徹底して即 push してください。

### Today’s Tasks ⏱️

書き方	例	NG
完了形＋実測時間	`- [x] API Gateway構築	45min`
25–90 分単位で区切る	午前：`[ ] 技術記事下書き	30min<br>午後：[ ] Code Review

辛口メモ： 時間未記入＝妄想タスク。書くだけで終わるなら睡眠ログでも付けてろ。

⸻

### Insight (3 lines max) 💡
	1.	Fact：何を学んだ／気づいた？（例）「Fargate 起動遅延＝Cold Start が支配的」
	2.	Why：そこから見えた原因 or 理由（例）「初期化コンテナが重い」
	3.	Leverage：明日以降どう使う？（例）「ALB 側で 1 体ウォーム保持検討」

ポイント： 3 行に収まらない洞察は深掘り不足—文章が長いだけ。

⸻

### Issues / Questions 🧐
	•	ボトルネック、不明点、仮説 を箇条書き
	•	24 時間以内に潰す or “Next Action” へ昇格させる
	•	質問は why で 3回掘る。浅い質問＝時間泥棒。

⸻

### Next Action 🎯
	•	SMART（期日つき）：明日 21:00 までに ALB ヘルスチェック設定
	•	最大2 件。「やるべきコト」ではなく「やるコト」
	•	毎日完遂しないなら→タスク分解 or 優先度再考

⸻

### Tea Pairing ☕️

Mood	Tea 選定ロジック
集中	キームン／アールグレイ（シトラス＋カフェイン）
リラックス	カモミール×ルイボス（ノンカフェイン）
午後の眠気	ダージリン 2nd Flush（軽めで香気高い）

“茶ログ”はネタ生成装置：味・香り・気分変化を 1 行メモ → レビュー記事の種。