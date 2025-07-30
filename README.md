# 📌 G2CTN: Group Sampling and Global Location with Hierarchical Network for Point Cloud Analysis
![](https://github.com/zhiyuan0609/G2CTN/blob/main/figures/3.png)
G2CTN processes point clouds by first extracting group sampling features through a Group Sampling Strategy, then employs GSF modules for local geometry extraction and the GLF Block with PVA/GLA attention for multi-scale feature enhancement. This approach effectively expands the receptive field while capturing comprehensive geometric structure information.
# 👉 NOTE
This repo is implementation for G2CTN in pytorch.🔥
# 🌀 Introduction
G2CTN's GS-GL module innovatively combines convolutional local feature extraction with Transformer-based global modeling. Its Group Sampling Strategy (GSS) integrates FPS and VPS to capture multi-scale geometric features. The architecture employs GSF blocks for local geometry analysis and GLF blocks with PVA/GLA attention for global context, effectively addressing point cloud sparsity while preserving both detailed and structural information.
