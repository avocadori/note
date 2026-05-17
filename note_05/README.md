# 🎨 画像プロンプト一覧｜note 05「AIで簡単にリサーチツールを作るテクニック」

このフォルダには、note本文に挿入する9枚のイラスト用プロンプトが入っています。
すべてGPT image2（または同等のAI画像生成ツール）にそのまま貼り付けて使えます。

## 📌 共通スタイルガイド（全イラストで統一）

note_01〜04 と統一感を保つため、同じスタイルガイドを採用しています。

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
| 2 | `02_landscape.md` | 第1章 | リサーチ自動化が初心者向けに最強な理由 |
| 3 | `03_four_steps.md` | 第2章 | リサーチツールの4ステップ構造 |
| 4 | `04_three_builds.md` | 第3章 | 3つの作り方（軽量／ノーコード／高機能） |
| 5 | `05_recipe_collection.md` | 第4章 | 5つのリサーチレシピ俯瞰 |
| 6 | `06_prompt_tips.md` | 第5章 | リサーチプロンプトのコツ5つ |
| 7 | `07_monetization.md` | 第6章 | 収益化3パターンの育て方 |
| 8 | `08_pitfalls.md` | 第7章 | よくある失敗パターン |
| 9 | `09_closing.md` | おわりに | クロージング |

## 🔍 note本文内での挿入位置の見つけ方

本文中に以下のようなHTMLコメントで挿入位置をマークしています。

```markdown
<!-- 📌 画像挿入位置 1：cover.png（記事のカバー画像） -->
```

`画像挿入位置 N` の `N` が、各プロンプトファイルの番号と対応しています。

## 💡 使い方のヒント

- **note_01〜04 とのシリーズ感**：人物の雰囲気・配色トーンを揃えると、シリーズとしての統一感が出ます
- **データ／調査系の図**：抽象的なシンボル（フィルター、メーター、グラフ、フロー矢印）を活用しつつ、文字は埋め込まないこと
- カバー画像（01）は **横長16:9または9:16**、その他は **正方形1:1または横長16:9** を推奨
