# Video Anomaly Detection with CLIP

This repository extends the [VadCLIP](https://arxiv.org/abs/2308.11681) framework for **video anomaly detection** by experimenting with model architectures and incorporating **VMamba**, a state space model designed for vision tasks, into CLIP.

## Overview

- **VadCLIP Notebook (`vad_clip_notebook.ipynb`)**  
  Main notebook for training and experimenting with modified VadCLIP.  
  - Integrates **VMamba** into the CLIP vision encoder.  
  - Supports **Comet logging** for experiment tracking.  
  - Includes architectural variations to evaluate their impact on anomaly detection.  

- **Feature Extraction Notebook (`vadclip_feature_extraction.ipynb`)**  
  Code for extracting CLIP-VMamba features from video dataset such as UCF Crime.  
  These features are later used for anomaly detection experiments.

## Key Contributions

- **VMamba-enhanced CLIP**: Replaces the standard CLIP encoder with a VMamba-based vision encoder to better capture spatiotemporal dependencies.  
- **Experiment Tracking**: Integrated with **Comet ML** for logging results, metrics, and hyperparameters.  
- **Feature Extraction Pipeline**: Provides reproducible extraction of video features from UCF Crime dataset clips.  
- **Research-Oriented Setup**: Designed for extension and ablation studies, making it suitable for further experimentation.

## Getting Started

Open the notebooks in Google Colab to get started
