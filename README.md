# Lightweight-Mtl-AMUL-Framework-for-Bias-Mitigation-and-Task-Adaptation-in-OCR

## Overview
This repository provides resources for bias mitigation and task adaptation in Optical Character Recognition (OCR) using a lightweight Multi-task Learning (Mtl) AMUL framework.

### Contents

- **Results**: Uploaded in `pr result.zip`.
- **Trained Models**: Provided in `models.zip` (to be uploaded in the future).
- **Jupyter Notebooks:** The following folders contain training and evaluation notebooks for primary and secondary models using different techniques.

---

### Folder Structure

#### 1. [BMWA-based AMUL](./BMWA-based%20AMUL/)
Contains Jupyter notebooks analyzing the effects of the BMWA-based AMUL approach on different OCR Scripts (Assamese,Meetei-Mayek and olchiki)  and model architectures:

- **BMWA-based AMUL's effects on Assamese for model B-PN(DensNet-169).ipynb:**  
  Evaluates the effects of BMWA-based AMUL on Assamese script using B-PN(DensNet-169) with several FSL configaration.
- **BMWA-based AMUL's effects on Assamese for model B-PN(resnet-18).ipynb:**  
  Evaluates the effects of BMWA-based AMUL on Assamese script using B-PN(ResNet-169) with several FSL configaration.
- **BMWA-based AMUL's effects on Meetei-Mayek for model B-PN(DensNet-169).ipynb:**  
  Evaluates the effects of BMWA-based AMUL on Meetei-Mayek script using B-PN(DensNet-169) with several FSL configaration.
- **BMWA-based AMUL's effects on Meetei-Mayek for model B-PN(resnet-18).ipynb:**  
  Evaluates the effects of BMWA-based AMUL on Meetei-Mayek script with B-PN(ResNet-169) with several FSL configaration.
- **BMWA-based AMUL's effects on olchiki for model B-PN(DensNet-169).ipynb:**  
  Evaluates the effects of BMWA-based AMUL on Olchiki script using B-PN(DensNet-169) with several FSL configaration.
- **BMWA-based AMUL's effects on olchiki for model B-PN(resnet-18).ipynb:**  
  Evaluates the effects of BMWA-based AMUL on Olchiki script with B-PN(ResNet-169) with several FSL configaration.

#### 2. [Secondary model Generation (training)](./Secondary%20model%20Generation%20(training)/)
Notebooks for training secondary models for different scripts and model architectures:

- **Secondary model generaton for BMWA-based AMUL on Meetei-Mayek for model B-PN(densnet-169).ipynb**
- **Secondary model generaton for BMWA-based AMUL on Meetei-Mayek for model B-PN(resnet-18).ipynb**
- **Secondary model generaton for BMWA-based AMUL on Olchiki for model B-PN(densnet-169).ipynb**
- **Secondary model generaton for BMWA-based AMUL on Olchiki for model B-PN(resnet-18).ipynb**
- **Template of Secondary model generaton for BMWA-based AMUL on Assamese for all MtL models.ipynb**

These notebooks provide templates and specific training runs for secondary models across script-model pairs.

#### 3. [Template for Primary model Training](./Template%20for%20Primary%20model%20Training/)
Templates for primary model training on different network architectures:

- **Desnet169_training.ipynb:**  
  Template for training the primary MtL model using DensNet-169.
- **Resnet_18 training.ipynb:**  
  Template for training the primary MtL model using ResNet-18.

---

### Other Files

- **pr result.zip:**  
  Contains precomputed results and model outputs.

---

## Future Updates
Once the associated article is accepted, this repository will be updated with:
1. **Datasets:** Links to the relevant datasets (attached with the final version of paper).
2. **Proposed LW-CNN-PN Model Architecture Code:** All source code (including training and testing with BMWA-based AMUL) for the LW-CNN-PN's architecture.
3. **Framework and Workflow:**  
   - Scripts and notebooks for training and testing of LW-CNN-PN.
   - Step-by-step processes for reproducibility.

Stay tuned for updates!
