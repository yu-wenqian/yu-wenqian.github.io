---
page_id: magic-image
layout: page
title: Magic Image
description: 面向多模态大模型的视觉提示安全对齐方法。
importance: 2
category: research
related_publications: true
---

多模态大模型同时面临越狱攻击与过度拒绝问题。一个有效的安全机制应当在降低有害响应的同时，尽量避免误拒合法的多模态请求。

**Magic Image** 探索通过优化图像像素作为视觉提示来实现轻量化多模态安全对齐，同时冻结模型参数。该方法联合考虑边界样本与越狱样本，以改善模型安全行为并保持有用性。

该项目对应 EMNLP 2025 论文 "Reimagining Safety Alignment with An Image"。
