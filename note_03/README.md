# 🎨 画像プロンプト一覧｜note 03「CursorやClaudeで爆速開発！プログラミング初心者でもコードが書けるようになる方法」

このフォルダには、note本文に挿入する9枚のイラスト用プロンプトが入っています。
すべてGPT image2（または同等のAI画像生成ツール）にそのまま貼り付けて使えます。

## 📌 共通スタイルガイド（全イラストで統一）

note_01／note_02 と統一感を保つため、同じスタイルガイドを採用しています。

```
Style: Flat vector illustration, modern Japanese editorial style,
soft pastel color palette (mint green #B8E0D2, soft pink #F4C7C3, 
sky blue #B5D8EB, cream beige #F5E8C7, warm gray #E0DDD3),
clean lines, friendly and approachable mood,
white or very light background, plenty of negative space,
no text or letters in the image,
business and tech theme, optimistic atmosphere
```

## 📁 ファイル一覧と挿入位置

| No. | ファイル名 | 挿入位置 | 内容 |
|-----|-----------|---------|------|
| 1 | `01_cover.md` | 記事冒頭 | カバー画像 |
| 2 | `02_landscape.md` | 第1章 | 2026年のAIコーディング環境 |
| 3 | `03_tool_comparison.md` | 第2章 | 4大AIコーディングツールの比較 |
| 4 | `04_cursor_workflow.md` | 第3章 | Cursorで自然言語コーディングする流れ |
| 5 | `05_claude_code_dialog.md` | 第4章 | ターミナルでClaude Codeと対話するイメージ |
| 6 | `06_seven_tips.md` | 第5章 | 7つのコツの図解 |
| 7 | `07_recipe_collection.md` | 第6章 | 実例レシピ集 |
| 8 | `08_pitfalls.md` | 第7章 | 失敗パターン |
| 9 | `09_closing.md` | おわりに | クロージング |

## 🔍 note本文内での挿入位置の見つけ方

本文中に以下のようなHTMLコメントで挿入位置をマークしています。

```markdown
<!-- 📌 画像挿入位置 1：cover.png（記事のカバー画像） -->
```

`画像挿入位置 N` の `N` が、各プロンプトファイルの番号と対応しています。

## 💡 使い方のヒント

- **note_01／note_02 とのシリーズ感**：人物の雰囲気・配色トーンを揃えると、シリーズとしての統一感が出ます
- **コード／ツールのイメージ**：実際のUIスクリーンショットを使わず、抽象的なシンボル（ブラケット、ターミナル風の枠など）に置き換えて表現すること
- カバー画像（01）は **横長16:9または9:16**、その他は **正方形1:1または横長16:9** を推奨
