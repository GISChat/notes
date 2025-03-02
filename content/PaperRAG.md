---
title: 科研文档友好的RAG技术
tags:
  - RAG
  - Paper
---
AI读文档不是新鲜事，但是如何让AI更聪明的阅读文献还是难题。

当前，RAG采用的通用切块技术在一定程度上减少了服务器性能需求，也减少了文档之间的关联程度。理想情况下，RAG的切块可以是每一个段落+1/3前后段落，这样可以保证单一语意的完整性，也可以保证上下文的连贯性。

下面我们将简单介绍几个RAG+Paper Reading的实现。
- [Zotero GPT](https://mp.weixin.qq.com/s/mjEFHsCZrSh1jS6Acqo60g)
- [NotebookLM](https://notebooklm.google)

### Zotero GPT
