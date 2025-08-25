# Yu-Gi-Oh! Card List Builder (Paste-only)

Yu-Gi-Oh! deck recipes → **card name + count** list generator.  
遊戯王デッキレシピのページ HTML を貼り付けると、モンスター・魔法・罠・エクストラの **カード名＋枚数** を整形して表示・保存できる小さな Web ツールです。

---

## ✨ Features / 特徴

- **Paste-only**: 公式デッキページの HTML をコピー＆貼り付けるだけ  
  → `<!-- ///deck_text -->` 〜 `<!-- #deck_text -->` の範囲を自動抽出して解析  
- **Grouped card list**: Monster / Spell / Trap / Extra ごとにリスト化  
- **One-click copy & save**: 出力をコピーしたり `.txt` 保存可能  
- **Offline ready**: 単一 HTML ファイル。ブラウザで開けばそのまま使える

---

## 📥 Usage / 使い方

1. デッキレシピのページを開き、ブラウザで **ページのソースを表示** してコピー  
2. このツールの **HTMLファイル** をブラウザで開き、テキストエリアに貼り付け  
3. 「カードリスト生成 / Build Card List」ボタンを押す  
4. 整形されたカードリストが表示されます  
   - 「コピー / Copy」ボタンでクリップボードへコピー  
   - 「テキスト保存 / Save as .txt」ボタンでファイル保存  

---

## 🛠 Development

- Pure **Vanilla JavaScript** + HTML + CSS
- No dependencies
- Works locally without a server

---

## 📄 License

MIT License

---

## 🤖 Note

This project was **created with the help of ChatGPT 5**.  
本プロジェクトは **ChatGPT 5** によって生成・整形されました。
