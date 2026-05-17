# 🎨 画像プロンプト一覧｜note 02「AIを思い通りに動かす！プロンプトエンジニアリング基礎とテンプレート集」

このフォルダには、note本文に挿入する8枚のイラスト用プロンプトが入っています。
すべてGPT image2（または同等のAI画像生成ツール）にそのまま貼り付けて使えます。

## 📌 共通スタイルガイド（全イラストで統一）

note_01 と統一感を保つため、同じスタイルガイドを採用しています。

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
| 2 | `02_prompt_concept.md` | 第1章 | プロンプト＝AIへの説明書のイメージ |
| 3 | `03_prompt_structure.md` | 第2章 | プロンプトの6要素構造図 |
| 4 | `04_five_techniques.md` | 第3章 | 5つの基本テクニック図解 |
| 5 | `05_template_collection.md` | 第4章 | 21テンプレート俯瞰イメージ |
| 6 | `06_common_mistakes.md` | 第5章 | よくある失敗と直し方 |
| 7 | `07_custom_template.md` | 第6章 | 自分専用テンプレートを育てる |
| 8 | `08_closing.md` | おわりに | クロージング |

## 🔍 note本文内での挿入位置の見つけ方

本文中に以下のようなHTMLコメントで挿入位置をマークしています。

```markdown
<!-- 📌 画像挿入位置 1：cover.png（記事のカバー画像） -->
```

`画像挿入位置 N` の `N` が、各プロンプトファイルの番号と対応しています。

## 💡 使い方のヒント

- **note_01 とのシリーズ感**：人物の雰囲気・配色トーンを揃えると、シリーズとしての統一感が出ます
- **テクニック解説の図**（04、05）：吹き出し・矢印・カード型レイアウトなどの要素は活かしつつ、文字は埋め込まないこと
- カバー画像（01）は **横長16:9または9:16**、その他は **正方形1:1または横長16:9** を推奨
