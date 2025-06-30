# Enabling Visual Scene Recovery from Wi-Fi CSI for Occlusion-Free Surveillance

This is the official implementation of our paper "Enabling Visual Scene Recovery from Wi-Fi CSI for Occlusion-Free Surveillance."

In this work, we propose CSI-Inpainter, the first framework to leverage Wi-Fi channel-state information (CSI) for removing large occlusions in surveillance images. It also pioneers multi-environment validation (office, factory) and a systematic study of how sensor placement, multi-sensor fusion, and CSI temporal/frequency resolution shape reconstruction quality.



## About CSI-Inpainter

CSI-Inpainter uses CSI time sequences to recover visual scenes, offering superior performance in large-size occlusion removal without reliance on conventional cameras. This method has been validated in varied real-world environments, including office and industrial settings, showcasing its robust capacity for discerning and reconstructing occluded segments.


## This repository contains:

- **Office Dataset**: A comprehensive dataset collected in office environments to test and validate the CSI-Inpainter (https://zenodo.org/records/10782964?preview=1).
- **Factory Dataset**: A specialized dataset from industrial settings to further challenge and evaluate our approach (will be released soon).
- **CSI-Guided Imaging and Obstacle Removal Code**: The complete codebase for implementing CSI-Inpainter, including data preprocessing, model training, and evaluation scripts.


## Usage

Please download the datasets and refer to the Jupyter directory for notebooks demonstrating how to use CSI-Inpainter for various applications. These examples provide a step-by-step guide to processing CSI data, training the model, and visualizing the results.


## News
- **[2025-06-01]** Our paper is formally published on [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10840275).
- **[2025-01-01]** Our paper is accepted by IEEE IoT Journal and now available on [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10840275). Congratulations!
- **[2024-03-06]** Our paper "CSI-Inpainter: Enabling Visual Scene Recovery from CSI Time Sequences for Occlusion Removal" is now available on [arXiv](https://arxiv.org/abs/2305.05385v3).
- Stay tuned for upcoming dataset releases and code updates.


## Acknowledgments
This work was supported by Nishio Lab (https://nishio-laboratory.github.io/), Institute of Science Tokyo. We thank all contributors and collaborators for their invaluable efforts in advancing this project.

