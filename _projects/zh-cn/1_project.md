---
page_id: sta
layout: page
title: 单 Token 安全对齐
description: 通过优化一个前缀 token 实现轻量化安全对齐。
importance: 1
category: research
related_publications: true
---

大语言模型在安全对齐后仍然面临安全性与有用性之间的权衡：一方面可能受到越狱攻击影响，另一方面也可能对正常请求产生过度拒绝。传统 RLHF 类方法训练成本较高，一些 training-free 防御方法则可能带来额外推理开销或依赖特定模型结构。

我们提出 **STA**，只优化一个前缀 token，同时冻结模型全部参数。该方法通过重塑有害样本与良性样本的决策分布，以极少的可训练参数改善模型安全性与有用性之间的平衡，并且不引入额外推理开销。

该项目对应 ACL 2026 论文 "You Only Need One Single Token to Refine Safety Alignment"。
