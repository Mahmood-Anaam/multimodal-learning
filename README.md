# Multimodal Learning with Limited Labels and Missing Modalities

This repository contains the implementation and results of a university project that investigates **multimodal learning** using both images and text under two key constraints:

- **Limited labeled data** during training
- **Missing modalities** (image or text) during inference

We apply and evaluate several approaches:
- Pretrained CLIP encoders (image-only and text-only)
- Mid-level fusion of image and text embeddings
- Self-supervised learning with SimCLR
- A robust fusion model capable of handling missing modalities
- Zero-shot classification using CLIP prompts

All experiments are conducted on a curated subset of the COCO Captions dataset. Performance is reported using Top-1 and Top-5 classification accuracy.

## Contents

- 📂 `notebooks/`: Jupyter notebooks for model training, evaluation, and ablation studies  
- 📂 `docs/figures/`: Evaluation results (.csv), architecture diagrams, and training plots  
- 📄 `docs/multimodal-learning-report-latex.zip`: Full LaTeX source of the final technical report  

## Summary

This work demonstrates that pretrained vision-language models (like CLIP) perform well even with limited labels, and that modality dropout during training improves robustness when input modalities are missing. The results, analysis, and proposed architecture provide a strong baseline for future work in multimodal learning under constrained settings.



