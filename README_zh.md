---
languages:
  - en
  - zh
  - ja
---

# CJL Skills Collection

[English](./README.md) · [简体中文](./README_zh.md) · [日本語](./README_ja.md)

---

## 技能一览

| 技能 | 说明 |
|------|------|
| **cjl-card** | **内容铸卡**：将内容转为 PNG 视觉卡片（长图、信息图、海报）。信息图模式根据内容密度、结构和情绪自动生成独特视觉构图，形式服务于内容，无固定模板。 |
| **cjl-learn** | **概念解剖**：从八个方向切开一个概念（历史、辩证、现象、语言、形式、存在、美感、元反思），最后压成一句顿悟，输出 org-mode 文件。 |
| **cjl-paper** | **论文阅读器**：为非学术人士提取论文中的想法，重理解不重批判。 |
| **cjl-plain** | **白话引擎**：把任何内容改写到聪明的十二岁小孩也能懂的程度。 |
| **cjl-rank** | **降秩引擎**：给一个领域，找出背后真正撑着它的几根独立的力。现象砍到不可再少的生成器，砍完能把现象一个个生回来，才算数。 |
| **cjl-x-download** | **X 媒体下载**：将 X/Twitter 帖子中的图片和视频下载到 ~/Downloads。 |
| **cjl-skill-map** | **技能地图**：扫描所有已安装技能，渲染可视化总览。 |
| **cjl-word** | **英语单词精通**：深度拆解一个英语单词的核心语义和顿悟时刻。 |
| **cjl-writes** | **写作引擎**：带着一个观点出发，在写的过程中把它想透。 |
| **cjl-roundtable** | **圆桌讨论**：以求真为目标的结构化多人辩证对话框架，主持人引导真实历史/当代人物进行多轮深度交锋，每轮生成 ASCII 思考框架图，最终输出知识网络。 |
| **cjl-travel** | **旅行研究**：输入城市名，自动生成深度文化研究文档（org-mode）+ 便携卡片（PNG）。覆盖历史分层、博物馆重点、古建看点、考古发现，方法论借鉴考古学案头研究（DBA）。 |
| **cjl-invest** | **投资研究**： |
| **cjl-slides** | **HTML 演示文稿**：支持 24 种国际设计风格的 HTML 幻灯片生成，可导出 PPTX。 |
| **cjl-relationship** | **关系图谱**： |
| **cjl-paper-river** | **论文河流**： |

## 工作流一览

| 工作流 | 说明 |
|--------|------|
| **cjl-paper-flow** | cjl-paper → cjl-card：读论文 + 做卡片一气呵成。 |
| **cjl-word-flow** | cjl-word → cjl-card：单词深度分析 + 信息图卡片一气呵成。 |
| **cjl-travel** | Research → ContentAnalysis → cjl-card：城市文明研究 + org 文档 + 便携卡片一气呵成。 |

---

## 安装方式

### 插件方式（推荐）

```bash
/install-plugin https://github.com/0xcjl/cjl-plugin
```

### 手动安装

```bash
git clone https://github.com/0xcjl/cjl-plugin.git ~/.claude/plugins/cjl-plugin
```

---

## 使用方法

激活任意技能：

```
/cjl-card [内容]
/cjl-paper [论文内容]
/cjl-slides [主题]
/cjl-travel [城市名]
...
```

---

## 设计思路

每个技能均围绕特定认知场景设计：

- **信息转化类**（card、slides）：将抽象内容转化为直观视觉形态
- **理解深化类**（paper、learn、word）：帮助非专业人士快速掌握核心概念
- **结构探索类**（rank、roundtable）：从多角度解构复杂现象
- **工作流类**（paper-flow、word-flow、travel）：串联多个技能，一句话完成复杂任务

---

## 参考来源

本插件集合的 base 结构参考自 [lijigang/ljg-skills](https://github.com/lijigang/ljg-skills)。

---

## 更新日志

### v1.0.0

- 初始版本
- 17 个技能 + 3 个工作流
