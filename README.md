# CVPR 2024 论文和开源项目合集(Papers with Code)

CVPR 2024 decisions are now available on OpenReview！


> 注1：欢迎各位大佬提交issue，分享CVPR 2024论文和开源项目！
>
> - [CVPR 2023](CVPR2022-Papers-with-Code.md)

# 【CVPR 2024 论文开源目录】

- [CVPR 2024 论文和开源项目合集(Papers with Code)](#cvpr-2024-论文和开源项目合集papers-with-code)
- [【CVPR 2024 论文开源目录】](#cvpr-2024-论文开源目录)
- [3DGS(Gaussian Splatting)](#3dgsgaussian-splatting)
- [Avatars](#avatars)
- [Backbone](#backbone)
- [CLIP](#clip)
- [MAE](#mae)
- [Embodied AI](#embodied-ai)
- [GAN](#gan)
- [OCR](#ocr)
- [NeRF](#nerf)
- [DETR](#detr)
- [Prompt](#prompt)
- [多模态大语言模型(MLLM)](#多模态大语言模型mllm)
- [大语言模型(LLM)](#大语言模型llm)
- [NAS](#nas)
- [ReID(重识别)](#reid重识别)
- [扩散模型(Diffusion Models)](#扩散模型diffusion-models)
- [Vision Transformer](#vision-transformer)
- [视觉和语言(Vision-Language)](#视觉和语言vision-language)
- [目标检测(Object Detection)](#目标检测object-detection)
- [异常检测(Anomaly Detection)](#异常检测anomaly-detection)
- [目标跟踪(Object Tracking)](#目标跟踪object-tracking)
- [语义分割(Semantic Segmentation)](#语义分割semantic-segmentation)
- [医学图像(Medical Image)](#医学图像medical-image)
- [医学图像分割(Medical Image Segmentation)](#医学图像分割medical-image-segmentation)
- [自动驾驶(Autonomous Driving)](#自动驾驶autonomous-driving)
- [3D点云(3D-Point-Cloud)](#3d点云3d-point-cloud)
- [3D目标检测(3D Object Detection)](#3d目标检测3d-object-detection)
- [3D语义分割(3D Semantic Segmentation)](#3d语义分割3d-semantic-segmentation)
- [图像编辑(Image Editing)](#图像编辑image-editing)
- [视频编辑(Video Editing)](#视频编辑video-editing)
- [Low-level Vision](#low-level-vision)
- [超分辨率(Super-Resolution)](#超分辨率super-resolution)
- [去噪(Denoising)](#去噪denoising)
  - [图像去噪(Image Denoising)](#图像去噪image-denoising)
- [3D人体姿态估计(3D Human Pose Estimation)](#3d人体姿态估计3d-human-pose-estimation)
- [图像生成(Image Generation)](#图像生成image-generation)
- [视频生成(Video Generation)](#视频生成video-generation)
- [3D生成](#3d生成)
- [视频理解(Video Understanding)](#视频理解video-understanding)
- [知识蒸馏(Knowledge Distillation)](#知识蒸馏knowledge-distillation)
- [立体匹配(Stereo Matching)](#立体匹配stereo-matching)
- [场景图生成(Scene Graph Generation)](#场景图生成scene-graph-generation)
- [视频质量评价(Video Quality Assessment)](#视频质量评价video-quality-assessment)
- [数据集(Datasets)](#数据集datasets)
- [其他(Others)](#其他others)

<a name="3DGS"></a>

# 3DGS(Gaussian Splatting)

**Scaffold-GS: Structured 3D Gaussians for View-Adaptive Rendering**

- Homepage: https://city-super.github.io/scaffold-gs/
- Paper: https://arxiv.org/abs/2312.00109
- Code: https://github.com/city-super/Scaffold-GS

**GPS-Gaussian: Generalizable Pixel-wise 3D Gaussian Splatting for Real-time Human Novel View Synthesis**

- Homepage: https://shunyuanzheng.github.io/GPS-Gaussian 
- Paper: https://arxiv.org/abs/2312.02155
- Code: https://github.com/ShunyuanZheng/GPS-Gaussian

**GaussianAvatar: Towards Realistic Human Avatar Modeling from a Single Video via Animatable 3D Gaussians**

- Paper: https://arxiv.org/abs/2312.02134
- Code: https://github.com/huliangxiao/GaussianAvatar

**GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting**

- Paper: https://arxiv.org/abs/2311.14521
- Code: https://github.com/buaacyw/GaussianEditor 

**Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction**

- Homepage: https://ingra14m.github.io/Deformable-Gaussians/ 
- Paper: https://arxiv.org/abs/2309.13101
- Code: https://github.com/ingra14m/Deformable-3D-Gaussians

**SC-GS: Sparse-Controlled Gaussian Splatting for Editable Dynamic Scenes**

- Homepage: https://yihua7.github.io/SC-GS-web/ 
- Paper: https://arxiv.org/abs/2312.14937
- Code: https://github.com/yihua7/SC-GS

**Spacetime Gaussian Feature Splatting for Real-Time Dynamic View Synthesis**

- Homepage: https://oppo-us-research.github.io/SpacetimeGaussians-website/ 
- Paper: https://arxiv.org/abs/2312.16812
- Code: https://github.com/oppo-us-research/SpacetimeGaussians

**DNGaussian: Optimizing Sparse-View 3D Gaussian Radiance Fields with Global-Local Depth Normalization**

- Homepage: https://fictionarry.github.io/DNGaussian/
- Paper: https://arxiv.org/abs/2403.06912
- Code: https://github.com/Fictionarry/DNGaussian

**4D Gaussian Splatting for Real-Time Dynamic Scene Rendering**

- Paper: https://arxiv.org/abs/2310.08528
- Code: https://github.com/hustvl/4DGaussians

**GaussianDreamer: Fast Generation from Text to 3D Gaussians by Bridging 2D and 3D Diffusion Models**

- Paper: https://arxiv.org/abs/2310.08529
- Code: https://github.com/hustvl/GaussianDreamer

<a name="Avatars"></a>

# Avatars

**GaussianAvatar: Towards Realistic Human Avatar Modeling from a Single Video via Animatable 3D Gaussians**

- Paper: https://arxiv.org/abs/2312.02134
- Code: https://github.com/huliangxiao/GaussianAvatar

**Real-Time Simulated Avatar from Head-Mounted Sensors**

- Homepage: https://www.zhengyiluo.com/SimXR/
- Paper: https://arxiv.org/abs/2403.06862

<a name="Backbone"></a>

# Backbone

**RepViT: Revisiting Mobile CNN From ViT Perspective**

- Paper: https://arxiv.org/abs/2307.09283
- Code: https://github.com/THU-MIG/RepViT

**TransNeXt: Robust Foveal Visual Perception for Vision Transformers**

- Paper: https://arxiv.org/abs/2311.17132
- Code: https://github.com/DaiShiResearch/TransNeXt

<a name="CLIP"></a>

# CLIP

**Alpha-CLIP: A CLIP Model Focusing on Wherever You Want**

- Paper: https://arxiv.org/abs/2312.03818
- Code: https://github.com/SunzeY/AlphaCLIP

**FairCLIP: Harnessing Fairness in Vision-Language Learning**

- Paper: https://arxiv.org/abs/2403.19949
- Code: https://github.com/Harvard-Ophthalmology-AI-Lab/FairCLIP

<a name="MAE"></a>

# MAE

<a name="Embodied-AI"></a>

# Embodied AI

**EmbodiedScan: A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI**

- Homepage: https://tai-wang.github.io/embodiedscan/
- Paper: https://arxiv.org/abs/2312.16170
- Code: https://github.com/OpenRobotLab/EmbodiedScan

**MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception**

- Homepage: https://iranqin.github.io/MP5.github.io/ 
- Paper: https://arxiv.org/abs/2312.07472
- Code: https://github.com/IranQin/MP5

**LEMON: Learning 3D Human-Object Interaction Relation from 2D Images**

- Paper: https://arxiv.org/abs/2312.08963
- Code: https://github.com/yyvhang/lemon_3d 

<a name="GAN"></a>

# GAN

<a name="OCR"></a>

# OCR

**An Empirical Study of Scaling Law for OCR**

- Paper: https://arxiv.org/abs/2401.00028
- Code: https://github.com/large-ocr-model/large-ocr-model.github.io

**ODM: A Text-Image Further Alignment Pre-training Approach for Scene Text Detection and Spotting**

- Paper: https://arxiv.org/abs/2403.00303
- Code: https://github.com/PriNing/ODM 

<a name="NeRF"></a>

# NeRF

**PIE-NeRF🍕: Physics-based Interactive Elastodynamics with NeRF**

- Paper: https://arxiv.org/abs/2311.13099
- Code: https://github.com/FYTalon/pienerf/ 

<a name="DETR"></a>

# DETR

**DETRs Beat YOLOs on Real-time Object Detection**

- Paper: https://arxiv.org/abs/2304.08069
- Code: https://github.com/lyuwenyu/RT-DETR

**Salience DETR: Enhancing Detection Transformer with Hierarchical Salience Filtering Refinement**

- Paper: https://arxiv.org/abs/2403.16131
- Code: https://github.com/xiuqhou/Salience-DETR

<a name="Prompt"></a>

# Prompt

<a name="MLLM"></a>

# 多模态大语言模型(MLLM)

**mPLUG-Owl2: Revolutionizing Multi-modal Large Language Model with Modality Collaboration**

- Paper: https://arxiv.org/abs/2311.04257
- Code: https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2

**Link-Context Learning for Multimodal LLMs**

- Paper: https://arxiv.org/abs/2308.07891
- Code: https://github.com/isekai-portal/Link-Context-Learning/tree/main 

**OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation**

- Paper: https://arxiv.org/abs/2311.17911
- Code: https://github.com/shikiw/OPERA

**Making Large Multimodal Models Understand Arbitrary Visual Prompts**

- Homepage: https://vip-llava.github.io/ 
- Paper: https://arxiv.org/abs/2312.00784

**Pink: Unveiling the power of referential comprehension for multi-modal llms**

- Paper: https://arxiv.org/abs/2310.00582
- Code: https://github.com/SY-Xuan/Pink

**Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding**

- Paper: https://arxiv.org/abs/2311.08046
- Code: https://github.com/PKU-YuanGroup/Chat-UniVi

**OneLLM: One Framework to Align All Modalities with Language**

- Paper: https://arxiv.org/abs/2312.03700
- Code: https://github.com/csuhan/OneLLM

<a name="LLM"></a>

# 大语言模型(LLM)

**VTimeLLM: Empower LLM to Grasp Video Moments**

- Paper: https://arxiv.org/abs/2311.18445
- Code: https://github.com/huangb23/VTimeLLM 

<a name="NAS"></a>

# NAS

<a name="ReID"></a>

# ReID(重识别)

**Magic Tokens: Select Diverse Tokens for Multi-modal Object Re-Identification**

- Paper: https://arxiv.org/abs/2403.10254
- Code: https://github.com/924973292/EDITOR 

**Noisy-Correspondence Learning for Text-to-Image Person Re-identification**

- Paper: https://arxiv.org/abs/2308.09911

- Code : https://github.com/QinYang79/RDE 

<a name="Diffusion"></a>

# 扩散模型(Diffusion Models)

**InstanceDiffusion: Instance-level Control for Image Generation**

- Homepage: https://people.eecs.berkeley.edu/~xdwang/projects/InstDiff/

- Paper: https://arxiv.org/abs/2402.03290
- Code: https://github.com/frank-xwang/InstanceDiffusion

**Residual Denoising Diffusion Models**

- Paper: https://arxiv.org/abs/2308.13712
- Code: https://github.com/nachifur/RDDM

**DeepCache: Accelerating Diffusion Models for Free**

- Paper: https://arxiv.org/abs/2312.00858
- Code: https://github.com/horseee/DeepCache

**DEADiff: An Efficient Stylization Diffusion Model with Disentangled Representations**

- Homepage: https://tianhao-qi.github.io/DEADiff/ 

- Paper: https://arxiv.org/abs/2403.06951
- Code: https://github.com/Tianhao-Qi/DEADiff_code

**SVGDreamer: Text Guided SVG Generation with Diffusion Model**

- Paper: https://arxiv.org/abs/2312.16476
- Code: https://ximinng.github.io/SVGDreamer-project/

**InteractDiffusion: Interaction-Control for Text-to-Image Diffusion Model**

- Paper: https://arxiv.org/abs/2312.05849
- Code: https://github.com/jiuntian/interactdiffusion

**MMA-Diffusion: MultiModal Attack on Diffusion Models**

- Paper: https://arxiv.org/abs/2311.17516
- Code: https://github.com/yangyijune/MMA-Diffusion

**VMC: Video Motion Customization using Temporal Attention Adaption for Text-to-Video Diffusion Models**

- Homeoage: https://video-motion-customization.github.io/ 
- Paper: https://arxiv.org/abs/2312.00845
- Code: https://github.com/HyeonHo99/Video-Motion-Customization

<a name="Vision-Transformer"></a>

# Vision Transformer

**TransNeXt: Robust Foveal Visual Perception for Vision Transformers**

- Paper: https://arxiv.org/abs/2311.17132
- Code: https://github.com/DaiShiResearch/TransNeXt

**RepViT: Revisiting Mobile CNN From ViT Perspective**

- Paper: https://arxiv.org/abs/2307.09283
- Code: https://github.com/THU-MIG/RepViT

**A General and Efficient Training for Transformer via Token Expansion**

- Paper: https://arxiv.org/abs/2404.00672
- Code: https://github.com/Osilly/TokenExpansion 

<a name="VL"></a>

# 视觉和语言(Vision-Language)

**PromptKD: Unsupervised Prompt Distillation for Vision-Language Models**

- Paper: https://arxiv.org/abs/2403.02781
- Code: https://github.com/zhengli97/PromptKD

**FairCLIP: Harnessing Fairness in Vision-Language Learning**

- Paper: https://arxiv.org/abs/2403.19949
- Code: https://github.com/Harvard-Ophthalmology-AI-Lab/FairCLIP

<a name="Object-Detection"></a>

# 目标检测(Object Detection)

**DETRs Beat YOLOs on Real-time Object Detection**

- Paper: https://arxiv.org/abs/2304.08069
- Code: https://github.com/lyuwenyu/RT-DETR

**Boosting Object Detection with Zero-Shot Day-Night Domain Adaptation**

- Paper: https://arxiv.org/abs/2312.01220
- Code: https://github.com/ZPDu/Boosting-Object-Detection-with-Zero-Shot-Day-Night-Domain-Adaptation 

**YOLO-World: Real-Time Open-Vocabulary Object Detection**

- Paper: https://arxiv.org/abs/2401.17270
- Code: https://github.com/AILab-CVC/YOLO-World

**Salience DETR: Enhancing Detection Transformer with Hierarchical Salience Filtering Refinement**

- Paper: https://arxiv.org/abs/2403.16131
- Code: https://github.com/xiuqhou/Salience-DETR

<a name="Anomaly-Detection"></a>

# 异常检测(Anomaly Detection)

**Anomaly Heterogeneity Learning for Open-set Supervised Anomaly Detection**

- Paper: https://arxiv.org/abs/2310.12790
- Code: https://github.com/mala-lab/AHL

<a name="VT"></a>

# 目标跟踪(Object Tracking)

**Delving into the Trajectory Long-tail Distribution for Muti-object Tracking**

- Paper: https://arxiv.org/abs/2403.04700
- Code: https://github.com/chen-si-jia/Trajectory-Long-tail-Distribution-for-MOT 

<a name="Semantic-Segmentation"></a>

# 语义分割(Semantic Segmentation)

**Stronger, Fewer, & Superior: Harnessing Vision Foundation Models for Domain Generalized Semantic Segmentation**

- Paper: https://arxiv.org/abs/2312.04265
- Code: https://github.com/w1oves/Rein

**SED: A Simple Encoder-Decoder for Open-Vocabulary Semantic Segmentation**

- Paper: https://arxiv.org/abs/2311.15537
- Code: https://github.com/xb534/SED 

<a name="MI"></a>

# 医学图像(Medical Image)

**Feature Re-Embedding: Towards Foundation Model-Level Performance in Computational Pathology**

- Paper: https://arxiv.org/abs/2402.17228
- Code: https://github.com/DearCaat/RRT-MIL

**VoCo: A Simple-yet-Effective Volume Contrastive Learning Framework for 3D Medical Image Analysis**

- Paper: https://arxiv.org/abs/2402.17300
- Code: https://github.com/Luffy03/VoCo

**ChAda-ViT : Channel Adaptive Attention for Joint Representation Learning of Heterogeneous Microscopy Images**

- Paper: https://arxiv.org/abs/2311.15264
- Code: https://github.com/nicoboou/chada_vit 

<a name="MIS"></a>

# 医学图像分割(Medical Image Segmentation)



<a name="Autonomous-Driving"></a>

# 自动驾驶(Autonomous Driving)

**UniPAD: A Universal Pre-training Paradigm for Autonomous Driving**

- Paper: https://arxiv.org/abs/2310.08370
- Code: https://github.com/Nightmare-n/UniPAD

**Cam4DOcc: Benchmark for Camera-Only 4D Occupancy Forecasting in Autonomous Driving Applications**

- Paper: https://arxiv.org/abs/2311.17663
- Code: https://github.com/haomo-ai/Cam4DOcc

**Memory-based Adapters for Online 3D Scene Perception**

- Paper: https://arxiv.org/abs/2403.06974
- Code: https://github.com/xuxw98/Online3D

**Symphonize 3D Semantic Scene Completion with Contextual Instance Queries**

- Paper: https://arxiv.org/abs/2306.15670
- Code: https://github.com/hustvl/Symphonies

**A Real-world Large-scale Dataset for Roadside Cooperative Perception**

- Paper: https://arxiv.org/abs/2403.10145
- Code: https://github.com/AIR-THU/DAIR-RCooper

**Adaptive Fusion of Single-View and Multi-View Depth for Autonomous Driving**

- Paper: https://arxiv.org/abs/2403.07535
- Code: https://github.com/Junda24/AFNet

**Traffic Scene Parsing through the TSP6K Dataset**

- Paper: https://arxiv.org/pdf/2303.02835.pdf
- Code: https://github.com/PengtaoJiang/TSP6K 

<a name="3D-Point-Cloud"></a>

# 3D点云(3D-Point-Cloud)



<a name="3DOD"></a>

# 3D目标检测(3D Object Detection)

**PTT: Point-Trajectory Transformer for Efficient Temporal 3D Object Detection**

- Paper: https://arxiv.org/abs/2312.08371
- Code: https://github.com/kuanchihhuang/PTT

**UniMODE: Unified Monocular 3D Object Detection**

- Paper: https://arxiv.org/abs/2402.18573

<a name="3DOD"></a>

# 3D语义分割(3D Semantic Segmentation)

<a name="Image-Editing"></a>

# 图像编辑(Image Editing)

**Edit One for All: Interactive Batch Image Editing**

- Homepage: https://thaoshibe.github.io/edit-one-for-all 
- Paper: https://arxiv.org/abs/2401.10219
- Code: https://github.com/thaoshibe/edit-one-for-all

<a name="Video-Editing"></a>

# 视频编辑(Video Editing)

**MaskINT: Video Editing via Interpolative Non-autoregressive Masked Transformers**

- Homepage:  [https://maskint.github.io](https://maskint.github.io/) 

- Paper: https://arxiv.org/abs/2312.12468

<a name="LLV"></a>

# Low-level Vision

**Residual Denoising Diffusion Models**

- Paper: https://arxiv.org/abs/2308.13712
- Code: https://github.com/nachifur/RDDM

**Boosting Image Restoration via Priors from Pre-trained Models**

- Paper: https://arxiv.org/abs/2403.06793

<a name="SR"></a>

# 超分辨率(Super-Resolution)

**SeD: Semantic-Aware Discriminator for Image Super-Resolution**

- Paper: https://arxiv.org/abs/2402.19387
- Code: https://github.com/lbc12345/SeD

**APISR: Anime Production Inspired Real-World Anime Super-Resolution**

- Paper: https://arxiv.org/abs/2403.01598
- Code: https://github.com/Kiteretsu77/APISR 

<a name="Denoising"></a>

# 去噪(Denoising)

## 图像去噪(Image Denoising)

<a name="3D-Human-Pose-Estimation"></a>

# 3D人体姿态估计(3D Human Pose Estimation)

**Hourglass Tokenizer for Efficient Transformer-Based 3D Human Pose Estimation**

- Paper: https://arxiv.org/abs/2311.12028
- Code: https://github.com/NationalGAILab/HoT 

<a name="Image-Generation"></a>

# 图像生成(Image Generation)

**InstanceDiffusion: Instance-level Control for Image Generation**

- Homepage: https://people.eecs.berkeley.edu/~xdwang/projects/InstDiff/

- Paper: https://arxiv.org/abs/2402.03290
- Code: https://github.com/frank-xwang/InstanceDiffusion

**ECLIPSE: A Resource-Efficient Text-to-Image Prior for Image Generations**

- Homepage: https://eclipse-t2i.vercel.app/
- Paper: https://arxiv.org/abs/2312.04655

- Code: https://github.com/eclipse-t2i/eclipse-inference

**Instruct-Imagen: Image Generation with Multi-modal Instruction**

- Paper: https://arxiv.org/abs/2401.01952

**Residual Denoising Diffusion Models**

- Paper: https://arxiv.org/abs/2308.13712
- Code: https://github.com/nachifur/RDDM

**UniGS: Unified Representation for Image Generation and Segmentation**

- Paper: https://arxiv.org/abs/2312.01985

**Multi-Instance Generation Controller for Text-to-Image Synthesis**

- Paper: https://arxiv.org/abs/2402.05408
- Code: https://github.com/limuloo/migc

**SVGDreamer: Text Guided SVG Generation with Diffusion Model**

- Paper: https://arxiv.org/abs/2312.16476
- Code: https://ximinng.github.io/SVGDreamer-project/

**InteractDiffusion: Interaction-Control for Text-to-Image Diffusion Model**

- Paper: https://arxiv.org/abs/2312.05849
- Code: https://github.com/jiuntian/interactdiffusion

**Ranni: Taming Text-to-Image Diffusion for Accurate Prompt Following**

- Paper: https://arxiv.org/abs/2311.17002
- Code: https://github.com/ali-vilab/Ranni

<a name="Video-Generation"></a>

# 视频生成(Video Generation)

**Vlogger: Make Your Dream A Vlog**

- Paper: https://arxiv.org/abs/2401.09414
- Code: https://github.com/Vchitect/Vlogger

**VBench: Comprehensive Benchmark Suite for Video Generative Models**

- Homepage: https://vchitect.github.io/VBench-project/ 
- Paper: https://arxiv.org/abs/2311.17982
- Code: https://github.com/Vchitect/VBench

**VMC: Video Motion Customization using Temporal Attention Adaption for Text-to-Video Diffusion Models**

- Homeoage: https://video-motion-customization.github.io/ 
- Paper: https://arxiv.org/abs/2312.00845
- Code: https://github.com/HyeonHo99/Video-Motion-Customization

<a name="3D-Generation"></a>

# 3D生成

**CityDreamer: Compositional Generative Model of Unbounded 3D Cities**

- Homepage: https://haozhexie.com/project/city-dreamer/ 
- Paper: https://arxiv.org/abs/2309.00610
- Code: https://github.com/hzxie/city-dreamer

**LucidDreamer: Towards High-Fidelity Text-to-3D Generation via Interval Score Matching**

- Paper: https://arxiv.org/abs/2311.11284
- Code: https://github.com/EnVision-Research/LucidDreamer 

<a name="Video-Understanding"></a>

# 视频理解(Video Understanding)

**MVBench: A Comprehensive Multi-modal Video Understanding Benchmark**

- Paper: https://arxiv.org/abs/2311.17005
- Code: https://github.com/OpenGVLab/Ask-Anything/tree/main/video_chat2 

<a name="KD"></a>

# 知识蒸馏(Knowledge Distillation)

**Logit Standardization in Knowledge Distillation**

- Paper: https://arxiv.org/abs/2403.01427
- Code: https://github.com/sunshangquan/logit-standardization-KD

**Efficient Dataset Distillation via Minimax Diffusion**

- Paper: https://arxiv.org/abs/2311.15529
- Code: https://github.com/vimar-gu/MinimaxDiffusion

<a name="Stereo-Matching"></a>

# 立体匹配(Stereo Matching)

**Neural Markov Random Field for Stereo Matching**

- Paper: https://arxiv.org/abs/2403.11193
- Code: https://github.com/aeolusguan/NMRF 

<a name="SGG"></a>

# 场景图生成(Scene Graph Generation)

**HiKER-SGG: Hierarchical Knowledge Enhanced Robust Scene Graph Generation**

- Homepage: https://zhangce01.github.io/HiKER-SGG/ 
- Paper : https://arxiv.org/abs/2403.12033
- Code: https://github.com/zhangce01/HiKER-SGG

<a name="Video-Quality-Assessment"></a>

# 视频质量评价(Video Quality Assessment)

**KVQ: Kaleidoscope Video Quality Assessment for Short-form Videos**

- Homepage: https://lixinustc.github.io/projects/KVQ/ 

- Paper: https://arxiv.org/abs/2402.07220
- Code: https://github.com/lixinustc/KVQ-Challenge-CVPR-NTIRE2024

<a name="Datasets"></a>

# 数据集(Datasets)

**A Real-world Large-scale Dataset for Roadside Cooperative Perception**

- Paper: https://arxiv.org/abs/2403.10145
- Code: https://github.com/AIR-THU/DAIR-RCooper

**Traffic Scene Parsing through the TSP6K Dataset**

- Paper: https://arxiv.org/pdf/2303.02835.pdf
- Code: https://github.com/PengtaoJiang/TSP6K 

<a name="Others"></a>

# 其他(Others)

**Object Recognition as Next Token Prediction**

- Paper: https://arxiv.org/abs/2312.02142
- Code: https://github.com/kaiyuyue/nxtp

**ParameterNet: Parameters Are All You Need for Large-scale Visual Pretraining of Mobile Networks**

- Paper: https://arxiv.org/abs/2306.14525
- Code: https://parameternet.github.io/ 

**Seamless Human Motion Composition with Blended Positional Encodings**

- Paper: https://arxiv.org/abs/2402.15509
- Code: https://github.com/BarqueroGerman/FlowMDM 

**LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning**

- Homepage:  https://ll3da.github.io/ 

- Paper: https://arxiv.org/abs/2311.18651
- Code: https://github.com/Open3DA/LL3DA

 **CLOVA: A Closed-LOop Visual Assistant with Tool Usage and Update**

- Homepage: https://clova-tool.github.io/ 
- Paper: https://arxiv.org/abs/2312.10908

**MoMask: Generative Masked Modeling of 3D Human Motions**

- Paper: https://arxiv.org/abs/2312.00063
- Code: https://github.com/EricGuo5513/momask-codes

 **Amodal Ground Truth and Completion in the Wild**

- Homepage: https://www.robots.ox.ac.uk/~vgg/research/amodal/ 
- Paper: https://arxiv.org/abs/2312.17247
- Code: https://github.com/Championchess/Amodal-Completion-in-the-Wild

**Improved Visual Grounding through Self-Consistent Explanations**

- Paper: https://arxiv.org/abs/2312.04554
- Code: https://github.com/uvavision/SelfEQ

**ImageNet-D: Benchmarking Neural Network Robustness on Diffusion Synthetic Object**

- Homepage: https://chenshuang-zhang.github.io/imagenet_d/
- Paper: https://arxiv.org/abs/2403.18775
- Code: https://github.com/chenshuang-zhang/imagenet_d

**Learning from Synthetic Human Group Activities**

- Homepage: https://cjerry1243.github.io/M3Act/ 
- Paper  https://arxiv.org/abs/2306.16772
- Code: https://github.com/cjerry1243/M3Act

**A Cross-Subject Brain Decoding Framework**

- Homepage: https://littlepure2333.github.io/MindBridge/
- Paper: https://arxiv.org/abs/2404.07850
- Code: https://github.com/littlepure2333/MindBridge

**Multi-Task Dense Prediction via Mixture of Low-Rank Experts**

- Paper : https://arxiv.org/abs/2403.17749
- Code: https://github.com/YuqiYang213/MLoRE

**Contrastive Mean-Shift Learning for Generalized Category Discovery**

- Homepage: https://postech-cvlab.github.io/cms/ 
- Paper: https://arxiv.org/abs/2404.09451
- Code: https://github.com/sua-choi/CMS
  