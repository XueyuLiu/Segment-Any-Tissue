# AutoPromptMedSAM: One-Shot Reference Guided Training-Free Prompt Engineering for Universal Medical Image Segmentation
<br>**[Xueyu Liu](https://scholar.google.com.hk/citations?user=jeatLqIAAAAJ&hl=zh-CN), Guangze Shi, Rui Wang, Yexin Lai, Jianan Zhang, Xinyu Wang, Weixia Han, Ming Li, Xiaoshuang Zhou, Yongfei Wu*, \textit{Member, IEEE}, Chen Wang and Wen Zheng.<br>


## Overview
<p align="center">
<img width="800" alt="structure" src="img/Display.png">
</p>

##  Description
In the field of medical imaging, the cost of training is often higher due to the expertise and complexity of annotations, which typically limits AI-driven smart medical technologies to segmentation tasks in various scenarios. To tackle this challenge, we introduce AutoPromptMedSAM, a training-free framework that automates the segmentation of targets in any medical image using one-shot reference images. AutoPromptMedSAM harnesses the robust feature matching capabilities of pretrained foundation models (PFMs) to generate initial prompts, introduces novel prompting engineering for optimized methods, and employs a class-agnostic segmentation model for final results. Our method was validated on four public datasets ranging from macro to micro scales and two private datasets, all yielding encouraging results. Comparative experiments have shown that AutoPromptMedSAM surpasses the performance of recently proposed one-shot methods. In summary, AutoPromptMedSAM significantly enhances the segmentation capabilities of class-agnostic models in the medical data domain without the need for training, providing a unique automatic prompt generation method and facilitating clinical assistance for medical professionals.
## Setup 
- Cuda 12.0
- Python 3.9.18
- PyTorch 2.0.0

## TODO
- [ ] Release code


## Acknowledgement
Thanks [DINOv2](https://github.com/facebookresearch/dinov2), [SAM](https://github.com/facebookresearch/segment-anything), [Matcher](https://github.com/aim-uofa/Matcher), [GBMSeg](https://github.com/SnowRain510/GBMSeg). for serving as building blocks of GBMSeg.
