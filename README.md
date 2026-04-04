---
languages:
  - en
  - zh
  - ja
---

# CJL Skills Collection

[English](./README.md) · [简体中文](./README_zh.md) · [日本語](./README_ja.md)

---

## Skills Overview

| Skill | Description |
|-------|-------------|
| **cjl-card** | **Visual Card Generator**: Transform content into PNG visual cards (long-form images, infographics, posters). The infographic mode auto-generates unique compositions based on content density, structure, and tone—no fixed templates, form serves content. |
| **cjl-learn** | **Concept Dissection**: Dissect a concept from 8 angles (history, dialectics, phenomenon, language, form, existence, aesthetics, meta-reflection), compress into a single epiphany. Output: org-mode file. |
| **cjl-paper** | **Paper Reader**: Extract ideas from academic papers for non-academics. Emphasis on understanding, not critique. |
| **cjl-plain** | **Plain Language Engine**: Rewrite any content to a level a smart 12-year-old can understand. |
| **cjl-rank** | **Dimension Reducer**: For a given domain, identify the few independent forces that truly hold it up. A generator that strips phenomena to the irreducible minimum—and can regenerate every phenomenon from those roots. |
| **cjl-x-download** | **X Media Downloader**: Download images and videos from X/Twitter posts to ~/Downloads. |
| **cjl-skill-map** | **Skill Map**: Scan all installed skills and render a visual overview. |
| **cjl-word** | **Word Mastery**: Deep dissection of a word's core semantics and "aha" moment. |
| **cjl-writes** | **Writing Engine**: Start with a point of view, think it through in the act of writing. |
| **cjl-roundtable** | **Roundtable Discussion**: Truth-seeking structured multi-person dialectical dialogue framework. Host guides real historical/contemporary figures through multiple rounds of deep交锋, each round generating an ASCII thinking framework, outputting a knowledge network. |
| **cjl-travel** | **Travel Research**: Input a city name, auto-generate deep cultural research document (org-mode) + portable cards (PNG). Covers historical layers, museum highlights, ancient architecture, archaeological findings. Methodology draws from archaeological desk research (DBA). |
| **cjl-invest** | **Investment Research**: To be explored. |
| **cjl-slides** | **HTML Presentations**: Generate HTML slides in 24 international design styles, exportable to PPTX. |
| **cjl-relationship** | **Relationship Graph**: To be explored. |
| **cjl-paper-river** | **Paper River**: To be explored. |

## Workflows Overview

| Workflow | Description |
|----------|-------------|
| **cjl-paper-flow** | cjl-paper → cjl-card: Read paper + make card in one go. |
| **cjl-word-flow** | cjl-word → cjl-card: Deep word analysis + infographic card in one go. |
| **cjl-travel** | Research → ContentAnalysis → cjl-card: City civilization research + org document + portable card in one go. |

---

## Installation

### Plugin (Recommended)

```bash
/install-plugin https://github.com/0xcjl/cjl-plugin
```

### Manual

```bash
git clone https://github.com/0xcjl/cjl-plugin.git ~/.claude/plugins/cjl-plugin
```

---

## Usage

Activate any skill:

```
/cjl-card [content]
/cjl-paper [paper content]
/cjl-slides [topic]
/cjl-travel [city name]
...
```

---

## Design Philosophy

Each skill is designed around a specific cognitive scenario:

- **Information transformation** (card, slides): Convert abstract content into intuitive visual forms
- **Understanding deepening** (paper, learn, word): Help non-experts quickly grasp core concepts
- **Structure exploration** (rank, roundtable): Deconstruct complex phenomena from multiple angles
- **Workflow** (paper-flow, word-flow, travel): Chain multiple skills to complete complex tasks in one command

---

## Credits

The base structure of this plugin collection is inspired by [lijigang/ljg-skills](https://github.com/lijigang/ljg-skills).

---

## Changelog

### v1.0.0

- Initial release
- 17 skills + 3 workflows
