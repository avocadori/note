# 🎨 画像プロンプト一覧｜note 01「AI開発で月10万円を目指すロードマップ」

このフォルダには、note本文に挿入する9枚のイラスト用プロンプトが入っています。
すべてGPT image2（または同等のAI画像生成ツール）にそのまま貼り付けて使えます。

## 📌 共通スタイルガイド（全イラストで統一）

すべてのプロンプトには、以下のスタイル指定を**共通ベース**として組み込んでいます。
これにより、note全体で**統一感のあるトーン＆マナー**を実現します。

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
| 2 | `02_landscape.md` | 第1章 | AI開発を取り巻く環境 |
| 3 | `03_revenue_models.md` | 第2章 | 4つの収益モデル |
| 4 | `04_roadmap_timeline.md` | 第3章 | 6ヶ月ロードマップ |
| 5 | `05_phase1_learning.md` | 第4章 | 学習フェーズ |
| 6 | `06_phase2_mvp.md` | 第5章 | MVP構築・発信 |
| 7 | `07_phase3_monetize.md` | 第6章 | マネタイズフェーズ |
| 8 | `08_pitfalls.md` | 第7章 | 失敗パターン |
| 9 | `09_closing.md` | おわりに | クロージング |

## 🔍 note本文内での挿入位置の見つけ方

本文中に以下のようなHTMLコメントで挿入位置をマークしています。

```markdown
<!-- 📌 画像挿入位置 1：cover.png（記事のカバー画像） -->
```

`画像挿入位置 N` の `N` が、各プロンプトファイルの番号と対応しています。

## 💡 使い方のヒント

- **イラストの人物・小物の色**は、共通スタイルガイドのパレットから2〜3色選ぶと統一感が出ます
- 生成後に「もう少し明るく」「人物を女性にして」など微調整するとさらに洗練されます
- カバー画像（01）は**横長16:9または9:16**、その他は**正方形1:1または横長16:9**を推奨
