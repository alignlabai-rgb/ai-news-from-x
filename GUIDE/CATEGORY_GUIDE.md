# Tech News Hub - Category Guide

## Overview
This repository organizes tech news from X into 6 numbered categories.

**Live Site (GitHub Pages)**: https://alignlabai-rgb.github.io/ai-news-from-x/

## Numbered Categories (01-06)

| No. | Category                    | Folder Name                  | Scope                                              | Update Frequency      |
|-----|-----------------------------|------------------------------|----------------------------------------------------|-----------------------|
| 01  | AI                          | `01-ai`                      | General AI models, tools, applications             | Daily                 |
| 02  | Chinese AI & Tech           | `02-chinese-ai`              | Chinese AI and related technologies                | Daily or every other day |
| 03  | AI Agents                   | `03-ai-agents`               | Autonomous agents and automation                   | Daily or every other day |
| 04  | Hardware & Physical Tech    | `04-hardware-physical-tech`  | Semiconductors, IOWN, photonics, new memory, physical innovations | Weekly or on major news |
| 05  | Longevity & Biotech         | `05-longevity`               | Anti-aging, longevity, biotech                     | 2-3 times per week    |
| 06  | Generative AI & Creative Tools | `06-generative-ai`        | Image/video generation, manga/short video tools, IP creation support | Daily or every other day |

## How to Request News

Please use the category number:
- "01の今日のニュース作って"
- "04 Hardwareの2026-05-16分を作成"
- "06を更新して"

## Folder Structure

```
ai-news-from-x/
├── index.html
├── GUIDE/CATEGORY_GUIDE.md
├── categories/
│   ├── 01-ai/
│   ├── 02-chinese-ai/
│   ├── 03-ai-agents/
│   ├── 04-hardware-physical-tech/
│   ├── 05-longevity/
│   └── 06-generative-ai/
└── ...
```

## Output Rules
- Create daily digests in `categories/XX-xxx/digests/YYYY-MM-DD.html`
- Use Tailwind CSS via CDN for modern design
- Keep consistent styling with the hub page
- Include the category number in titles

## For Other AI Agents (Codex, etc.)

1. Read this file first.
2. Use the numbered category system.
3. Match the existing HTML style.
4. If unsure about structure, check the repository or ask to confirm current folders.

**Last Updated**: 2026-05-16