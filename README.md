# 🚀 Awesome Acceleration GenAI  
A curated list of awesome papers on **acceleration techniques** for Generative AI.  

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-70+-pink)
![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)

---

## 📑 Contents
- [Cache Methods](#-cache-methods)
- [Token Merging & Sparse](#-token-merging--sparse)
- [Optimal Timestep](#-optimal-timestep)
- [Distillation](#-distillation)
- [Image Generation](#-image-generation)
- [Video Generation](#-video-generation)
- [Others](#-others)

---

## ⚡ Cache Methods

- **Timestep Embedding Tells: It’s Time to Cache for Video Diffusion Model**, *CVPR 2025* [[Paper](https://arxiv.org/pdf/2411.19108)] [[Code](https://liewfeng.github.io/TeaCache/)]  
- **Adaptive Caching for Faster Video Generation with Diffusion Transformers**, *arXiv 2024* [[Paper](https://arxiv.org/pdf/2411.02397)] [[Code](https://adacache-dit.github.io/)]  
- **PAB: Real-time video generation with pyramid attention broadcast**, *ICLR 2025* [[Paper](https://arxiv.org/pdf/2408.12588)] [[Code](https://github.com/NUS-HPC-AI-Lab/VideoSys)]  
- **SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers**, *arXiv 2024* [[Paper](https://arxiv.org/pdf/2411.10510)] [[Code](https://github.com/Roblox/SmoothCache)]  
- **Δ-DiT: Training-Free Acceleration for Diffusion Transformers**, *arXiv 2024* [[Paper](https://arxiv.org/pdf/2406.01125)]  
- **T-Gate: Faster Diffusion via Temporal Attention Decomposition**, *TMLR 2025* [[Paper](https://arxiv.org/abs/2404.02747)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)]  
- **Unveiling Redundancy in Diffusion Transformers (DiTs): A Systematic Study**, *arXiv 2024* [[Paper](https://arxiv.org/abs/2411.13588)] [[Code](https://github.com/xdit-project/DiTCacheAnalysis)]  
- **Accelerating Diffusion Transformer via Error-Optimized Cache**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2501.19243)]  
- **ToCa: Token-wise Feature Caching for Diffusion Transformers**, *ICLR 2025* [[Paper](https://arxiv.org/abs/2410.05317)] [[Code](https://github.com/Shenyi-Z/ToCa)]  
- **DuCa: Dual Feature Caching for Diffusion Transformers**, *arXiv 2024* [[Paper](https://arxiv.org/abs/2412.18911)] [[Code](https://github.com/Shenyi-Z/DuCa)]  
- **UniCP: Unified Caching and Pruning Framework for Efficient Video Generation**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2502.04393)]  
- **FasterCache: Training-Free Video Diffusion Acceleration with High Quality**, *arXiv 2024* [[Paper](https://arxiv.org/pdf/2410.19355)] [[Code](https://vchitect.github.io/FasterCache/)]  
- **Region-Adaptive Sampling for Diffusion Transformers**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2502.10389)] [[Code](https://microsoft.github.io/RAS/)]  
- **CacheQuant: Comprehensively Accelerated Diffusion Models**, *CVPR 2025* [[Paper](https://arxiv.org/pdf/2503.01323v1)] [[Code](https://github.com/BienLuky/CacheQuant)]  
- **Cache Me if You Can: Accelerating Diffusion Models through Block Caching**, *CVPR 2024* [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wimbauer_Cache_Me_if_You_Can_Accelerating_Diffusion_Models_through_Block_CVPR_2024_paper.pdf)] [[Code](https://fwmb.github.io/blockcaching/#)]  
- **BlockDance: Reuse Structurally Similar Spatio-Temporal Features**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2503.15927)]  
- **Learning-to-Cache: Layer Caching for Diffusion Transformers**, *NeurIPS 2024* [[Paper](https://arxiv.org/pdf/2406.01733)] [[Code](https://github.com/horseee/learning-to-cache)]  
- **TaylorSeers: Forecasting for Accelerating Diffusion Models**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2503.06923)] [[Code](https://github.com/Shenyi-Z/TaylorSeer)]  
- **Profiling-Based Feature Reuse for Video Diffusion Models**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2504.03140)] [[Code](https://github.com/GeekGuru123/ProfilingDiT/tree/main)]  
- **SRDiffusion: Sketching-Rendering Cooperation**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2505.19151)]  
- **AB-Cache: Adams-Bashforth Cached Feature Reuse**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2504.10540)]  
- **EEdit: Rethinking Spatial and Temporal Redundancy for Efficient Image Editing**, *ICCV 2025* [[Paper](https://arxiv.org/pdf/2503.10270)] [[Code](https://github.com/yuriYanZeXuan/EEdit?tab=readme-ov-file)]  
- **CacheDiT: Training-free Cache Acceleration Toolbox for Diffusion Transformers**, *arXiv 2025* [[Code](https://github.com/vipshop/cache-dit?tab=readme-ov-file)]  
- **Confidence-Gated Taylor Forecasting for Acceleration**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2508.02240)]  
- **HiCache: Hermite Polynomial-based Feature Caching**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2508.16984)]  
- **ERTACache: Error Rectification and Timesteps Adjustment**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2508.21091)]  
- **DiCache: Let Diffusion Model Determine Its Own Cache**, *arXiv 2025* [[Paper](https://www.arxiv.org/abs/2508.17356)]  
- **OmniCache: Global Trajectory-Oriented Cache Reuse**, *arXiv 2025* [[Paper](https://www.arxiv.org/pdf/2508.16212)]  
- **EasyCache: Runtime-Adaptive Caching for Video Diffusion**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2507.02860)] [[Code](https://github.com/H-EmbodVis/EasyCache)]  
- **Forecast then Calibrate: Caching as ODE for Diffusion Transformers**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2508.16211)]
- **SpecDiff: Accelerating Diffusion Model Inference with Self-Speculation**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2509.13848)]  
- **Evolutionary Caching to Accelerate Your Off-the-Shelf Diffusion Model**,  *arXiv 2025* [[Paper](https://arxiv.org/abs/2506.15682)] [[Code](https://github.com/AniAggarwal/ecad)]
- **SemCache:Adaptive Semantic-Aware Caching for Efficient Video Diffusion** *arXiv 2025* [[Paper](https://openreview.net/pdf/2e6b729aca381c1d81e8d40fd39db74b8360147c.pdf)] [[Code](https://openreview.net/forum?id=WyfmWX2ncn)]


---

## 🔀 Token Merging & Sparse

- **AsymRnR**: Video Diffusion Transformers Acceleration with Asymmetric Reduction and Restoration, *arXiv 2024* [[Paper](https://arxiv.org/abs/2412.11706)]  
- **Dynamic Token Carving (Jenga)**: Training-Free Efficient Video Generation, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2505.16864)] [[Code](https://github.com/dvlab-research/Jenga)]  
- **VORTA**: Efficient Video Diffusion via Routing Sparse Attention, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2505.18809)]  
- **Sparse VideoGen**: Accelerating with Spatial-Temporal Sparsity, *ICML 2025* [[Paper](https://arxiv.org/pdf/2502.01776)] [[Code](https://github.com/svg-project/Sparse-VideoGen)]  
- **Sparse VideoGen2**: Semantic-Aware Permutation, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2505.18875)] [[Code](https://github.com/svg-project/Sparse-VideoGen)]  

---

## ⏱ Optimal Timestep

- **Shortest Path in Denoising Diffusion**, *CVPR 2025* [[Paper](https://arxiv.org/pdf/2503.03265)] [[Code](https://github.com/UnicomAI/ShortDF)]  
- **BOSS: Bellman Optimal StepSize**, *ICLR 2024* [[Paper](https://arxiv.org/pdf/2312.16414)] [[Code](https://github.com/nguyenngocbaocmt02/BOSS)]  
- **Optimal Stepsize for Diffusion Sampling**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2503.21774v1)] [[Code](https://github.com/bebebe666/OptimalSteps)]  

---

## 🎯 Distillation

- **DKDM**: Data-Free Knowledge Distillation for Diffusion Models, *CVPR 2025* [[Paper](https://arxiv.org/pdf/2409.03550)] [[Code](https://github.com/qianlong0502/DKDM)]  
- **Distilling Diversity and Control in Diffusion Models**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2503.10637)] [[Code](https://distillation.baulab.info/)]  

---

## 🖼 Image Generation

- **EEdit**: Efficient Image Editing by Redundancy Reduction, *ICCV 2025* [[Paper](https://arxiv.org/pdf/2503.10270)] [[Code](https://github.com/yuriYanZeXuan/EEdit)]  

---

## 🎬 Video Generation

- **Impossible Videos**, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2503.14378)] [[Code](https://github.com/showlab/Impossible-Videos)]  
- **SRDiffusion**: Sketching-Rendering Cooperation, *arXiv 2025* [[Paper](https://arxiv.org/pdf/2505.19151)]  

---

## 📌 Others

- **Inference-Time Scaling for Diffusion Models beyond Scaling Denoising Steps**, *CVPR 2025* [[Paper](https://arxiv.org/pdf/2501.09732)]  

---

✨ *This list is continuously updated with the latest works.*  
