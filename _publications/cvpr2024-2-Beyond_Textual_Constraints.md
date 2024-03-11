---
title: "Beyond Textual Constraints: Learning Novel Diffusion Conditions with Fewer Examples"
collection: publications
permalink: /publication/cvpr2024-2-Beyond_Textual_Constraints
excerpt: In this paper, we delve into a novel aspect of learning novel diffusion conditions with datasets an order of magnitude smaller. The rationale behind our approach is the elimination of textual constraints during the few-shot learning process. To that end, we implement two optimization strategies. The first, prompt-free conditional learning, utilizes a prompt-free encoder derived from a pre-trained Stable Diffusion model. This strategy is designed to adapt new conditions to the diffusion process by minimizing the textual-visual correlation, thereby ensuring a more precise alignment between the generated content and the specified conditions. The second strategy entails condition-specific negative rectification, which addresses the inconsistencies typically brought about by Classifier-free guidance in few-shot training contexts. Our extensive experiments across a variety of condition modalities demonstrate the effectiveness and efficiency of our framework, yielding results comparable to those obtained with datasets a thousand times larger.
date: 2024-6-18
venue: 'CVPR'
citation: '
Yu Y, Liu B, Zheng C, et al. Beyond textual constraints: learning novel diffusion conditions with fewer examples[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2024.'
---
In this paper, we delve into a novel aspect of learning novel diffusion conditions with datasets an order of magnitude smaller. The rationale behind our approach is the elimination of textual constraints during the few-shot learning process. To that end, we implement two optimization strategies. The first, prompt-free conditional learning, utilizes a prompt-free encoder derived from a pre-trained Stable Diffusion model. This strategy is designed to adapt new conditions to the diffusion process by minimizing the textual-visual correlation, thereby ensuring a more precise alignment between the generated content and the specified conditions. The second strategy entails condition-specific negative rectification, which addresses the inconsistencies typically brought about by Classifier-free guidance in few-shot training contexts. Our extensive experiments across a variety of condition modalities demonstrate the effectiveness and efficiency of our framework, yielding results comparable to those obtained with datasets a thousand times larger.


[Download paper here](https://openaccess.thecvf.com/content/CVPR2023/papers/Zheng_Where_Is_My_Spot_Few-Shot_Image_Generation_via_Latent_Subspace_CVPR_2023_paper.pdf)

Recommended citation: 

```
@inproceedings{yu2024beyond,
  title={Beyond textual constraints: learning novel diffusion conditions with fewer examples},
  author={Yu, Yuyang and Liu, Bangzhen and Zheng, Chenxi and Xu, Xuemiao and Zhang, Huaidong and He, Shengfeng},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2024}
}
```
