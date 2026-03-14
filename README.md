# Explainable Prompt-Driven Oral Cancer Lesion Segmentation using SAM

## Overview

This project focuses on automated segmentation of oral cancer lesions from medical images using deep learning models and the Segment Anything Model (SAM). The study compares multiple deep learning baseline architectures and evaluates the impact of prompt-driven segmentation with explainability techniques.

The goal is to improve segmentation accuracy and provide interpretable results that can support early diagnosis and clinical decision-making.

## Models Used

The following deep learning baseline models were implemented and evaluated:

* UNet
* UNet++
* Attention UNet
* Swin-UNet

These models are further integrated with the Segment Anything Model (SAM) to perform prompt-driven segmentation.

## Key Features

* Deep learning based medical image segmentation
* Prompt-driven segmentation using Segment Anything Model (SAM)
* Prompt Sensitivity Analysis (PSA)
* Explainable AI (XAI) for model interpretation
* Comparative analysis of multiple segmentation architectures

## Prompt Types Used

Prompt Sensitivity Analysis evaluates the effect of different prompts on segmentation performance:

* Point Prompt
* Box Prompt
* Mask Prompt

## Evaluation Metrics

The models are evaluated using standard segmentation metrics:

* Intersection over Union (IoU)
* Dice Score
* Precision
* Recall
* ROC Curve
* Precision-Recall Curve

## Methodology

1. Data preprocessing and augmentation
2. Training baseline segmentation models
3. Applying Segment Anything Model for prompt-driven segmentation
4. Performing Prompt Sensitivity Analysis
5. Evaluating segmentation performance using multiple metrics
6. Applying Explainable AI techniques to interpret model predictions

## Project Structure

notebooks/

01_unet.ipynb

02_unetplusplus.ipynb

03_attention_unet.ipynb

04_swin_unet.ipynb

05_sam_segmentation.ipynb

06_prompt_sensitivity_analysis.ipynb

07_xai_analysis.ipynb

images/

methodology.png

architecture.png

README.md

## Technologies Used

* Python
* PyTorch
* Segment Anything Model (SAM)
* OpenCV
* NumPy
* Matplotlib
* Google Colab

## Results

Experimental results including segmentation outputs, IoU scores, Dice scores, ROC curves, and precision-recall curves are generated directly within the Google Colab notebooks during execution.

## Future Scope

* Deployment on Edge AI devices for real-time medical analysis
* Integration with clinical diagnostic systems
* Development of automated screening tools for early oral cancer detection

## Author

Laxmipriya Rout
