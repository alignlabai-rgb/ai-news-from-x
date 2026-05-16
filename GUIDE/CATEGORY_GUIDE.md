# Tech News Hub - Category Guide (Final)

## Overview
Xから集めた技術ニュースを**番号付き6カテゴリ**で管理しています。

**Live Site**: https://alignlabai-rgb.github.io/ai-news-from-x/

目標：**毎日更新しやすいボリューム**を確保するため、各カテゴリの範囲を適切に広げています。

## Numbered Categories (01-06)

| No. | Category Name                          | Folder                        | Scope                                                                 | Update Frequency          |
|-----|----------------------------------------|-------------------------------|-----------------------------------------------------------------------|---------------------------|
| 01  | AI                                     | `01-ai`                       | AIモデル・ツール・応用・ブレークスルー全般                           | 毎日                      |
| 02  | Chinese AI & Tech                      | `02-chinese-ai`               | 中国発のAIと関連ハードウェア・技術                                    | 毎日 or 隔日              |
| 03  | AI Agents                              | `03-ai-agents`                | 自律型エージェント・マルチエージェント・自動化システム                | 毎日 or 隔日              |
| 04  | Hardware & Physical Tech               | `04-hardware-physical-tech`   | 半導体、新デバイス、IOWN、フォトニクス、新メモリ、エネルギー技術（先進核融合含む）など物理層の新技術 | 毎日〜週2回程度           |
| 05  | Longevity, Biotech & Molecular Biology | `05-longevity`                | アンチエイジング・長寿研究＋分子生物学・バイオテクノロジーの大きな発見 | 週2〜3回                  |
| 06  | Generative AI & Creative Tools         | `06-generative-ai`            | 画像・動画生成、漫画・ショート動画作成ツール、IP制作向け生成AI        | 毎日 or 隔日              |

## Request Examples
- 「01の今日のニュース作って」
- 「04 Hardwareの2026-05-16分を作成」
- 「06を更新して」

## Folder Structure
```
ai-news-from-x/
├── index.html
├── GUIDE/CATEGORY_GUIDE.md
└── categories/
    ├── 01-ai/
    ├── 02-chinese-ai/
    ├── 03-ai-agents/
    ├── 04-hardware-physical-tech/
    ├── 05-longevity/
    └── 06-generative-ai/
```

## Output Guidelines
- 各ダイジェストは `categories/XX-xxx/digests/YYYY-MM-DD.html` に保存
- Tailwind CSS CDNを使用したモダンなデザイン
- ハブページとスタイルを統一
- タイトルに番号を入れる

## For Other AI Agents
このファイルを最初に読んでから作業してください。
番号で指定されたカテゴリを優先し、現在のハブページのスタイルに合わせてください。

**Last Updated**: 2026-05-16