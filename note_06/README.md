# 🎨 画像プロンプト一覧｜note 06「AI商品化ワークシート」（シリーズ最終回）

このフォルダには、note本文に挿入する9枚のイラスト用プロンプトが入っています。
すべてGPT image2（または同等のAI画像生成ツール）にそのまま貼り付けて使えます。

## 📌 共通スタイルガイド（全イラストで統一）

note_01〜05 と統一感を保つため、同じスタイルガイドを採用しています。
**シリーズ最終回**として、クロージング画像（09）は「6本完走」を匂わせる構図を意識しています。

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
| 2 | `02_landscape.md` | 第1章 | 「動くもの」と「売れる商品」の対比 |
| 3 | `03_five_stages.md` | 第2章 | 商品化6ステージのフロー |
| 4 | `04_workshop_collection.md` | 第3章 | 6つのワークシート俯瞰 |
| 5 | `05_customer_resolution.md` | 第5章 | 顧客解像度を上げるイメージ |
| 6 | `06_mvp_blueprint.md` | 第7章 | MVPからローンチまでの設計図 |
| 7 | `07_launch_plan.md` | 第9章 | 90日ロードマップのタイムライン |
| 8 | `08_pitfalls.md` | 第10章 | 商品化の失敗パターン |
| 9 | `09_closing.md` | おわりに | シリーズ完結のクロージング |

## 🔍 note本文内での挿入位置の見つけ方

本文中に以下のようなHTMLコメントで挿入位置をマークしています。

```markdown
<!-- 📌 画像挿入位置 1：cover.png（記事のカバー画像） -->
```

`画像挿入位置 N` の `N` が、各プロンプトファイルの番号と対応しています。

## 💡 使い方のヒント

- **シリーズ完結感**：人物の雰囲気・配色トーンを note_01〜05 と完全に揃えること。クロージング（09）は特に「シリーズ完走」を匂わせる構図に
- **ワークシート系の図**：書き込み式の余白感を強調。完成品ではなく「これから埋める」感
- カバー画像（01）は **横長16:9または9:16**、その他は **正方形1:1または横長16:9** を推奨
