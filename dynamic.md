# Dynamic NeRF

**Verified**: Papers listed with ```[+]``` have been verfied by myself or colleagues. The code is runnable. Please leave an issue if you need help on setting up.

# 1. Datasets
## Custom Data Preparation
- [Monocular Dynamic View Synthesis: A Reality Check](https://github.com/KAIR-BAIR/dycheck/blob/main/docs/RECORD3D_CAPTURE.md)
- [Process a video into a Nerfie dataset](https://colab.research.google.com/github/google/nerfies/blob/main/notebooks/Nerfies_Capture_Processing.ipynb)
- [Robust Dynamic Radiance Fields](https://github.com/facebookresearch/robust-dynrf)
Estimate monocular depth, Predict optical flows, Obtain motion mask.
- [Neural Scene Flow Fields](https://github.com/zhengqili/Neural-Scene-Flow-Fields/tree/main)
Instructions for custom data.

### Synthetic
- [D-Nerf Dataset](https://www.albertpumarola.com/research/D-NeRF/index.html)


### Real
- [Plenoptic Dataset](https://github.com/facebookresearch/Neural_3D_Video/releases/tag/v1.0)
- [Hypernerf Dataset](https://github.com/google/hypernerf/releases/tag/v0.1)
- [Nerfies Dataset](https://github.com/google/nerfies/releases/download/0.1/nerfies-vrig-dataset-v0.1.zip)
- [Dynamic NeRF](https://github.com/gaochen315/DynamicNeRF)
Balloon1, Balloon2, Jumping, Playground, Skating, Truck, Umbrella

# 2. Papers
## 2024
- Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis, Luiten et. al., International Conference on 3D Vision (3DV), 2024. [[Paper](https://dynamic3dgaussians.github.io/paper.pdf) | [Project Page](https://dynamic3dgaussians.github.io/) | [Code](https://github.com/JonathonLuiten/Dynamic3DGaussians) | [Explanation Video](https://www.youtube.com/live/hDuy1TgD8I4?si=6oGN0IYnPRxOibpg)]
- Sync-NeRF : Generalizing Dynamic NeRFs to Unsynchronized Videos, AAAI 2024. [[Paper](https://arxiv.org/abs/2310.13356), [Code](https://github.com/seoha-kim/Sync-NeRF)]
- Endo-4DGS: Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting, [[Paper](https://arxiv.org/abs/2401.16416) | [Code](https://github.com/lastbasket/Endo-4DGS)]
- DaReNeRF: Direction-aware Representation for Dynamic Scenes, CVPR 2024
- Sync-NeRF: Generalizing Dynamic NeRFs to Unsynchronized Videos, AAAI2024. [Code](https://github.com/seoha-kim/Sync-NeRF)
- SC-GS: Sparse-Controlled Gaussian Splatting for Editable Dynamic Scenes. [Code](https://github.com/yihua7/SC-GS)
- GaussianFlow: Splatting Gaussian Dynamics for 4D Content Creation
- Entity-NeRF: Detecting and Removing Moving Entities in Urban Scenes, CVPR 2024. [Project](https://otonari726.github.io/entitynerf/)
- Ced-NeRF: A Compact and Efficient Method for Dynamic Neural Radiance Fields, AAAI 2024. [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28138)
- 3D Geometry-aware Deformable Gaussian Splatting for Dynamic View Synthesis, CVPR 2024. [Project](https://npucvr.github.io/GaGS/)

- FPO++: efficient encoding and rendering of dynamic neural radiance fields by analyzing and enhancing Fourier PlenOctrees, The Visual Computer, 2024.
- Evdnerf: Reconstructing event data with dynamic neural radiance fields, WACV 2024. [Code](https://github.com/anish-bhattacharya/EvDNeRF)
- CTNeRF: Cross-time Transformer for dynamic neural radiance field from monocular video, Pattern Recognition, 2024. [Code](https://github.com/xingy038/ctnerf)
- DynamicSurf: Dynamic Neural RGB-D Surface Reconstruction with an Optimizable Feature Grid, International Conference on 3D Vision (3DV) 2024. [Code](https://github.com/Mirgahney/dynsurf)
- [+] Spacetime Gaussian Feature Splatting for Real-Time Dynamic View Synthesis, CVPR 2024. [Code](https://github.com/oppo-us-research/SpacetimeGaussians)

## 2023
- DynIBaR: Neural Dynamic Image-Based Rendering, CVPR, 2023 [[Project Page](https://dynibar.github.io/)]
- Tensor4D : Efficient Neural 4D Decomposition for High-fidelity Dynamic Reconstruction and Rendering, Shao et. al., CVPR, 2023. [[Paper](https://arxiv.org/abs/2211.11610) | [Code](https://github.com/DSaurus/Tensor4D)]
- HyperReel: High-Fidelity 6-DoF Video with Ray-Conditioned Sampling, CVPR 2023 (Highlight). [Code](https://github.com/facebookresearch/hyperreel)
- HexPlane: A Fast Representation for Dynamic Scenes, Cao et. al., CVPR, 2023. [[Paper](https://caoang327.github.io/HexPlane/HexPlane.pdf) | [Project Page](https://caoang327.github.io/HexPlane/) | [Code](https://github.com/Caoang327/HexPlane)]
- Robust Dynamic Radiance Fields, Liu et. al., CVPR, 2023. [[Code](https://github.com/facebookresearch/robust-dynrf)]
- V4D: Voxel for 4D Novel View Synthesis, Gan et. al., IEEE Transactions on Visualization and Computer Graphics, 2023. [[Paper](https://arxiv.org/abs/2205.14332) | [Code](https://github.com/GANWANSHUI/V4D)] (instructions for custom data)
- Dynamic Mesh-Aware Radiance Fields, ICCV, 2023. [[Project Page](https://mesh-aware-rf.github.io/) | [Code](https://github.com/YilingQiao/DMRF)]
- NeRFPlayer: A Streamable Dynamic Scene Representation with Decomposed Neural Radiance Fields, IEEE Transactions on Visualization and Computer Graphics, vol 29(5), 2023. [[Code](https://github.com/lsongx/nerfplayer-nerfstudio)]
- Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction, Yang et. al., ACM Transactions on Graphics, 2023. [[Paper](https://arxiv.org/pdf/2309.13101.pdf) | [Project Page](https://ingra14m.github.io/Deformable-Gaussians/) | [Code](https://github.com/ingra14m/Deformable-3D-Gaussians)]
- V4d: Voxel for 4d novel view synthesis, Gan et. al., IEEE Transactions on Visualization and Computer Graphics, 2023. [[Code](https://github.com/GANWANSHUI/V4D)]
- MixVoxels: Mixed Neural Voxels for Fast Multi-view Video Synthesis, ICCV2023 Oral. [Code](https://github.com/fengres/mixvoxels)
- HOSNeRF: Dynamic Human-Object-Scene Neural Radiance Fields from a Single Video, ICCV2023. [Code](https://github.com/TencentARC/HOSNeRF)
- DynPoint: Dynamic Neural Point For View Synthesis, NeurIPS 2023.

## 2022
- Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time, CVPR 2022 [[Project Page](https://aoliao12138.github.io/FPO/)]
- D2NeRF: Self-Supervised Decoupling of Dynamic and Static Objects from a Monocular Video, NeurIPS, 2022. [[Project Page](https://d2nerf.github.io/) | [Code](https://github.com/ChikaYan/d2nerf)]
- Monocular Dynamic View Synthesis: A Reality Check, Gao et. al., Neurips 2022. [[Project Page](https://hangg7.com/dycheck/)]
- TiNeuVox: Fast Dynamic Radiance Fields with Time-Aware Neural Voxels, Fang et. al., ACM SIGGRAPH Asia 2022. [[Project Page](https://jaminfong.cn/tineuvox/) | [Code](https://github.com/hustvl/TiNeuVox)]
- Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time, CVPR 2022. [Project](https://aoliao12138.github.io/FPO/)

## 2021
- Nerfies: Deformable Neural Radiance Fields, ICCV, 2021. [[Code](https://github.com/google/nerfies)] (instructions for **custom data**, this is the one everyone refering to)
- Dynamic View Synthesis from Dynamic Monocular Video, ICCV, 2021. [[Code](https://github.com/gaochen315/DynamicNeRF)]
- HyperNeRF: A Higher-Dimensional Representation for Topologically Varying Neural Radiance Fields, ACM Trans. Graph, 2021. [[Code](https://github.com/google/hyperNeRF) | [Project Page](https://hypernerf.github.io/) | [Colab](./colabs/HyperNerf.ipynb)] (instructions for custom data)
- BARF: Bundle-Adjusting Neural Radiance Fields, Lin et. al., ICCV 2021 (Oral). [[Code](https://github.com/chenhsuanlin/bundle-adjusting-NeRF)]

## 2020
- D-NeRF: Neural Radiance Fields for Dynamic Scenes, Pumarola et. al, CVPR 2020. [[Project Page](https://www.albertpumarola.com/research/D-NeRF/index.html) | [Code](https://github.com/albertpumarola/D-NeRF)]