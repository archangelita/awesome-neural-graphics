# Awesome Neural Graphics

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)
![visitors](https://visitor-badge.glitch.me/badge?style=flat-square&page_id=sptemporal/awesome-neural-graphics)

This repository is a collection of recent advancements in neural graphics. 

Please feel free to open a [pull request](https://github.com/sptemporal/awesome-graphics-research/pulls) if you think I'm missing something or if you have any recommendations (for papers, SDKs, implementations, or other kind of educative resources). 

# Introduction to Neural Graphics

Neural graphics or in other words AI graphics is a emerging new field of AI and graphics to create an accelerated graphics pipeline that learns from data. Integrating AI techniques to graphics pipelines improves results, helps automate design choices, and offers new kind of unimagined potentials for creators and artists. Under the guidance of SOTA research and engineering, neural graphics is expected to be redefine how virtual worlds are created, simulated, delivered/distributed and experienced by users. New research and a broad suite of tools that apply the power of neural graphics to the creation and animation of 3D objects and worlds. These SDKs and research contribute to each stage of the content creation pipeline, including 3D content creation, physics and animation, experience, and more.

## Table of Content

- [Papers](#papers)
- [SDKs](#sdks)

## Papers

### 2022

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis (Revisited)](https://arxiv.org/abs/2003.08934)
- [Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://arxiv.org/abs/2201.05989)
- [Extracting Triangular 3D Models, Materials, and Lighting From Images](https://nvlabs.github.io/nvdiffrec/assets/paper.pdf)
- [Image Features Influence Reaction Time: A Learned Probabilistic Perceptual Model for Saccade Latency](https://arxiv.org/abs/2205.02437)
- [Implicit Neural Representation for Physics-driven Actuated Soft Bodies](https://cgl.ethz.ch/publications/papers/paperYan22a.php)
- [Variable Bitrate Neural Fields](https://research.nvidia.com/vbnf)
- [Neural Fields in Visual Computing and Beyond](https://neuralfields.cs.brown.edu/)
- [NeAT: Neural Adaptive Tomography](https://vccimaging.org/Publications/Ruckert2022NeAT/Ruckert2022NeAT.pdf)
- [Neural Layered BRDFs](https://wangningbei.github.io/2022/NLBRDF.html)
- [FoV-NeRF: Foveated Neural Radiance Fields for Virtual Reality (Revisited)](https://arxiv.org/abs/2103.16365)
- [Amodal 3D Understanding and Free-Viewpoint Rendering for the Closed Scene Composed of Pre-Captured Objects](https://zju3dv.github.io/nr_in_a_room/)
- [A Compact Representation of Measured BRDFs Using Neural Processes](https://shuangz.com/projects2/npbrdf-tog22/npbrdf-tog22.pdf)
- [GANimator: Neural Motion Synthesis from a Single Sequence](https://peizhuoli.github.io/ganimator/index.html)
- [Neural Dual Contouring](https://arxiv.org/pdf/2202.01999.pdf)
- [NeROIC: Neural Object Capture and Rendering from Online Image Collections](https://formyfamily.github.io/NeROIC/)
- [Advances in Neural Rendering](https://arxiv.org/abs/2111.05849)
- [Another awesome collection of resources on neural rendering by weihaox](https://github.com/weihaox/awesome-neural-rendering)

## SDKs

- [Kaolin Wisp](https://github.com/NVIDIAGameWorks/kaolin-wisp) – an addition to Kaolin, a PyTorch library enabling faster 3D deep learning research by reducing the time needed to test and implement new techniques from weeks to days. Kaolin Wisp is a research-oriented library for neural fields, establishing a common suite of tools and a framework to accelerate new research in neural fields.
- [Instant Neural Graphics Primitives](https://nvlabs.github.io/instant-ngp/) - a new approach to capturing the shape of real-world objects, and the inspiration behind NVIDIA Instant NeRF, an inverse rendering model that turns a collection of still images into a digital 3D scene. This technique and associated GitHub code accelerate the process by up to 1,000x.
- [3D MoMa](https://nvlabs.github.io/nvdiffrec/) – a new inverse rendering pipeline that allows users to quickly import a 2D object into a graphics engine to create a 3D object that can be modified with realistic materials, lighting and physics.
- [GauGAN360](http://imaginaire.cc/gaugan360/) - the next evolution of NVIDIA GauGAN, an AI model that turns rough doodles into photorealistic masterpieces. GauGAN360 generates 8K, 360-degree panoramas that can be ported into Omniverse scenes.
- [NVIDIA Omniverse ACE](https://developer.nvidia.com/nvidia-omniverse-platform/ace) - a collection of cloud-based AI models and services for developers to easily build, customize and deploy engaging and interactive avatars.
- [NeuralVDB](https://developer.nvidia.com/neuralvdb) – a groundbreaking improvement on OpenVDB, the current industry standard for volumetric data storage. Using machine learning, NeuralVDB introduces compact neural representations, dramatically reducing memory footprint to allow for higher-resolution 3D data. Large-scale volume representation with AI-enabled data compression technology.
- [Omniverse Audio2Face](https://www.nvidia.com/en-us/omniverse/apps/audio2face/) – an AI technology that generates expressive facial animation from a single audio source. It’s useful for interactive real-time applications and as a traditional facial animation authoring tool.
- [ASE: Animation Skills Embedding](https://nv-tlabs.github.io/ASE/) – an approach enabling physically simulated characters to act in a more responsive and life-like manner in unfamiliar situations. It uses deep learning to teach characters how to respond to new tasks and actions.
- [TAO Toolkit](https://developer.nvidia.com/tao-toolkit) – a framework to enable users to create an accurate, high-performance pose estimation model, which can evaluate what a person might be doing in a scene using computer vision much more quickly than current methods.
- [Image Features Eye Tracking](https://research.nvidia.com/publication/2022-08_image-features-influence-reaction-time-learned-probabilistic-perceptual-model) – a research model linking the quality of pixel rendering to a user’s reaction time. By predicting the best combination of rendering quality, display properties and viewing conditions for the least latency, It will allow for better performance in fast-paced, interactive computer graphics applications such as competitive gaming.
- [Holographic Glasses for Virtual Reality](https://research.nvidia.com/publication/2022-08_holographic-glasses-virtual-reality) – a collaboration with Stanford University on a new VR glasses design that delivers full-color 3D holographic images in a groundbreaking 2.5-mm-thick optical stack.
