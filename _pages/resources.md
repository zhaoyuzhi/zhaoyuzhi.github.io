---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
description: "Datasets, benchmarks, and selected open-source code from Yuzhi Zhao's research."
---

[Dataset](#dataset) · [Code](#code)

## Dataset

- **GraphDroid Benchmark** — ASE 2026<br>
  A benchmark for **mobile app GUI testing**, comprising 41 open-source and commercial Android apps across 21 categories. The reproduction package accompanies our work on history-aware exploration and intent fulfillment.<br>
  [Project Page](https://doi.org/10.5281/zenodo.21512256)

- **VP-Bench** — AAAI 2026<br>
  A benchmark for **visual prompting in multimodal large language models**. Its perception stage contains 34,267 images and 38,932 questions, while a second stage evaluates the effect of visual prompts on six downstream tasks, including GUI grounding and medical imaging.<br>
  [Project Page](https://github.com/Endlinc/VP-Bench)

- **KG-RAG UI Transition Graphs** — EMNLP 2025<br>
  A collection of **UI transition graphs for GUI agent research**, covering 30 Chinese apps on Android and HarmonyOS, plus 12 English apps on Android. The graphs support exploration and retrieval of app interaction paths for intent-driven navigation.<br>
  [Project Page](https://github.com/zhaoyuzhi/KG-RAG-GUI-Agent)

- **ICM-Instruct Validation Sets** — AAAI 2025<br>
  Released validation data for **rule-based, explainable image content moderation**. The collection includes 1,623 images across 35 categories and a 379-image subset for evaluating moderation explanation quality.<br>
  [Project Page](https://github.com/zhaoyuzhi/ICM-Assistant)

- **SpaceSGG** — WACV 2025<br>
  An instruction-tuning dataset for **scene graph generation and spatial reasoning**, combining object locations, relations, and depth information. It provides spatial descriptions, question-answer pairs, and multi-turn conversations, together with a 271-question spatial relation validation set.<br>
  [Project Page](https://github.com/Endlinc/LLaVA-SpaceSGG)

- **QR Dataset** — IEEE TIP 2024<br>
  A dataset for **joint denoising and deblurring of dual-exposure Quad-Bayer images**, pairing RAW inputs with RGB ground truth. It contains 701 synthetic training tuples, 30 validation tuples, and real captures from an IMX586 sensor.<br>
  [Project Page](https://github.com/zhaoyuzhi/QRNet)

- **D2-Dataset** — ECCV 2022<br>
  A dataset for **night image restoration from long- and short-exposure image pairs**, introduced with D2HNet. It provides 5,661 synthetic training tuples, validation data, and 28 real captured image pairs for studying joint denoising and deblurring.<br>
  [Project Page](https://github.com/zhaoyuzhi/D2HNet)

- **Family Face Database (FF-Database)** — IEEE TMM 2022<br>
  A dataset for **child face prediction from parent images**, introduced with ChildPredictor. It contains 7,488 parent faces and 8,558 child faces with labeled facial attributes. Access is available by request under the project's terms of use.<br>
  [Project Page](https://github.com/zhaoyuzhi/ChildPredictor)

- **Legacy Photo Dataset (LP Dataset)** — WACV 2021<br>
  A collection of approximately 25,000 legacy photographs with real noise and degradation, designed for **learning noise priors and restoring old photos**. Research access is available by request under the project's terms of use.<br>
  [Project Page](https://github.com/zhaoyuzhi/Legacy-Photo-Editing-with-Learned-Noise-Prior)

## Code

Selected implementations from my first-author papers and a widely used repository I maintain.

- **QRNet** — IEEE TIP 2024<br>
  Official PyTorch implementation for **reconstructing sharp, clean RGB images from dual-exposure Quad-Bayer inputs**, with training and evaluation code and pre-trained models.<br>
  [Project Page](https://github.com/zhaoyuzhi/QRNet)

- **SVCNet** — IEEE TIP 2023<br>
  Official PyTorch implementation for **scribble-guided video colorization**, propagating user-provided colors while maintaining temporal consistency across frames.<br>
  [Project Page](https://github.com/zhaoyuzhi/SVCNet)

- **HSGAN** — IEEE TNNLS 2023<br>
  Official implementation for **hyperspectral reconstruction from RGB images** using a generative adversarial network, with training and validation code.<br>
  [Project Page](https://github.com/zhaoyuzhi/HSGAN)

- **D2HNet** — ECCV 2022<br>
  Official PyTorch implementation for **joint denoising and deblurring of night photos**, combining long- and short-exposure images through a hierarchical restoration network.<br>
  [Project Page](https://github.com/zhaoyuzhi/D2HNet)

- **ChildPredictor** — IEEE TMM 2022<br>
  Official implementation for **child face synthesis conditioned on parent images**, using disentangled representations of facial attributes. The repository provides inference code, pre-trained models, and a data collection pipeline.<br>
  [Project Page](https://github.com/zhaoyuzhi/ChildPredictor)

- **VCGAN** — IEEE TMM 2022<br>
  Official implementation of a hybrid generative adversarial network for **automatic image and video colorization**, incorporating temporal information to improve consistency in videos.<br>
  [Project Page](https://github.com/zhaoyuzhi/VCGAN)

- **HRNet** — CVPR NTIRE Workshop 2020<br>
  Official implementation of a hierarchical regression network for **spectral reconstruction from RGB images**. The method won first place in the real-world track of the NTIRE 2020 Spectral Reconstruction Challenge.<br>
  [Project Page](https://github.com/zhaoyuzhi/Hierarchical-Regression-Network-for-Spectral-Reconstruction-from-RGB-Images)

- **SCGAN** — IEEE TCSVT 2020<br>
  Official implementation for **saliency-guided image colorization**, using semantic information and saliency maps to generate plausible colors. Training and evaluation code are provided.<br>
  [Project Page](https://github.com/zhaoyuzhi/Semantic-Colorization-GAN)

- **deepfillv2** — PyTorch reimplementation<br>
  My PyTorch reimplementation of **gated-convolution image inpainting**, inspired by the ICCV 2019 DeepFill v2 paper by Yu et al. It focuses on gated convolutions in a coarse-to-fine framework and provides training and testing code.<br>
  [Project Page](https://github.com/zhaoyuzhi/deepfillv2)
