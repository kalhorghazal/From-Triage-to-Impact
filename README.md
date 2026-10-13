# From-Triage-to-Impact

This repository contains the dataset and analysis code for the paper:

**Title:** "From Triage to Impact: A Multi-Hop Reasoning Benchmark for Explainable Persian Hate Speech"

**Abstract:** "Hate speech has become increasingly prevalent on social media, raising concerns about its detection, interpretation, and moderation. Persian, a relatively low-resource language, lacks sufficient annotated data and computational resources for fine-grained hate speech analysis. In this study, we introduce a fine-grained, multi-hop benchmark for explainable Persian hate speech analysis, covering content triage, target identification, hate tactic and moral foundation analysis, textual evidence extraction, harmful narrative inference, and severity assessment. By evaluating state-of-the-art large language models (LLMs), we find that performance generally declines as tasks require more fine-grained semantic and inferential reasoning. Proprietary models generally outperform open-weight models, while reasoning-oriented models show no consistent advantage. Incorporating intermediate reasoning steps substantially improves severity prediction compared with one-shot assessment. Our analysis further reveals that Incitement to Violence or Harm is most strongly associated with higher severity, while political-affiliation targets are particularly associated with subversion-based moral framing. Overall, this work provides insights into LLM-based hate speech analysis and supports more accountable moderation of Persian-language social media."

## Directories

The repository is organized into the following directories:

* **LLM Evaluation**: This directory contains the Python scripts used to calculate metrics for evaluating LLMs on hate speech detection at each annotation hop.
* 
* **Human Validation**: This directory contains Python scripts used to calculate inter-annotator agreement and human–LLM alignment metrics as part of the human validation of LLM-generated annotations.

## Datasets

Since the dataset collected and used in this study contains potentially offensive or violent hate speech texts, we do not publicly release it. However, access can be provided upon reasonable request to the corresponding authors.
