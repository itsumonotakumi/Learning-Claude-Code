# やさしいAIエンジニアリング学習教材

AIコーディングエージェントの「仕組み」と「使いこなし方」を、**初心者〜初級エンジニア向けにかみ砕いて**解説する、日本語の自己完結型 学習教材集です。
インターネット上の一次情報を調べ、「説明が少ない・日本語でない・専門用語が多い」という分かりにくさを解消することを目的に再構成・加筆しました。

## 📚 収録教材（2つ）

| ファイル | テーマ | 内容 |
|---|---|---|
| **`index.html`** | Claude Code の仕組みを理解する | AIコーディングエージェントの内部構造を19テーマ・5レイヤーで解説（エージェントループ〜マルチエージェント） |
| **`loop-engineering.html`** | やさしいループ・エンジニアリング | AI時代の新しい働き方「Loop Engineering」を初級者向けに解説。**ナデラの "Learning loop" との違い**も明確化 |

2つはつながっています。`loop-engineering.html` で出てくる「ループの部品」（自動化・サブエージェント・メモリなど）は、`index.html` で学ぶ仕組みそのものです。**セットで読むと理解が深まります。** 各ページの上部に相互リンクがあります。

## 使い方

**HTMLファイルをブラウザで開くだけ** です。

- インストール・サーバー・ビルドは一切不要
- 外部通信・データ保存を一切行わない、**単一HTMLファイル**（CSS/JSすべて内蔵）
- ファイルを保存すれば**オフラインでも**閲覧可能
- スマホ・PC対応（レスポンシブ）、ライト/ダークテーマ切替つき

```
open index.html              # macOS（loop-engineering.html も同様）
xdg-open index.html          # Linux
start index.html             # Windows
```

## 各教材の構成

### ① Claude Code の仕組みを理解する（`index.html`）
「たった一つのループ」を土台に、5つの層が積み重なる地図で全体を理解します。

| レイヤー | テーマ |
|---|---|
| ⚙️ 1. ツールと実行 | s01 エージェントループ / s02 ツール使用 / s03 権限 / s04 フック |
| 🗺️ 2. 計画と調整 | s05 TodoWrite / s06 サブエージェント / s07 スキル / s10 システムプロンプト / s11 エラー回復 |
| 🧩 3. メモリ管理 | s08 コンテキスト圧縮 / s09 メモリ |
| ⏱️ 4. 並行処理 | s13 バックグラウンドタスク / s14 Cron スケジューラー |
| 🤝 5. マルチエージェント基盤 | s12 タスクシステム / s15 エージェントチーム / s16 チームプロトコル / s17 自律エージェント / s18 Worktree 分離 / s19 MCP ツール |

各テーマは **「なぜ学ぶ?（メリット）→ 概念 → 仕組み → 身近なたとえ → 実物との対応 → 要点」** の順で解説。

### ② やさしいループ・エンジニアリング（`loop-engineering.html`）
なぜ学ぶ? → ループとは → ループの全体像 → 発想の転換（4世代）→ ループの6つの部品 → 回し方（5ステップ）→ **ナデラの "Learning loop" との違い** → 似た概念で理解する → 具体例 → 3つの落とし穴 → 用語辞典。

## 出典・クレジット

- **①**: [learn.shareai.run](https://learn.shareai.run/ja/) / [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code)、Claude Code 公式ドキュメント、Model Context Protocol 公式
- **②**: [Addy Osmani「Loop Engineering」](https://addyosmani.com/blog/loop-engineering/)、[Zenn記事](https://zenn.dev/acrosstudioblog/articles/38509c0473683a)、Satya Nadella のエッセイ/著書、フィードバックループ・OODA・Lean Startup 等の一次情報

いずれも学習目的の二次教材です。新しい用語（Loop Engineering 等）は定義が流動的な点にご留意ください。
