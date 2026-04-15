# Overview

Multimodal Emotion Recognition (MER) aims to understand human affect from text, audio, and visual signals, but real-world multimodal inputs are often incomplete or contradictory across modalities, making reliable prediction difficult. Although recent Multimodal Large Language Models (MLLMs) have shown strong potential for MER, their internal decision-making under modality conflict and missingness remains underexplored. To study this systematically, we introduce **EmoMM**, a benchmark covering aligned, conflict, and missing-modality settings, and use it to evaluate multiple MLLMs. Our analysis reveals a **Video Contribution Collapse (VCC)** phenomenon, where models sharply underutilize video evidence in challenging cases, largely due to video-token redundancy and stable modality preference. To address this issue, we further propose **CHASE**, a lightweight conflict-aware inference-time attention steering method that improves cross-modal evidence integration and enhances robustness under conflict and missing-modality conditions. 

![Overview of the EmoMM benchmark](./EmoMM_subset.png)

*Figure 1. Overview of the EmoMM benchmark. Left: subset split of EmoMM into EmoMM-Align, EmoMM-Conflict, and EmoMM-Missing. Right: example instances illustrating the three subsets.*
