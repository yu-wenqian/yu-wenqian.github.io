---
page_id: sta
layout: page
title: Single-Token Safety Alignment
description: Lightweight safety alignment by optimizing one prefix token.
importance: 1
category: research
related_publications: true
---

Large language models often face a difficult trade-off after safety alignment: they may still be vulnerable to jailbreak attacks while also over-refusing benign requests. Existing RLHF-style methods can be expensive to train, while training-free defenses may introduce extra inference cost or depend heavily on model architecture.

We propose **STA**, a lightweight safety alignment method that optimizes only one prefix token while freezing the full model. By reshaping the decision distribution of harmful and benign samples, STA aims to improve the safety-helpfulness trade-off with minimal trainable parameters and no additional inference overhead.

This project is associated with our ACL 2026 paper, "You Only Need One Single Token to Refine Safety Alignment."
