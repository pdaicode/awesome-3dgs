# Awesome 3D Gaussian Splatting Resources 
3D Gaussian Splatting (3DGS) opens a new window for using neural rendering for real applications. 
This repo is intended to provide a collection of papers that are related to 3DGS, but not necessarily use 3DGS.

In general, 3D Gaussian Splatting can be considered as a variant of NeRF. This repo will more focused on the practical side of NeRF, e.g. realtime, compatibility with Unity/Unreal, ease of editing, etc.

Other resources: [Dynamic NeRF](./dynamic.md)

**Verified**: Papers listed with ```[+]``` have been verfied by myself or colleagues. The code is runnable. Please leave an issue if you need help on setting up.

**If you have any additions or suggestions, feel free to contribute. Everything is welcome.**

## Most Recent Update & News:
[Complete List](./UpdateLog.md)
- 21 Dec: added **verified** section
- 26 Nov: added more details for cumstom data.
- 14 Nov: Start a separate page for [**NeRF**](./nerf)
- 29 Oct: Start a separate page for [**Dynamic NeRF**](./dynamic)
- 27 Oct: [News] Luma AI releases ["Luma UE Plugin 0.4"](https://twitter.com/LumaLabsAI/status/1717979512313364626): now with splats! Crop, cull, relight, supporting UE 5.3!

## 1. 3D Reconstruction

- **3D Gaussian Splatting for Real-Time Radiance Field Rendering**, 
[Bernhard Kerbl](https://scholar.google.at/citations?user=jeasMB0AAAAJ&hl=en), [Georgios Kopanas](https://scholar.google.com/citations?user=QLWLLHMAAAAJ), [Thomas Leimkühler](https://www-sop.inria.fr/members/Thomas-Sebastian.Leimkuhler/), [George Drettakis](https://scholar.google.fr/citations?user=LGo5J4IAAAAJ&hl=en), SIGGRAPH 2023 (Best Paper). 
[[📄 Paper (Low Resolution)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf) | [📄 Paper (High Resolution)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf) | [🌐 Project Page](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) | [💻 Code](https://github.com/graphdeco-inria/gaussian-splatting) | [🎥 Short Presentation](https://youtu.be/T_kXY43VZnk?si=DrkbDFxQAv5scQNT) | [🎥 Explanation Video](https://www.youtube.com/live/xgwvU7S0K-k?si=edF8NkYtsRbgTbKi) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pdaicode/awesome-3dgs/blob/master/colabs/gaussian_splatting_colab.ipynb)]

### 2023
Speed & Efficiency
- ```[+]``` LightGaussian: Unbounded 3D Gaussian Compression with 15x Reduction and 200+ FPS, 2023. [[Paper](https://arxiv.org/abs/2311.17245) | [Code](https://github.com/VITA-Group/LightGaussian)]
- ```[+]``` SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering, 2023. [[Paper](https://arxiv.org/abs/2311.12775) | [Code](https://github.com/Anttwo/SuGaR)]
- Compact 3D Gaussian Representation for Radiance Field, [[Paper](https://github.com/maincold2/Compact-3DGS/blob/main) | [Code](https://github.com/maincold2/Compact-3DGS)]
- Compact3D: Compressing Gaussian Splat Radiance Field Models with Vector Quantization, [[Paper](https://arxiv.org/abs/2311.18159) | [Code](https://github.com/UCDvision/compact3d)]

Quality
- Mip-Splatting: Alias-free 3D Gaussian Splatting, [[Paper](https://arxiv.org/abs/2311.16493) | [Code](https://github.com/autonomousvision/mip-splatting)]
- FisherRF: Active View Selection and Uncertainty Quantification for Radiance Fields using Fisher Information, [Paper](https://arxiv.org/abs/2311.17874)
- Multi-Scale 3D Gaussian Splatting for Anti-Aliased Rendering, [Paper](https://arxiv.org/abs/2311.17089)
- COLMAP-Free 3D Gaussian Splatting, [[Paper](https://arxiv.org/pdf/2312.07504) | [Project](https://oasisyang.github.io/colmap-free-3dgs/)]
- NeuSG: Neural Implicit Surface Reconstruction with 3D Gaussian Splatting Guidance, [Paper](https://arxiv.org/abs/2312.00846)
- Depth-Regularized Optimization for 3D Gaussian Splatting in Few-Shot Images, [Paper](https://arxiv.org/pdf/2311.13398)
- GS-SLAM: Dense Visual SLAM with 3D Gaussian Splatting, [Paper](https://arxiv.org/abs/2311.11700)
- SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM, [[Paper](https://arxiv.org/pdf/2312.02126.pdf) | [Code](https://github.com/spla-tam/SplaTAM)]

Reflection
- GaussianShader: 3D Gaussian Splatting with Shading Functions for Reflective Surfaces, [[Paper](https://arxiv.org/abs/2311.17977) | [Code](https://github.com/Asparagus15/GaussianShader)]
- Relightable 3D Gaussian: Real-time Point Cloud Relighting with BRDF Decomposition and Ray Tracing, [Paper](https://arxiv.org/abs/2311.16043)

## 2. Dynamic 3D Gaussian Splatting:
- ```[+]``` 4D Gaussian Splatting for Real-Time Dynamic Scene Rendering, [[Paper](https://arxiv.org/pdf/2310.08528.pdf) | [Project Page](https://guanjunwu.github.io/4dgs/) | [Code](https://github.com/hustvl/4DGaussians) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pdaicode/awesome-3dgs/blob/master/colabs/4DGaussians.ipynb)]
- Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis, [[Paper](https://dynamic3dgaussians.github.io/paper.pdf) | [Project Page](https://dynamic3dgaussians.github.io/) | [Code](https://github.com/JonathonLuiten/Dynamic3DGaussians) | [Explanation Video](https://www.youtube.com/live/hDuy1TgD8I4?si=6oGN0IYnPRxOibpg)]
- Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction, [[Paper](https://arxiv.org/pdf/2309.13101.pdf) | [Project Page](https://ingra14m.github.io/Deformable-Gaussians/) | [Code](https://github.com/ingra14m/Deformable-3D-Gaussians)]
- Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting, [Paper](https://arxiv.org/pdf/2310.10642.pdf) 
- 4K4D: Real-Time 4D View Synthesis at 4K Resolution. [[Paper](https://drive.google.com/file/d/1Y-C6ASIB8ofvcZkyZ_Vp-a2TtbiPw1Yx/view?usp=sharing) | [Project Page](https://zju3dv.github.io/4k4d/)]

## 3. Generative 3D Gaussian Splatting:
Papers with shared code are ranked higher in this list

- Text-to-3D using Gaussian Splatting, [[📄 Paper](https://arxiv.org/pdf/2309.16585.pdf) | [Project Page](https://gsgen3d.github.io/) | [Code](https://github.com/gsgen3d/gsgen) | [Explanation Video](https://www.youtube.com/live/l956ye13F8M?si=ZkvFL_lsY5OQUB7e)]
- DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation, [Paper](https://arxiv.org/pdf/2309.16653.pdf) | [Project Page](https://dreamgaussian.github.io/) | [Code](https://github.com/dreamgaussian/dreamgaussian) | [Explanation Video](https://www.youtube.com/live/l956ye13F8M?si=ZkvFL_lsY5OQUB7e)]
- GaussianDreamer: Fast Generation from Text to 3D Gaussian Splatting with Point Cloud Priors, [[Paper](https://arxiv.org/pdf/2310.08529.pdf) | [Project Page](https://taoranyi.com/gaussiandreamer/) | [Code](https://github.com/hustvl/GaussianDreamer)]
- Gsgen: Text-to-3D using Gaussian Splatting, [[Paper](https://arxiv.org/abs/2309.16585) | [Project Page](https://gsgen3d.github.io/) | [Code](https://github.com/gsgen3d/gsgen)]
- LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes, [[Paper](https://arxiv.org/abs/2311.13384) | [Project Page](https://luciddreamer-cvlab.github.io/)]
- PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics, [[Paper](https://arxiv.org/abs/2311.12198) | [Project Page](https://xpandora.github.io/PhysGaussian/)]
- HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting, [[Paper](https://arxiv.org/abs/2311.17061)]
- Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting, [[Paper](https://arxiv.org/abs/2312.04820) | [Code](https://github.com/yangxiaofeng/LODS)]

## Digital Avatar
- HeadGaS: Real-Time Animatable Head Avatars via 3D Gaussian Splatting, [Paper](https://arxiv.org/abs/2312.02902)
- HUGS: Human Gaussian Splats, [Paper](https://arxiv.org/abs/2311.17910)
- SplatArmor: Articulated Gaussian splatting for animatable humans from monocular RGB videos, [Paper](https://arxiv.org/pdf/2311.10812)
- Gaussian Shell Maps for Efficient 3D Human Generation, [Paper](https://arxiv.org/abs/2311.17857)
- Animatable Gaussians: Learning Pose-dependent Gaussian Maps for High-fidelity Human Avatar Modeling, [Paper](https://arxiv.org/pdf/2311.16096.pdf)


## 4. 3D Gaussian Viewers

### Colab
- [Camenduru](https://github.com/camenduru/gaussian-splatting-colab)
- [NeRFStudio](https://github.com/nerfstudio-project/nerfstudio/blob/main/colab/demo.ipynb)

### Training
- [fast: C++/CUDA](https://github.com/MrNeRF/gaussian-splatting-cuda)
- [nerfstudio: python/CUDA](https://github.com/nerfstudio-project/gsplat)
- [Taichi 3D Gaussian Splatting](https://github.com/wanmeihuali/taichi_3d_gaussian_splatting)

### Viewers 
- [Luma AI (WebGL)](https://lumalabs.ai/luma-web-library)
- [WebGL Viewer 1](https://github.com/antimatter15/splat)
- [WebGL Viewer 2](https://github.com/cvlab-epfl/gaussian-splatting-web)
- [Three.js](https://github.com/mkkellogg/GaussianSplats3D)
- [A-Frame](https://github.com/quadjr/aframe-gaussian-splatting)

### Game Engines 
- [Unity Implementation](https://github.com/aras-p/UnityGaussianSplatting)
- [Blender](https://github.com/ReshotAI/gaussian-splatting-blender-addon)

## 5. Documents
### Product
- [Luma AI](https://lumalabs.ai/interactive-scenes)
- [Polycam](https://poly.cam/gaussian-splatting)

### Blog Posts

1. [Gaussian Splatting is pretty cool](https://aras-p.info/blog/2023/09/05/Gaussian-Splatting-is-pretty-cool/)
2. [Making Gaussian Splats smaller](https://aras-p.info/blog/2023/09/13/Making-Gaussian-Splats-smaller/)
3. [Making Gaussian Splats more smaller](https://aras-p.info/blog/2023/09/27/Making-Gaussian-Splats-more-smaller/)

### Tutorial Videos

1. [Getting Started with 3DGS](https://youtu.be/UXtuigy_wYc?si=j1vfORNspcocSH-b)
2. [How to view 3DGS Scenes in Unity](https://youtu.be/5_GaPYBHqOo?si=6u9j1HqXwF_5WSUL)


## Reference 
- [Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting)
- [MrNeRF](https://github.com/MrNeRF/awesome-3D-gaussian-splatting/tree/main)
- https://dellaert.github.io/NeRF22/
- https://github.com/yangjiheng/nerf_and_beyond_docs