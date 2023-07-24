
# Attentive Multimodal Fusion for Optical and Scene Flow
This paper presents an investigation into the estimation of optical and scene flow using RGBD information in scenarios where the RGB modality is affected by noise or captured in dark environments. Existing methods typically rely solely on RGB images or fuse the modalities at later stages, which can result in lower accuracy when the RGB information is unreliable. To address this issue, we propose a novel deep neural network approach named FusionRAFT, which enables early-stage information exchange between sensor modalities (RGB and depth). Our approach incorporates self- and cross-attention layers at different network levels to fuse these modalities and construct informative features that leverage the strengths of both modalities. Through comparative experiments, we demonstrate that our approach outperforms recent methods in terms of performance on the synthetic dataset Flyingthings3D, as well as the generalization on the real-world dataset KITTI. We illustrate that our approach exhibits improved robustness in the presence of noise and low-lighting conditions affecting the RGB images.
## Tested with
*
*
## Installation

## Download dataset

## Citing our work
@article{zhou2023FusionRAFT,
  title={{Attentive Multimodal Fusion for Optical and Scene Flow}},
  author={Y. Zhou and G. Mei and Y. Wang and F. Poiesi and Y. Wan},
  journal={IEEE ROBOTICS AND AUTOMATION LETTERS},
  year={2023}
}

## Acknowledgements
