# ToolCraftX Arabic AI Prompts Dataset

The **first open-source collection of production-grade Arabic AI prompt templates** — 11 hand-crafted prompts for generating Gulf-region Arabic content, curated from [ToolCraftX](https://toolcraftx.com) (a 14-in-1 Arabic AI toolbox).

Each prompt is provided in **3 languages**: original (Chinese/English), English description, and **native Arabic version** — ready to drop into any LLM (GPT-4, Claude, DeepSeek, Gemini, Qwen).

## File

| File | Records | Description |
|---|---|---|
| `toolcraftx-arabic-prompts.json` | 11 | 11 Arabic AI prompt templates with metadata, original + Arabic prompts, placeholders, use cases |

**Size**: ~25 KB | **License**: CC0 1.0

## Tools Covered

| # | Slug | Name (EN) | Name (AR) | Category |
|---|---|---|---|---|
| 1 | `writer` | Arabic Content Writer | كاتب المحتوى العربي | text-generation |
| 2 | `translator` | Arabic Translator | المترجم العربي | translation |
| 3 | `rewriter` | Arabic Text Polisher | محسن النصوص العربية | text-editing |
| 4 | `image` | AR→EN Image Prompt Translator | مترجم أوامر الصور | image-generation |
| 5 | `seo` | Arabic SEO Specialist | خبير السيو العربي | seo |
| 6 | `ppt` | Arabic PPT Outliner | منشئ العروض التقديمية | presentation |
| 7 | `chat` | Gulf Arabic AI Assistant | المساعد الذكي الخليجي | conversational |
| 8 | `summarize` | Arabic Text Summarizer | ملخص النصوص العربية | summarization |
| 9 | `table_generate` | Arabic Table Generator | منشئ الجداول العربية | structured-output |
| 10 | `table_analyze` | Arabic Data Analyst | محلل البيانات العربي | data-analysis |
| 11 | `script` | Arabic Video Scriptwriter | كاتب السيناريو العربي | video-script |

## Schema

```json
{
  "slug": "writer",
  "name_en": "Arabic Content Writer",
  "name_zh": "阿语内容创作",
  "name_ar": "كاتب المحتوى العربي",
  "category": "text-generation",
  "input_type": "topic + tone",
  "output_lang": "ar",
  "description_en": "Generate original Arabic content...",
  "description_zh": "为海湾市场生成原创阿语内容...",
  "description_ar": "إنشاء محتوى عربي أصلي...",
  "prompt_original": "你是专业的阿拉伯语内容创作专家...",
  "prompt_ar": "أنت كاتب محتوى عربي محترف...",
  "has_fstring_placeholders": true,
  "placeholders": ["tone_desc"],
  "source_url": "https://toolcraftx.com/arabic-writer"
}
```

## Unique Features

### 1. Production-Grade
These prompts power **ToolCraftX** (14-in-1 Arabic AI toolbox) in production — not theoretical templates. Battle-tested against thousands of Gulf-region users.

### 2. Gulf-Specific
All prompts explicitly target **Saudi Arabia / UAE** markets:
- Gulf business register (لغة الأعمال الخليجية)
- Cultural appropriateness for MENA region
- Modern Standard Arabic (فصحى) with Gulf-friendly expressions

### 3. Multi-Modal Coverage
- **Text**: writer / rewriter / translator / chat / summarize
- **Visual**: image (AR→EN prompt translation for Midjourney/DALL-E)
- **Video**: script (TikTok/Reels HOOK-BODY-CTA structure)
- **Data**: table_generate / table_analyze
- **SEO**: full Arabic SEO asset generation
- **Presentation**: ppt outline in Arabic

### 4. Ready-to-Use
Each prompt is a complete system message — just substitute placeholders like `{tone_desc}`, `{cols}`, `{nrows}`, `{style}` and call any LLM.

## Use Cases

- **LLM fine-tuning** — Arabic prompt engineering examples
- **Prompt libraries** — seed data for Arabic prompt marketplaces
- **Chatbots** — drop-in system prompts for Arabic GPT wrappers
- **Education** — learn Arabic prompt engineering from real examples
- **MENA SaaS** — integrate into Arabic-facing AI products
- **Research** — cross-lingual prompt transfer studies (ZH/EN → AR)

## Methodology

- **Source**: ToolCraftX (https://toolcraftx.com) production code
- **Arabic versions**: Hand-crafted by native Arabic linguists + DeepSeek-V3 refinement
- **Quality**: All prompts tested against DeepSeek-V3, GPT-4, Claude in production
- **License**: CC0 1.0 — use freely in any project

## License

**CC0 1.0 Public Domain** — free for any use, commercial or non-commercial.

## Citation

```bibtex
@dataset{toolcraftx_arabic_prompts_2026,
  title={ToolCraftX Arabic AI Prompts Dataset},
  author={ToolCraftX},
  year={2026},
  publisher={Kaggle},
  url={https://github.com/HeTaobaba123/toolcraftx-arabic-prompts},
  note={11 production-grade Arabic prompt templates, 3-language schema, CC0 1.0}
}
```

## Sister Datasets

- [Arabic-Chinese Web Novel Metadata](https://github.com/HeTaobaba123/arabic-chinese-novels-dataset) — 7,476 novels
- [TCM Arabic-Chinese Bilingual Dataset](https://github.com/HeTaobaba123/tcm-arabic-dataset-) — Traditional Chinese Medicine
- [DaoPath Taoist Metaphysics Dataset](https://github.com/HeTaobaba123/daopath-terms-dataset) — I Ching, BaZi, Zi Wei Dou Shu
- [HanseBrief China-Arab Trade News](https://github.com/HeTaobaba123/hansebrief-trade-news-dataset) — 16,996 bilingual trade news

## Contact

- Website: https://toolcraftx.com
- Issues: [GitHub Issues](https://github.com/HeTaobaba123/toolcraftx-arabic-prompts/issues)
