---
name: Research Interests
about: Configure paper search topics
title: Research Interests
labels: config
assignees: ''
---

把下面 JSON 里的 `include_terms`、`exclude_terms`、`journals` 和 `topics[*].keywords` 当成可编辑清单即可。

```json
{
  "sources": [
    {
      "type": "openalex",
      "name": "OpenAlex Translation Journals",
      "journals": [
        "Target",
        "Perspectives",
        "The Translator",
        "Translation Studies",
        "Meta",
        "Babel",
        "Translation Spaces",
        "Across Languages and Cultures",
        "The Journal of Specialised Translation",
        "Translation and Interpreting Studies",
        "TTR",
        "Interpreter and Translator Trainer",
        "Journal of Literary Semantics",
        "Language and Literature",
        "Discourse Studies",
        "Narrative"
      ]
    },
    {
      "type": "crossref",
      "name": "Crossref Translation Journals",
      "journals": [
        "Target",
        "Perspectives",
        "The Translator",
        "Translation Studies",
        "Meta",
        "Babel",
        "Translation Spaces",
        "Across Languages and Cultures",
        "The Journal of Specialised Translation",
        "Translation and Interpreting Studies",
        "TTR",
        "Interpreter and Translator Trainer",
        "Journal of Literary Semantics",
        "Language and Literature",
        "Discourse Studies",
        "Narrative"
      ]
    }
  ],
  "include_terms": [
    "translation studies",
    "translation",
    "translator",
    "interpreting",
    "literary translation",
    "Chinese-English translation",
    "corpus linguistics",
    "discourse",
    "linguistics",
    "language",
    "stylistics",
    "narratology",
    "narrative",
    "cognitive linguistics",
    "cognitive poetics",
    "systemic functional linguistics",
    "rewriting",
    "Lefevere",
    "poetics",
    "patronage",
    "ideology",
    "Bourdieu",
    "field theory",
    "habitus",
    "capital",
    "symbolic capital",
    "sociology of translation",
    "translator agency",
    "translation norms",
    "translation history"
  ],
  "exclude_terms": [
    "agriculture",
    "fertilizer",
    "biochar",
    "crop",
    "rice",
    "soil",
    "irrigation",
    "nutrient",
    "chemistry",
    "physics",
    "materials science",
    "clinical",
    "medicine",
    "engineering",
    "environmental science"
  ],
  "conference_sources": {
    "enabled": false
  },
  "topics": [
    {
      "id": "rewriting_field_translation_studies",
      "name": "勒费弗尔改写理论与布迪厄场域理论",
      "description": "关注勒费弗尔改写理论、操纵学派、意识形态、诗学、赞助人、译者主体性，以及布迪厄的场域、惯习、资本、象征资本和翻译社会学。",
      "keywords": [
        "Lefevere rewriting theory",
        "rewriting theory",
        "poetics and translation",
        "ideology and translation",
        "patronage and translation",
        "Bourdieu field theory",
        "Bourdieu and translation",
        "sociology of translation",
        "translation field",
        "translator habitus",
        "symbolic capital translation",
        "translator agency",
        "translation norms",
        "literary translation reception",
        "paratext and translation",
        "translation history"
      ],
      "arxiv_categories": []
    },
    {
      "id": "cognitive_translation_studies",
      "name": "认知取向的翻译研究",
      "description": "关注认知翻译研究、认知语言学与翻译、体认语言学、译者认知、翻译过程、概念隐喻、识解、框架语义和意义建构。",
      "keywords": [
        "cognitive translation studies",
        "cognitive translatology",
        "cognitive linguistics and translation",
        "embodied cognition and translation",
        "translator cognition",
        "translation process research",
        "conceptual metaphor translation",
        "metaphor translation",
        "construal in translation",
        "frame semantics translation",
        "cognitive poetics translation",
        "Chinese-English literary translation"
      ],
      "arxiv_categories": []
    },
    {
      "id": "narratology_and_translation",
      "name": "叙事学与翻译研究",
      "description": "关注叙事视角、聚焦、声音、时间、人物塑造、叙事身份、重述、再叙事和翻译中的叙事重构。",
      "keywords": [
        "narratology and translation",
        "narrative translation",
        "narrative theory translation",
        "re-narration",
        "narrative framing translation",
        "focalization translation",
        "narrative voice translation",
        "point of view translation",
        "characterization in translation",
        "fiction translation narratology"
      ],
      "arxiv_categories": []
    },
    {
      "id": "corpus_discourse_stylistic_translation",
      "name": "语料库、话语与文体翻译研究",
      "description": "关注语料库翻译研究、话语分析、批评话语分析、系统功能语言学、文体学、译者风格、关键词、搭配、语义韵和评价系统。",
      "keywords": [
        "corpus-based translation studies",
        "corpus translation studies",
        "parallel corpus translation",
        "comparable corpus translation",
        "translator style",
        "translation norms corpus",
        "keywords in translation",
        "collocation translation",
        "semantic prosody translation",
        "corpus-assisted literary translation",
        "critical discourse analysis translation",
        "systemic functional linguistics translation",
        "appraisal theory translation",
        "stylistics and translation"
      ],
      "arxiv_categories": []
    },
    {
      "id": "translation_technology_translator_studies",
      "name": "翻译技术、机器翻译与译者研究",
      "description": "只保留与翻译学、译者研究、文学翻译、人机协同、译后编辑、翻译伦理和翻译质量评价直接相关的技术研究。",
      "keywords": [
        "machine translation and translation studies",
        "neural machine translation",
        "literary machine translation",
        "LLM-assisted translation",
        "computer-assisted translation",
        "post-editing",
        "translator-computer interaction",
        "translation technology",
        "translation quality assessment",
        "translator agency technology",
        "translation ethics",
        "translator subjectivity"
      ],
      "arxiv_categories": []
    }
  ]
}
```
