---
title: "Learning with Unreliability: Fast Few-shot Voxel Radiance Fields with Relative Geometric Consistency"
collection: publications
permalink: /publication/cvpr2024-1-Learning_with_Unreliability
excerpt: 'We propose a voxel-based optimization framework, ReVoRF, for few-shot radiance fields that strategically address the unreliability in pseudo novel view synthesis. Our method pivots on the insight that relative depth relationships within neighboring regions are more reliable than the absolute color values in disoccluded areas. Consequently, we devise a bilateral geometric consistency loss that carefully navigates the trade-off between color fidelity and geometric accuracy in the context of depth consistency for uncertain regions. Moreover, we present a reliability-guided learning strategy to discern and utilize the variable quality across synthesized views, complemented by a reliability-aware voxel smoothing algorithm that smoothens the transition between reliable and unreliable data patches. Our approach allows for a more nuanced use of all available data, promoting enhanced learning from regions previously considered unsuitable for high-quality reconstruction. Extensive experiments across diverse datasets reveal that our approach attains significant gains in efficiency and accuracy, delivering rendering speeds of 3 FPS, 7 mins to train a $360^\circ$ scene, and a 5\% improvement in PSNR over existing few-shot methods. Code is available at [https://github.com/HKCLynn/ReVoRF]{https://github.com/HKCLynn/ReVoRF}.'
date: 2024-06-18
venue: 'CVPR'
citation: 'Xu Y, Liu B, Tang H, et al. Learning with unreliability: fast few-shot voxel radiance fields with relative geometric consistency[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2024.'
---
We propose a voxel-based optimization framework, ReVoRF, for few-shot radiance fields that strategically addresses the unreliability in pseudo novel view synthesis. Our method pivots on the insight that relative depth relationships within neighboring regions are more reliable than the absolute color values in disoccluded areas. Consequently, we devise a bilateral geometric consistency loss that carefully navigates the trade-off between color fidelity and geometric accuracy in the context of depth consistency for uncertain regions. Moreover, we present a reliability-guided learning strategy to discern and utilize the variable quality across synthesized views, complemented by a reliability-aware voxel smoothing algorithm that smoothens the transition between reliable and unreliable data patches. Our approach allows for a more nuanced use of all available data, promoting enhanced learning from regions previously considered unsuitable for high-quality reconstruction. Extensive experiments across diverse datasets reveal that our approach attains significant gains in efficiency and accuracy, delivering rendering speeds of 3 FPS, 7 mins to train a $360^\circ$ scene, and a 5\% improvement in PSNR over existing few-shot methods. Code is available at [https://github.com/HKCLynn/ReVoRF]{https://github.com/HKCLynn/ReVoRF}.

[Download paper here](https://openaccess.thecvf.com/content/CVPR2024/papers/Xu_Learning_with_Unreliability_Fast_Few-shot_Voxel_Radiance_Fields_with_Relative_CVPR_2024_paper.pdf)

Recommended citation: 
```
@inproceedings{xu2024unreal,
  title={Learning with unreliability: fast few-shot voxel radiance fields with relative geometric consistency},
  author={Yingjie Xu, Bangzhen Liu, Hao Tang, Bailin Deng, Shengfeng He},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2024}
}
```
