# Dialectal-Gap-LLM-Evaluation

# Quantifying the Dialectal Gap: LLM Performance on Regional Arabic vs. MSA

This repository contains the code and dataset results for evaluating the zero-shot performance of Large Language Models (LLMs) on Modern Standard Arabic (MSA) compared to regional dialects (Egyptian). 

## Repository Contents
* `AdvNLP_Assignmnet_009_020_021.ipynb`: A Google Colab-ready Python notebook that loads the Qwen 2.5 (3B) model via 4-bit quantization and runs a zero-shot multiple-choice question-answering pipeline.
* `dialectal_gap_results.csv`: The final output data containing the model's predictions, the true answers, and the calculated accuracy across 120 test instances.

## Methodology Highlights
* **Task:** Zero-shot Multiple-Choice Question Answering (MCQ-QA)
* **Datasets:** `MBZUAI/ArabicMMLU` (MSA) and `QCRI/AraDiCE-ArabicMMLU-egy` (Egyptian Dialect)
* **Hardware Profile:** Optimized for consumer-grade GPUs (e.g., NVIDIA T4) using `bitsandbytes` NF4 quantization.

## Link to Full Paper
The full academic paper detailing the evaluation metrics and error analysis can be found [Insert Link to your PDF if hosted online, or remove this line].
