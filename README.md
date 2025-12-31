# Dual-Path Attentive Fusion with Vision–Language Guidance under Adversarial Perturbations

Official repository for the paper:

**Dual-Path Attentive Fusion with Vision–Language Guidance under Adversarial Perturbations**  
Anonymous ICME submission (under review)

> This repository currently provides the project overview, paper resources, and citation information.  
> Code, pretrained models, and evaluation scripts will be released after the review process.

---

## Overview

We study **robust and language-steerable infrared–visible (IR–VI) fusion** under adversarial perturbations and distribution shift.  
Our framework integrates three complementary components:

- **DPAC (Dual-Path Attentive Coupling)**: factorizes cross-modal attention into promotive and suppressive paths, enabling explicit inhibition of background-driven correlations.
- **VLAGM (Vision–Language Affine-and-Gated Modulation)**: converts frozen language embeddings into bounded **channel calibration (what)** and **spatial priors (where)** for controllable fusion.
- **HCCA (Hierarchical Cross-Modal Contrastive Alignment)**: aligns IR/VI representations across scales via patch-level contrastive learning with memory-efficient sampling.

---

## Planned Release

We plan to release:
- Training and evaluation code (PyTorch)
- Reproducible configs and scripts
- Pretrained checkpoints
- Text annotations / prompts used for experiments (where licensing permits)
- Robustness evaluation (PGD/I-FGSM) utilities

---

## Results (from the paper)

- Improved fusion quality on text-annotated benchmarks (MSRS / M3FD / RoadScene)
- Stronger prompt controllability (matched vs. mismatched prompts)
- Better cross-dataset generalization (FLIR / LLVIP / TNO) without fine-tuning
- Enhanced robustness under adversarial perturbations

(See the paper for quantitative tables and qualitative comparisons.)

---

## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{anonymous2026dpac,
  title     = {Dual-Path Attentive Fusion with Vision--Language Guidance under Adversarial Perturbations},
  author    = {Anonymous},
  booktitle = {IEEE International Conference on Multimedia \{ICME\}},
  year      = {2026},
  note      = {under review}
}
