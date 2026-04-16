# Project Guidelines

## Purpose
このリポジトリは日々の学習内容を記録するための学習ログ集である。
新しいログを作るときは、既存の記法と粒度に合わせる。
参考スタイル:
- Swift系の学習ログは logs/swift 配下の既存ファイル
- Agentic Coding系の学習ログは logs/agentic-coding 配下の既存ファイル

## Log Structure
日次ログは原則として以下の構成にする。
- タイトルは日付
- 今日の作業内容
- 今日学んだこと
- 必要なら実装したこと
- 必要なら明日やること

## Writing Style
- 学習内容は箇条書きだけで終わらせず、何が分かったかを短く説明する
- 単なる作業記録ではなく、再読したときに理解が戻る粒度でまとめる
- コードや表は必要なときだけ使う
- 既存ログの見出しレベルと雰囲気をなるべく揃える
- 日本語で記述する

## Classification
- Swift学習は logs/swift/YYYY-MM-DD.md
- Agentic Coding学習は logs/agentic-coding/YYYY-MM-DD.md
- どちらにも当てはまらない場合は、ユーザーに確認するか、最も近いカテゴリを提案する

## README Update
新しいログを追加したら README の該当セクションにも 1 行追加する。
表示形式は既存の箇条書きと揃える。

## Input Handling
入力が会話ログ、断片メモ、FigJam要約であっても、内容を整理して日次ログ形式に再構成する。
情報が足りないときは勝手に断定せず、曖昧な点を残さないよう補完候補を明示する。