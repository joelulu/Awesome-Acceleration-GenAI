# Awesome Acceleration GenAI  
A curated list of awesome papers on acceleration techniques for Generative AI.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-14-pink)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)

## <span id="head1"> *Contents* </span>

- Awesome Acceleration GenAI
  - [Cache Method](#Cache-Method)
  - [Token Merging](#Token-Merging)
  - [Distillation](#Distillation)
  - [Image Generation](#image-generation)
  - [Video Generation](#video-generation)
  - [optimal timestep](#optimal-timestep) 
  - [Others](#Others) 


### Cache-Method:


- **[1] Timestep Embedding Tells: It’s Time to Cache for Video Diffusion Model**, CVPR 2025.
  
  [[Paper](https://arxiv.org/pdf/2411.19108)]
  [[Code](https://liewfeng.github.io/TeaCache/)]


- **[2] Adaptive Caching for Faster Video Generation with Diffusion Transformers**, arxiv 2024.
  
  [[Paper](https://arxiv.org/pdf/2411.02397)]
  [[Code](https://adacache-dit.github.io/)]
  

- **[3] PAB: Real-time video generation with pyramid attention broadcast**, ICLR 2025.
  
  [[Paper](https://arxiv.org/pdf/2408.12588)]
  [[Code](https://github.com/NUS-HPC-AI-Lab/VideoSys)]
  

- **[4] SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers**, arxiv 2024.
  
  [[Paper](https://arxiv.org/pdf/2411.10510)]
  [[Code](https://github.com/Roblox/SmoothCache)]

- **[5] Δ-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers**, arxiv 2024.
  
  [[Paper](https://arxiv.org/pdf/2406.01125)]


- **[6] T-Gate: Faster Diffusion via Temporal Attention Decomposition**, TMLR 2025.
  
  [[Paper](https://arxiv.org/abs/2404.02747)]
  [[Code](https://github.com/HaozheLiu-ST/T-GATE)]
  

- **[7] Unveiling Redundancy in Diffusion Transformers (DiTs): A Systematic Study**, arxiv 2024.
  
  [[Paper](https://arxiv.org/abs/2411.13588)]
  [[Code](https://github.com/xdit-project/DiTCacheAnalysis)]
  

- **[8] Accelerating Diffusion Transformer via Error-Optimized Cache**, arxiv 2025.

  [[Paper](https://arxiv.org/pdf/2501.19243)]
  


- **[9] ToCa: Accelerating Diffusion Transformers with Token-wise Feature Caching**, ICLR 2025.
  
  [[Paper](https://arxiv.org/abs/2410.05317)]
  [[Code](https://github.com/Shenyi-Z/ToCa)]
  

- **[10] DuCa: Accelerating Diffusion Transformers with Dual Feature Caching**, arxiv 2024.
  
  [[Paper](https://arxiv.org/abs/2412.18911)]
  [[Code](https://github.com/Shenyi-Z/DuCa)]


- **[11] UniCP: A Unified Caching and Pruning Framework for Efficient Video Generation**, arxiv 2025.
  
  [[Paper](https://arxiv.org/pdf/2502.04393)]


- **[12] FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality**, arxiv 2024.
  
  [[Paper](https://arxiv.org/pdf/2410.19355)]
  [[Code](https://vchitect.github.io/FasterCache/)]

- **[13] Region-Adaptive Sampling for Diffusion Transformers**, arxiv 2025.
  
  [[Paper](https://arxiv.org/pdf/2502.10389)]
  [[Code](https://microsoft.github.io/RAS/)]

- **[14] CacheQuant: Comprehensively Accelerated Diffusion Models**, CVPR 2025.
  
  [[Paper](https://arxiv.org/pdf/2503.01323v1)]
  [[Code](https://github.com/BienLuky/CacheQuant)]

- **[15] Cache Me if You Can: Accelerating Diffusion Models through Block Caching**, CVPR 2024.
  
  [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wimbauer_Cache_Me_if_You_Can_Accelerating_Diffusion_Models_through_Block_CVPR_2024_paper.pdf)]
  [[Code](https://fwmb.github.io/blockcaching/#)]

- **[16] BlockDance: Reuse Structurally Similar Spatio-Temporal Features to Accelerate Diffusion Transformers**, arxiv 2025.
  
  [[Paper](https://arxiv.org/pdf/2503.15927)]

- **[17] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching**, NeurIPS 2024
  
  [[Paper](https://arxiv.org/pdf/2406.01733)]
  [[Code](https://github.com/horseee/learning-to-cache)]


  

### Token-Merging

- **[1] AsymRnR: Video Diffusion Transformers Acceleration with Asymmetric Reduction and Restoration**, arxiv 2024.
  
  [[Paper](https://arxiv.org/abs/2412.11706)]


### Others 
  
- **[1] Inference-Time Scaling for Diffusion Models beyond Scaling Denoising Steps**, CVPR 2025.
   
  [[Paper](https://arxiv.org/pdf/2501.09732)]

- **[2] Impossible Videosl**, arxiv 2025.
   
  [[Paper](https://arxiv.org/pdf/2503.14378))]
  [[Code](https://github.com/showlab/Impossible-Videos?tab=readme-ov-file)]

- **[3] DKDM: Data-Free Knowledge Distillation for Diffusion Models with Any
Architecture**, CVPR 2025.
   
  [[Paper](https://arxiv.org/pdf/2409.03550)]
  [[Code](https://github.com/qianlong0502/DKDM)]

- **[4] Distilling Diversity and Control in Diffusion Models**, arxiv 2025.
   
  [[Paper](https://arxiv.org/pdf/2503.10637)]
  [[Code](https://distillation.baulab.info/)]

### optimal-timestep

- **[1] Optimizing for the Shortest Path in Denoising Diffusion Model**, CVPR 2025.
   
  [[Paper](https://arxiv.org/pdf/2503.03265)]
  [[Code](https://github.com/UnicomAI/ShortDF)]

- **[2] Bellman Optimal StepSize Straightening Of Flow-Matching Models**, ICLR 2024.
   
  [[Paper](https://arxiv.org/pdf/2312.16414)]
  [[Code](https://github.com/nguyenngocbaocmt02/BOSS)]

- **[3] Optimal Stepsize for Diffusion Sampling**, arxiv 2025.
   
  [[Paper](https://arxiv.org/pdf/2503.21774v1)]
  [[Code](https://github.com/bebebe666/OptimalSteps)]

It is still being updated...



