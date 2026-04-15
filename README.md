# PascalVOC2007 Semantic Segmentation

This repository contains my mini project notebook for semantic segmentation on Pascal VOC 2007, together with all generated figures.

## Repository Contents

- `mini_project_2.ipynb`: Main notebook with data loading, training, evaluation, and visualization.
- `figures/`: Output figures organized by experiment:
  - `unet-r34/`
  - `sam2/`
  - `deeplabv3/`
  - `ablation_study_1/`
  - `ablation-study-2/`

## What Is Included in the Notebook

- Dataset setup and preprocessing for Pascal VOC segmentation.
- Baseline training and evaluation with U-Net (ResNet encoder).
- Additional model experiments with SAM 2.1 and DeepLabV3+.
- Ablation studies:
  - ResNet-18 vs ResNet-34 (U-Net encoder comparison)
  - DeepLabV3+ baseline vs augmented training
- Metrics and qualitative visualization (best/worst samples, mosaics, training curves).

## How To Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Sophie374/PascalVOC2007_Semantic_Segmentation.git
   cd PascalVOC2007_Semantic_Segmentation
   ```
2. Open `mini_project_2.ipynb` in Jupyter Notebook or VS Code.
3. Run cells in order to reproduce experiments (depending on your environment, some model sections may require GPU and additional packages).

## Notes

- Figures are uploaded as individual files (instead of zip) so they can be previewed directly on GitHub.
- Large intermediate artifacts are not required to browse results; the main outputs are in `figures/`.
