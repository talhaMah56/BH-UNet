# BH-UNet

### Biogeographical Trends of Benthic Habitats in Guam from WorldView-2/3 Observations Using Advanced Deep Learning

> **Status:** 🚧 Code release in progress. Coming soon! 🚧

---

## Overview
This repository will contain the official PyTorch implementation of **BH-UNet** as described in the research paper:

**"Biogeographical Trends of Benthic Habitats in Guam from WorldView-2/3 Observations Using Advanced Deep Learning"**
*Authors: Talha Mahmood, Bingqing Liu, Charles Sabin, Megan K. La Peyre, Coy A. LeBlanc, Lyndsay L. Rankin, Kevin J. Buffington, Karen M. Thorne, Cara Lin, and Xu Yuan*

**Abstract:**
Benthic habitats such as seagrass meadows and coral reefs are vital components of shallow coastal ecosystems, yet they face increasing threats from both anthropogenic and climatic stressors. Traditional remote sensing and manual classification methods for mapping these habitats often struggle with fine-scale heterogeneity, label scarcity,  computational inefficiency, and thus insufficient performance. This study addresses these challenges by introducing BH-UNet, a lightweight deep learning framework applied to high-resolution WorldView-2/3 multispectral imagery of Guam’s Hagåtña Bay and Manell-Geus. The model incorporates channel-wise attention mechanisms and bilinear upsampling to enhance feature extraction while minimizing computational complexity. Trained on nine labeled images, the model utilizes patch-based preprocessing and augmentation to mitigate class imbalance and environmental variability. We conducted experiments and evaluated the performance of our proposed solution, which exhibits outstanding performance, achieving Intersection-over-Union (IoU) scores exceeding 0.98 and Dice coefficients above 0.99 across all habitat classes. These results demonstrate superior boundary preservation and broader adaptability compared to the original UNet design, which struggled with class imbalance. The efficiency of the framework enabled its application to time-series imagery, revealing fluctuations in seagrass extent from 2010 to 2024. Moreover, for the first time,it documented seagrass meadow declines associated with intensified marine heatwaves in 2014 and 2020, underscoring the framework's potential for scalable and operational coastal monitoring. This work advances AI-driven marine conservation by balancing computational efficiency with ecological precision, offering a pathway for adaptive management in data-limited coastal ecosystems.  


## 📅 Release Schedule
The full source code, including training scripts, data preprocessing pipelines, and pre-trained weights, will be made publicly available **upon acceptance/publication** of the paper.

We are currently cleaning the code and finalizing documentation to ensure it is easy to run and reproduce our results.

## 🔧 Implementation Details
- **Framework:** PyTorch
- **Hardware:** Implemented on a single NVIDIA RTX 4090 GPU.

## ✉️ Contact
For immediate inquiries regarding the paper or code, please contact:
Talha Mahmood - talha@udel.edu
