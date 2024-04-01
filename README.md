# AP-MedSAM: One-Shot Reference Guided Training-Free Prompt Engineering for Universal Medical Image Segmentation
<br>[Xueyu Liu](https://scholar.google.com.hk/citations?user=jeatLqIAAAAJ&hl=zh-CN), Guangze Shi, Rui Wang, Yexin Lai, Jianan Zhang, Xinyu Wang, Weixia Han, Ming Li, Xiaoshuang Zhou, Yongfei Wu*, Chen Wang and Wen Zheng.<br>


## Overview
<p align="center">
<img width="800" alt="eg" src="img/Display.png">
</p>

##  Description
In the field of medical imaging, AI-driven technologies have historically faced limitations due to the high costs and complexities associated with training, especially in image segmentation. To address these challenges, we present AP-MedSAM, an innovative training-free framework designed to automate the segmentation of medical images with exceptional efficiency. AP-MedSAM leverages the robust feature matching capabilities of pretrained foundation models to generate initial prompt points. It then introduces a series of novel automatic prompt engineering techniques across feature and physical spaces to optimize the prompt scheme. Finally, AP-MedSAM utilizes a class-agnostic foundation segmentation model with the generated prompt scheme to achieve accurate segmentation results. Our method has been validated on four public datasets ranging from macro to micro scales and two private datasets. Results demonstrate superior performance compared to existing one-shot methods, requiring only one labeled reference image in a training-free manner. Ablation experiments further confirm the effectiveness of each component of the automatic prompt engineering. In summary, AP-MedSAM introduces a unique automatic prompt framework that enables robust, domain-independent, universal segmentation performance without the need for training. This significantly advances the automatic prompting of foundation segmentation models for medical images. AP-MedSAM introduces a brand-new paradigm for medical image segmentation, laying a solid foundation for the clinical application of intelligent medicine.
## Setup 
- Cuda 12.0
- Python 3.9.18
- PyTorch 2.0.0

## TODO
- [ ] Release code


## Acknowledgement
Thanks [DINOv2](https://github.com/facebookresearch/dinov2), [SAM](https://github.com/facebookresearch/segment-anything), [Matcher](https://github.com/aim-uofa/Matcher), [GBMSeg](https://github.com/SnowRain510/GBMSeg). for serving as building blocks of GBMSeg.
