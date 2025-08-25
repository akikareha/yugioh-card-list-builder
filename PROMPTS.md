# PROMPTS.md

This document summarizes the main prompts given to ChatGPT 5 in the process of creating this tool.  
本ツールを作るにあたり、ChatGPT 5 に与えた主なプロンプトの概略をまとめています。

---

## Initial Idea / 最初の発想
- 「遊戯王の公式カードデータベースに公開されているデッキレシピを読めるか？」  
- 「画像ではなく、HTMLに埋め込まれているカード名（span/title属性など）を取り出せるのでは？」  

---

## Extracting Deck HTML Snippet / HTML断片の抽出
- 「デッキレシピのURLから取得したHTMLの `<!-- ///deck_text -->` から `<!-- #deck_text -->` までを切り出し、テキストエリアに表示するツールを Vanilla JavaScript で作れないか？」  

---

## Simplification / 単純化
- 「CORS問題があるので、URL取得はやめて HTML貼り付け専用にしよう」  
- 「説明は日本語と英語を併記してほしい」  
- 「UIを簡略化して、抽出・コピー・保存に絞ろう」  

---

## Card List Formatting / カードリスト整形
- 「Monster / Spell / Trap / Extra ごとに、カード名＋枚数のリストを整形する機能を追加して」  
- 「整形結果もコピーや保存ができるようにして」  

---

## Final Adjustment / 最終調整
- 「抽出結果の表示・保存は不要。**カード名＋枚数リストの生成と保存**をメイン機能にして」  
- 「GitHubに置くから README.md を作って」  
- 「どんなプロンプトで生成されたか概略を PROMPTS.md にまとめて」 ← この依頼

---

## Note
The actual implementation code and documentation were generated iteratively, based on the above requests and refinements.  
実際の実装コードとドキュメントは、上記の要望を基に段階的に生成・改善されました。
