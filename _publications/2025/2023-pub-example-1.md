---
title: "Layout Stroke Imitation: A Layout Guided Handwriting Stroke Generation for Style Imitation with Diffusion Model"
date: 2025-09-19 00:01:00 +0800
selected: true
pub: "arxiv"
pub_date: "2025"
abstract: >-
  Handwriting stroke generation is crucial for improving the performance of tasks such as handwriting recognition and writer’s order recovery. In handwriting stroke generation, it is significantly important to imitate the sample calligraphic style. The previous studies have suggested utilizing the calligraphic features of the handwriting. However, they had not considered word spacing (word layout) as an explicit handwriting feature, which results in inconsistent word spacing for style imitation. Firstly, this work proposes multi-scale attention features for calligraphic style imitation. These multi-scale feature embeddings highlight the local and global style features. Secondly, we propose to include the words layout, which facilitates word spacing for handwriting stroke generation.

  Moreover, we propose a conditional diffusion model to predict strokes in contrast to previous work, which directly generated style images. Stroke generation provides additional temporal coordinate information, which is lacking in image generation. Hence, our proposed conditional diffusion model for stroke generation is guided by calligraphic style and word layout for better handwriting imitation and stroke generation in a calligraphic style.

  Our experimentation shows that the proposed diffusion model outperforms the current state-of-the-art stroke generation and is competitive with recent image generation networks.
cover: /assets/images/covers/layout.png
authors:
  - Sidra Hanif
  - Longin Jan Latecki
links:
  Paper: https://arxiv.org/abs/2509.15678
---

