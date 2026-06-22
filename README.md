# TraitRegFormer

Official repository for:

**TraitRegFormer: An End-to-End Multi-Phenotype Instance Regression Framework for RGB-Based Lettuce Phenotyping**

## Overview

TraitRegFormer is an end-to-end scene-to-instance framework for simultaneous lettuce instance localization, segmentation, and multi-phenotype regression from RGB images. The framework directly estimates:

* Leaf Area (LA)
* Shoot Fresh Weight (SFW)
* Shoot Dry Weight (SDW)

for individual lettuce plants in multi-plant scenes without separate crop extraction and regression stages.

## Dataset

The TraitRegFormer benchmark contains:

* 1,403 RGB images
* 15,698 lettuce instances
* Instance-level bounding box and mask annotations
* Measured LA, SFW, and SDW labels for 660 lettuce plants
* Additional pseudo-labeled samples for training augmentation

## Code Availability

The manuscript is currently under review.

The complete source code, trained models, dataset, and reproduction scripts will be publicly released upon acceptance of the paper.

## Planned Release Contents

* TraitRegFormer implementation
* Training and inference scripts
* Pretrained model weights
* Benchmark dataset
* Evaluation code
* Documentation for reproduction

## Citation

If you find this work useful, please cite:

```bibtex
Citation information will be released after publication.
```

## Contact

Jie Deng

College of Water Resources and Intelligence Engineering
China Agricultural University

Email: [djcc@cau.edu.cn](mailto:djcc@cau.edu.cn)
