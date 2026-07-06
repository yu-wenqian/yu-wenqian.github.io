---
page_id: magic-image
layout: page
title: Magic Image
description: Visual-prompt safety alignment for multimodal large models.
importance: 2
category: research
related_publications: true
---

Multimodal large models face both jailbreak vulnerabilities and over-refusal problems. A safety mechanism for these models should reduce harmful responses without broadly blocking legitimate multimodal requests.

**Magic Image** explores a lightweight multimodal safety alignment strategy by optimizing image pixels as a visual prompt while freezing the model parameters. The method jointly considers boundary samples and jailbreak samples to improve safety behavior while preserving model usefulness.

This project is associated with our EMNLP 2025 paper, "Reimagining Safety Alignment with An Image."
