# Benchmark

Real-world multimodal emotion recognition often faces two practical challenges: cross-modal conflict and missing modalities. However, many existing datasets only provide a single multimodal label and assume that all modalities are always available, which makes these settings difficult to study systematically. To address this, we introduce EmoMM, a benchmark designed for multimodal emotion recognition under both modality conflict and modality missingness. EmoMM provides both unimodal and multimodal emotion annotations, enabling evaluation under full-modality and missing-modality conditions.

![Overview of the EmoMM benchmark](./EmoMM_Flowchart.png)

*Figure 2. Overview of the EmoMM construction pipeline: data curation for CH-SIMS v2.0 and CMU-MOSI, single-modality human labeling for independent unimodal annotations on CMU-MOSI (CH-SIMS v2.0 provides unimodal labels), followed by statistical analysis and subset partitioning under sentiment conflicts and modality missingness.*

We analyze the label distributions of ground truth, text, audio, and video, and measure the consistency between different sources. The results show that text has the strongest agreement with the ground-truth label, suggesting that lexical information often provides the clearest emotional signal. In contrast, text and video show the weakest agreement, reflecting that visual emotion cues are often more subtle and harder to interpret.

![Overview of the EmoMM benchmark](./EmoMM_statistics.png)

*Figure 3. EmoMM statistics: five-class label distributions (left) and cross-modal agreement coefficients(right).*

