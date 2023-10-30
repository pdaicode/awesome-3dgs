# Awesome 3D Gaussian Splatting Resources 
3D Gaussian Splatting (3DGS) opens a new window for using neural rendering for real applications. 
This is a curated list of papers and open source resources focused on 3D Gaussian Splatting, intended to keep pace with the anticipated surge of research in the coming months. 

**If you have any additions or suggestions, feel free to contribute. Everything is welcome.**

[Related Papers](./PointCloud.md)
## Most Recent Update & News:
[Complete List](./UpdateLog.md)
- 29 Oct: Start a separate page for [**Dynamic NeRF**](./dynamic)
- 27 Oct: [News] Luma AI releases ["Luma UE Plugin 0.4"](https://twitter.com/LumaLabsAI/status/1717979512313364626): now with splats! Crop, cull, relight, supporting UE 5.3!
- 24 Oct: Added related papers


## 3D Gaussian Splatting for Real-Time Radiance Field Rendering

**Authors**: [Bernhard Kerbl](https://scholar.google.at/citations?user=jeasMB0AAAAJ&hl=en), [Georgios Kopanas](https://scholar.google.com/citations?user=QLWLLHMAAAAJ), [Thomas Leimkühler](https://www-sop.inria.fr/members/Thomas-Sebastian.Leimkuhler/), [George Drettakis](https://scholar.google.fr/citations?user=LGo5J4IAAAAJ&hl=en), 

**Published**: SIGGRAPH 2023 (Best Paper)

<details open>
<summary><b>Abstract</b></summary>
Radiance Field methods have recently revolutionized novel-view synthesis of scenes captured with multiple photos or videos. However, achieving high visual quality still requires neural networks that are costly to train and render, while recent faster methods inevitably trade off speed for quality. For unbounded and complete scenes (rather than isolated objects) and 1080p resolution rendering, no current method can achieve real-time display rates. We introduce three key elements that allow us to achieve state-of-the-art visual quality while maintaining competitive training times and importantly allow high-quality real-time (≥ 30 fps) novel-view synthesis at 1080p resolution. First, starting from sparse points produced during camera calibration, we represent the scene with 3D Gaussians that preserve desirable properties of continuous volumetric radiance fields for scene optimization while avoiding unnecessary computation in empty space; Second, we perform interleaved optimization/density control of the 3D Gaussians, notably optimizing anisotropic covariance to achieve an accurate representation of the
scene; Third, we develop a fast visibility-aware rendering algorithm that supports anisotropic splatting and both accelerates training and allows real-time rendering. We demonstrate state-of-the-art visual quality and real-time rendering on several established datasets.
</details>
  
[📄 Paper (Low Resolution)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf) | [📄 Paper (High Resolution)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf) | [🌐 Project Page](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) | [💻 Code](https://github.com/graphdeco-inria/gaussian-splatting) | [🎥 Short Presentation](https://youtu.be/T_kXY43VZnk?si=DrkbDFxQAv5scQNT) | [🎥 Explanation Video](https://www.youtube.com/live/xgwvU7S0K-k?si=edF8NkYtsRbgTbKi) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pdaicode/awesome-3dgs/blob/master/colabs/gaussian_splatting_colab.ipynb)

## Dynamic 3D Gaussian Splatting:
- Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis, Jonathon Luiten, Georgios Kopanas, Bastian Leibe, Deva Ramanan. 
[[Paper](https://dynamic3dgaussians.github.io/paper.pdf) | [Project Page](https://dynamic3dgaussians.github.io/) | [Code](https://github.com/JonathonLuiten/Dynamic3DGaussians) | [Explanation Video](https://www.youtube.com/live/hDuy1TgD8I4?si=6oGN0IYnPRxOibpg)]

- Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction, Ziyi Yang, Xinyu Gao, Wen Zhou, Shaohui Jiao, Yuqing Zhang, Xiaogang Jin 
[📄 Paper](https://arxiv.org/pdf/2309.13101.pdf) | [🌐 Project Page](https://ingra14m.github.io/Deformable-Gaussians/) | [💻 Code (to be released)](https://github.com/ingra14m/Deformable-3D-Gaussians) 

- 4D Gaussian Splatting for Real-Time Dynamic Scene Rendering, Guanjun Wu, Taoran Yi, Jiemin Fang, Lingxi Xie, Xiaopeng Zhang, Wei Wei, Wenyu Liu, Tian Qi, Xinggang Wang
[📄 Paper](https://arxiv.org/pdf/2310.08528.pdf) | [🌐 Project Page](https://guanjunwu.github.io/4dgs/) | [💻 Code](https://github.com/hustvl/4DGaussians) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pdaicode/awesome-3dgs/blob/master/colabs/4DGaussians.ipynb)
  
- Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting
[📄 Paper](https://arxiv.org/pdf/2310.10642.pdf) 

- 4K4D: Real-Time 4D View Synthesis at 4K Resolution. [📄 Paper](https://drive.google.com/file/d/1Y-C6ASIB8ofvcZkyZ_Vp-a2TtbiPw1Yx/view?usp=sharing) | [🌐 Project Page](https://zju3dv.github.io/4k4d/)

## Generative 3D Gaussian Splatting:
Papers with shared code are ranked higher in this list

- Text-to-3D using Gaussian Splatting, Zilong Chen, Feng Wang, Huaping Liu, [📄 Paper](https://arxiv.org/pdf/2309.16585.pdf) | [🌐 Project Page](https://gsgen3d.github.io/) | [💻 Code](https://github.com/gsgen3d/gsgen) | [🎥 Short Presentation](https://streamable.com/28snte) | [🎥 Explanation Video](https://www.youtube.com/live/l956ye13F8M?si=ZkvFL_lsY5OQUB7e)


- DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation, Jiaxiang Tang, Jiawei Ren, Hang Zhou, Ziwei Liu, Gang Zeng, [📄 Paper](https://arxiv.org/pdf/2309.16653.pdf) | [🌐 Project Page](https://dreamgaussian.github.io/) | [💻 Code](https://github.com/dreamgaussian/dreamgaussian) | [🎥 Explanation Video](https://www.youtube.com/live/l956ye13F8M?si=ZkvFL_lsY5OQUB7e)

- GaussianDreamer: Fast Generation from Text to 3D Gaussian Splatting with Point Cloud Priors, Taoran Yi1, Jiemin Fang, Guanjun Wu1, Lingxi Xie, Xiaopeng Zhang, Wenyu Liu, Tian Qi, Xinggang Wang 
[📄 Paper](https://arxiv.org/pdf/2310.08529.pdf) | [🌐 Project Page](https://taoranyi.com/gaussiandreamer/) | [💻 Code](https://github.com/hustvl/GaussianDreamer) 

- Gsgen: Text-to-3D using Gaussian Splatting, 
[Paper](https://arxiv.org/abs/2309.16585) | [Project Page](https://gsgen3d.github.io/) | [Code](https://github.com/gsgen3d/gsgen) 

## Products
- [Luma AI](https://lumalabs.ai/interactive-scenes)
- [Polycam](https://poly.cam/gaussian-splatting)

## Open Source Implementations 

### Colab Resources
- [Camenduru](https://github.com/camenduru/gaussian-splatting-colab)
- [NeRFStudio](https://github.com/nerfstudio-project/nerfstudio/blob/main/colab/demo.ipynb)

### Reference 
- [Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting)

### Taichi Implementations
- [Taichi 3D Gaussian Splatting](https://github.com/wanmeihuali/taichi_3d_gaussian_splatting)

### Game Engines 
- [Unity Implementation](https://github.com/aras-p/UnityGaussianSplatting)
- [Blender](https://github.com/ReshotAI/gaussian-splatting-blender-addon)

### Training
- [fast: C++/CUDA](https://github.com/MrNeRF/gaussian-splatting-cuda)
- [nerfstudio: python/CUDA](https://github.com/nerfstudio-project/gsplat)

### Viewers 
- [WebGL Viewer 1](https://github.com/antimatter15/splat)
- [WebGL Viewer 2](https://github.com/cvlab-epfl/gaussian-splatting-web)
- [Three.js](https://github.com/mkkellogg/GaussianSplats3D)
- [A-Frame](https://github.com/quadjr/aframe-gaussian-splatting)

## Blog Posts

1. [Gaussian Splatting is pretty cool](https://aras-p.info/blog/2023/09/05/Gaussian-Splatting-is-pretty-cool/)
2. [Making Gaussian Splats smaller](https://aras-p.info/blog/2023/09/13/Making-Gaussian-Splats-smaller/)
3. [Making Gaussian Splats more smaller](https://aras-p.info/blog/2023/09/27/Making-Gaussian-Splats-more-smaller/)

## Tutorial Videos

1. [Getting Started with 3DGS](https://youtu.be/UXtuigy_wYc?si=j1vfORNspcocSH-b)
2. [How to view 3DGS Scenes in Unity](https://youtu.be/5_GaPYBHqOo?si=6u9j1HqXwF_5WSUL)

## Credits

Thanks to [MrNeRF](https://github.com/MrNeRF/awesome-3D-gaussian-splatting/tree/main)