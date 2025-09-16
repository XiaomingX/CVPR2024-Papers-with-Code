# CVPR 2024 论文与开源项目合集（Papers with Code）

> 注1：欢迎各位大佬提交issue，分享CVPR 2024的论文和开源项目！
>
> - [CVPR 2023 合集](CVPR2022-Papers-with-Code.md)

# 【CVPR 2024 论文开源目录】

- [CVPR 2024 论文与开源项目合集（Papers with Code）](#cvpr-2024-论文与开源项目合集papers-with-code)
- [【CVPR 2024 论文开源目录】](#cvpr-2024-论文开源目录)
- [3DGS（高斯溅射，Gaussian Splatting）](#3dgs高斯溅射gaussian-splatting)
- [数字人化身（Avatars）](#数字人化身avatars)
- [骨干网络（Backbone）](#骨干网络backbone)
- [CLIP（跨模态匹配模型）](#clip跨模态匹配模型)
- [MAE（掩码自编码器）](#mae掩码自编码器)
- [具身智能（Embodied AI）](#具身智能embodied-ai)
- [GAN（生成对抗网络）](#gan生成对抗网络)
- [OCR（光学字符识别）](#ocr光学字符识别)
- [NeRF（神经辐射场）](#nerf神经辐射场)
- [DETR（检测Transformer）](#detr检测transformer)
- [提示学习（Prompt）](#提示学习prompt)
- [多模态大语言模型（MLLM）](#多模态大语言模型mllm)
- [大语言模型（LLM）](#大语言模型llm)
- [NAS（神经架构搜索）](#nas神经架构搜索)
- [ReID（重识别）](#reid重识别)
- [扩散模型（Diffusion Models）](#扩散模型diffusion-models)
- [视觉Transformer（Vision Transformer）](#视觉transformervision-transformer)
- [视觉与语言（Vision-Language）](#视觉与语言vision-language)
- [目标检测（Object Detection）](#目标检测object-detection)
- [异常检测（Anomaly Detection）](#异常检测anomaly-detection)
- [目标跟踪（Object Tracking）](#目标跟踪object-tracking)
- [语义分割（Semantic Segmentation）](#语义分割semantic-segmentation)
- [医学图像（Medical Image）](#医学图像medical-image)
- [医学图像分割（Medical Image Segmentation）](#医学图像分割medical-image-segmentation)
- [自动驾驶（Autonomous Driving）](#自动驾驶autonomous-driving)
- [3D点云（3D-Point-Cloud）](#3d点云3d-point-cloud)
- [3D目标检测（3D Object Detection）](#3d目标检测3d-object-detection)
- [3D语义分割（3D Semantic Segmentation）](#3d语义分割3d-semantic-segmentation)
- [图像编辑（Image Editing）](#图像编辑image-editing)
- [视频编辑（Video Editing）](#视频编辑video-editing)
- [低级视觉（Low-level Vision）](#低级视觉low-level-vision)
- [超分辨率（Super-Resolution）](#超分辨率super-resolution)
- [去噪（Denoising）](#去噪denoising)
  - [图像去噪（Image Denoising）](#图像去噪image-denoising)
- [3D人体姿态估计（3D Human Pose Estimation）](#3d人体姿态估计3d-human-pose-estimation)
- [图像生成（Image Generation）](#图像生成image-generation)
- [视频生成（Video Generation）](#视频生成video-generation)
- [3D生成](#3d生成)
- [视频理解（Video Understanding）](#视频理解video-understanding)
- [知识蒸馏（Knowledge Distillation）](#知识蒸馏knowledge-distillation)
- [立体匹配（Stereo Matching）](#立体匹配stereo-matching)
- [场景图生成（Scene Graph Generation）](#场景图生成scene-graph-generation)
- [视频质量评价（Video Quality Assessment）](#视频质量评价video-quality-assessment)
- [数据集（Datasets）](#数据集datasets)
- [其他（Others）](#其他others)

<a name="3DGS"></a>

# 3DGS（高斯溅射，Gaussian Splatting）

**《Scaffold-GS：面向视图自适应渲染的结构化3D高斯模型》**
- 项目主页：https://city-super.github.io/scaffold-gs/
- 论文链接：https://arxiv.org/abs/2312.00109
- 代码仓库：https://github.com/city-super/Scaffold-GS

**《GPS-Gaussian：面向实时人体新视图合成的可泛化像素级3D高斯溅射》**
- 项目主页：https://shunyuanzheng.github.io/GPS-Gaussian 
- 论文链接：https://arxiv.org/abs/2312.02155
- 代码仓库：https://github.com/ShunyuanZheng/GPS-Gaussian

**《GaussianAvatar：基于可驱动3D高斯的单视频真实感人体化身建模》**
- 论文链接：https://arxiv.org/abs/2312.02134
- 代码仓库：https://github.com/huliangxiao/GaussianAvatar

**《GaussianEditor：基于高斯溅射的快速可控3D编辑》**
- 论文链接：https://arxiv.org/abs/2311.14521
- 代码仓库：https://github.com/buaacyw/GaussianEditor 

**《可变形3D高斯：面向高保真单目动态场景重建》**
- 项目主页：https://ingra14m.github.io/Deformable-Gaussians/ 
- 论文链接：https://arxiv.org/abs/2309.13101
- 代码仓库：https://github.com/ingra14m/Deformable-3D-Gaussians

**《SC-GS：面向可编辑动态场景的稀疏控制高斯溅射》**
- 项目主页：https://yihua7.github.io/SC-GS-web/ 
- 论文链接：https://arxiv.org/abs/2312.14937
- 代码仓库：https://github.com/yihua7/SC-GS

**《时空高斯特征溅射：面向实时动态视图合成》**
- 项目主页：https://oppo-us-research.github.io/SpacetimeGaussians-website/ 
- 论文链接：https://arxiv.org/abs/2312.16812
- 代码仓库：https://github.com/oppo-us-research/SpacetimeGaussians

**《DNGaussian：基于全局-局部深度归一化的稀疏视图3D高斯辐射场优化》**
- 项目主页：https://fictionarry.github.io/DNGaussian/
- 论文链接：https://arxiv.org/abs/2403.06912
- 代码仓库：https://github.com/Fictionarry/DNGaussian

**《4D高斯溅射：面向实时动态场景渲染》**
- 论文链接：https://arxiv.org/abs/2310.08528
- 代码仓库：https://github.com/hustvl/4DGaussians

**《GaussianDreamer：通过桥接2D与3D扩散模型实现文本到3D高斯的快速生成》**
- 论文链接：https://arxiv.org/abs/2310.08529
- 代码仓库：https://github.com/hustvl/GaussianDreamer

<a name="Avatars"></a>

# 数字人化身（Avatars）

**《GaussianAvatar：基于可驱动3D高斯的单视频真实感人体化身建模》**
- 论文链接：https://arxiv.org/abs/2312.02134
- 代码仓库：https://github.com/huliangxiao/GaussianAvatar

**《基于头戴式传感器的实时仿真化身》**
- 项目主页：https://www.zhengyiluo.com/SimXR/
- 论文链接：https://arxiv.org/abs/2403.06862

<a name="Backbone"></a>

# 骨干网络（Backbone）

**《RepViT：从Transformer视角重访移动端CNN》**
- 论文链接：https://arxiv.org/abs/2307.09283
- 代码仓库：https://github.com/THU-MIG/RepViT

**《TransNeXt：面向视觉Transformer的鲁棒中央凹视觉感知》**
- 论文链接：https://arxiv.org/abs/2311.17132
- 代码仓库：https://github.com/DaiShiResearch/TransNeXt

<a name="CLIP"></a>

# CLIP（跨模态匹配模型）

**《Alpha-CLIP：专注于任意目标区域的CLIP模型》**
- 论文链接：https://arxiv.org/abs/2312.03818
- 代码仓库：https://github.com/SunzeY/AlphaCLIP

**《FairCLIP：面向视觉-语言学习的公平性优化》**
- 论文链接：https://arxiv.org/abs/2403.19949
- 代码仓库：https://github.com/Harvard-Ophthalmology-AI-Lab/FairCLIP

<a name="MAE"></a>

# MAE（掩码自编码器）

<a name="Embodied-AI"></a>

# 具身智能（Embodied AI）

**《EmbodiedScan：面向具身智能的全栈多模态3D感知套件》**
- 项目主页：https://tai-wang.github.io/embodiedscan/
- 论文链接：https://arxiv.org/abs/2312.16170
- 代码仓库：https://github.com/OpenRobotLab/EmbodiedScan

**《MP5：基于主动感知的Minecraft多模态开放式具身系统》**
- 项目主页：https://iranqin.github.io/MP5.github.io/ 
- 论文链接：https://arxiv.org/abs/2312.07472
- 代码仓库：https://github.com/IranQin/MP5

**《LEMON：从2D图像中学习3D人机交互关系》**
- 论文链接：https://arxiv.org/abs/2312.08963
- 代码仓库：https://github.com/yyvhang/lemon_3d 

<a name="GAN"></a>

# GAN（生成对抗网络）

<a name="OCR"></a>

# OCR（光学字符识别）

**《OCR缩放定律的实证研究》**
- 论文链接：https://arxiv.org/abs/2401.00028
- 代码仓库：https://github.com/large-ocr-model/large-ocr-model.github.io

**《ODM：面向场景文本检测与识别的文本-图像深度对齐预训练方法》**
- 论文链接：https://arxiv.org/abs/2403.00303
- 代码仓库：https://github.com/PriNing/ODM 

<a name="NeRF"></a>

# NeRF（神经辐射场）

**《PIE-NeRF🍕：基于物理的神经辐射场交互式弹性动力学》**
- 论文链接：https://arxiv.org/abs/2311.13099
- 代码仓库：https://github.com/FYTalon/pienerf/ 

<a name="DETR"></a>

# DETR（检测Transformer）

**《DETR系列在实时目标检测上超越YOLO系列》**
- 论文链接：https://arxiv.org/abs/2304.08069
- 代码仓库：https://github.com/lyuwenyu/RT-DETR

**《Salience DETR：基于层级显著性过滤 refinement 的检测Transformer增强》**
- 论文链接：https://arxiv.org/abs/2403.16131
- 代码仓库：https://github.com/xiuqhou/Salience-DETR

<a name="Prompt"></a>

# 提示学习（Prompt）

<a name="MLLM"></a>

# 多模态大语言模型（MLLM）

**《mPLUG-Owl2：以模态协作革新多模态大语言模型》**
- 论文链接：https://arxiv.org/abs/2311.04257
- 代码仓库：https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2

**《面向多模态大语言模型的链接上下文学习》**
- 论文链接：https://arxiv.org/abs/2308.07891
- 代码仓库：https://github.com/isekai-portal/Link-Context-Learning/tree/main 

**《OPERA：通过过信任惩罚与反思分配缓解多模态大语言模型的幻觉问题》**
- 论文链接：https://arxiv.org/abs/2311.17911
- 代码仓库：https://github.com/shikiw/OPERA

**《让大型多模态模型理解任意视觉提示》**
- 项目主页：https://vip-llava.github.io/ 
- 论文链接：https://arxiv.org/abs/2312.00784

**《Pink：释放多模态大语言模型的指代理解能力》**
- 论文链接：https://arxiv.org/abs/2310.00582
- 代码仓库：https://github.com/SY-Xuan/Pink

**《Chat-UniVi：统一视觉表示赋能大语言模型的图像与视频理解》**
- 论文链接：https://arxiv.org/abs/2311.08046
- 代码仓库：https://github.com/PKU-YuanGroup/Chat-UniVi

**《OneLLM：统一所有模态与语言对齐的框架》**
- 论文链接：https://arxiv.org/abs/2312.03700
- 代码仓库：https://github.com/csuhan/OneLLM

<a name="LLM"></a>

# 大语言模型（LLM）

**《VTimeLLM：赋能大语言模型掌握视频时刻信息》**
- 论文链接：https://arxiv.org/abs/2311.18445
- 代码仓库：https://github.com/huangb23/VTimeLLM 

<a name="NAS"></a>

# NAS（神经架构搜索）

<a name="ReID"></a>

# ReID（重识别）

**《Magic Tokens：为多模态目标重识别选择多样化令牌》**
- 论文链接：https://arxiv.org/abs/2403.10254
- 代码仓库：https://github.com/924973292/EDITOR 

**《面向文本到图像行人重识别的噪声对应学习》**
- 论文链接：https://arxiv.org/abs/2308.09911
- 代码仓库：https://github.com/QinYang79/RDE 

<a name="Diffusion"></a>

# 扩散模型（Diffusion Models）

**《InstanceDiffusion：面向图像生成的实例级控制》**
- 项目主页：https://people.eecs.berkeley.edu/~xdwang/projects/InstDiff/
- 论文链接：https://arxiv.org/abs/2402.03290
- 代码仓库：https://github.com/frank-xwang/InstanceDiffusion

**《残差去噪扩散模型》**
- 论文链接：https://arxiv.org/abs/2308.13712
- 代码仓库：https://github.com/nachifur/RDDM

**《DeepCache：免费加速扩散模型》**
- 论文链接：https://arxiv.org/abs/2312.00858
- 代码仓库：https://github.com/horseee/DeepCache

**《DEADiff：基于解耦表示的高效风格化扩散模型》**
- 项目主页：https://tianhao-qi.github.io/DEADiff/ 
- 论文链接：https://arxiv.org/abs/2403.06951
- 代码仓库：https://github.com/Tianhao-Qi/DEADiff_code

**《SVGDreamer：基于扩散模型的文本引导SVG生成》**
- 论文链接：https://arxiv.org/abs/2312.16476
- 代码仓库：https://ximinng.github.io/SVGDreamer-project/

**《InteractDiffusion：面向文本到图像扩散模型的交互控制》**
- 论文链接：https://arxiv.org/abs/2312.05849
- 代码仓库：https://github.com/jiuntian/interactdiffusion

**《MMA-Diffusion：面向扩散模型的多模态攻击》**
- 论文链接：https://arxiv.org/abs/2311.17516
- 代码仓库：https://github.com/yangyijune/MMA-Diffusion

**《VMC：基于时序注意力自适应的文本到视频扩散模型视频运动定制》**
- 项目主页：https://video-motion-customization.github.io/ 
- 论文链接：https://arxiv.org/abs/2312.00845
- 代码仓库：https://github.com/HyeonHo99/Video-Motion-Customization

<a name="Vision-Transformer"></a>

# 视觉Transformer（Vision Transformer）

**《TransNeXt：面向视觉Transformer的鲁棒中央凹视觉感知》**
- 论文链接：https://arxiv.org/abs/2311.17132
- 代码仓库：https://github.com/DaiShiResearch/TransNeXt

**《RepViT：从Transformer视角重访移动端CNN》**
- 论文链接：https://arxiv.org/abs/2307.09283
- 代码仓库：https://github.com/THU-MIG/RepViT

**《基于令牌扩展的Transformer通用高效训练》**
- 论文链接：https://arxiv.org/abs/2404.00672
- 代码仓库：https://github.com/Osilly/TokenExpansion 

<a name="VL"></a>

# 视觉与语言（Vision-Language）

**《PromptKD：面向视觉-语言模型的无监督提示蒸馏》**
- 论文链接：https://arxiv.org/abs/2403.02781
- 代码仓库：https://github.com/zhengli97/PromptKD

**《FairCLIP：面向视觉-语言学习的公平性优化》**
- 论文链接：https://arxiv.org/abs/2403.19949
- 代码仓库：https://github.com/Harvard-Ophthalmology-AI-Lab/FairCLIP

<a name="Object-Detection"></a>

# 目标检测（Object Detection）

**《DETR系列在实时目标检测上超越YOLO系列》**
- 论文链接：https://arxiv.org/abs/2304.08069
- 代码仓库：https://github.com/lyuwenyu/RT-DETR

**《基于零样本昼夜域自适应的目标检测性能提升》**
- 论文链接：https://arxiv.org/abs/2312.01220
- 代码仓库：https://github.com/ZPDu/Boosting-Object-Detection-with-Zero-Shot-Day-Night-Domain-Adaptation 

**《YOLO-World：实时开放词汇目标检测》**
- 论文链接：https://arxiv.org/abs/2401.17270
- 代码仓库：https://github.com/AILab-CVC/YOLO-World

**《Salience DETR：基于层级显著性过滤 refinement 的检测Transformer增强》**
- 论文链接：https://arxiv.org/abs/2403.16131
- 代码仓库：https://github.com/xiuqhou/Salience-DETR

<a name="Anomaly-Detection"></a>

# 异常检测（Anomaly Detection）

**《面向开集有监督异常检测的异常异质性学习》**
- 论文链接：https://arxiv.org/abs/2310.12790
- 代码仓库：https://github.com/mala-lab/AHL

<a name="VT"></a>

# 目标跟踪（Object Tracking）

**《深入探索多目标跟踪中的轨迹长尾分布》**
- 论文链接：https://arxiv.org/abs/2403.04700
- 代码仓库：https://github.com/chen-si-jia/Trajectory-Long-tail-Distribution-for-MOT 

<a name="Semantic-Segmentation"></a>

# 语义分割（Semantic Segmentation）

**《更强、更少、更优：利用视觉基础模型实现域泛化语义分割》**
- 论文链接：https://arxiv.org/abs/2312.04265
- 代码仓库：https://github.com/w1oves/Rein

**《SED：面向开放词汇语义分割的简单编解码器》**
- 论文链接：https://arxiv.org/abs/2311.15537
- 代码仓库：https://github.com/xb534/SED 

<a name="MI"></a>

# 医学图像（Medical Image）

**《特征重嵌入：在计算病理学中实现基础模型级性能》**
- 论文链接：https://arxiv.org/abs/2402.17228
- 代码仓库：https://github.com/DearCaat/RRT-MIL

**《VoCo：面向3D医学图像分析的简单高效体积对比学习框架》**
- 论文链接：https://arxiv.org/abs/2402.17300
- 代码仓库：https://github.com/Luffy03/VoCo

**《ChAda-ViT：面向异质显微图像联合表示学习的通道自适应注意力》**
- 论文链接：https://arxiv.org/abs/2311.15264
- 代码仓库：https://github.com/nicoboou/chada_vit 

<a name="MIS"></a>

# 医学图像分割（Medical Image Segmentation）

<a name="Autonomous-Driving"></a>

# 自动驾驶（Autonomous Driving）

**《UniPAD：面向自动驾驶的通用预训练范式》**
- 论文链接：https://arxiv.org/abs/2310.08370
- 代码仓库：https://github.com/Nightmare-n/UniPAD

**《Cam4DOcc：面向自动驾驶应用的纯相机4D占据预测基准》**
- 论文链接：https://arxiv.org/abs/2311.17663
- 代码仓库：https://github.com/haomo-ai/Cam4DOcc

**《面向在线3D场景感知的基于记忆的适配器》**
- 论文链接：https://arxiv.org/abs/2403.06974
- 代码仓库：https://github.com/xuxw98/Online3D

**《基于上下文实例查询的3D语义场景补全协同优化》**
- 论文链接：https://arxiv.org/abs/2306.15670
- 代码仓库：https://github.com/hustvl/Symphonies

**《面向路侧协同感知的真实世界大规模数据集》**
- 论文链接：https://arxiv.org/abs/2403.10145
- 代码仓库：https://github.com/AIR-THU/DAIR-RCooper

**《面向自动驾驶的单视图与多视图深度自适应融合》**
- 论文链接：https://arxiv.org/abs/2403.07535
- 代码仓库：https://github.com/Junda24/AFNet

**《基于TSP6K数据集的交通场景解析》**
- 论文链接：https://arxiv.org/pdf/2303.02835.pdf
- 代码仓库：https://github.com/PengtaoJiang/TSP6K 

<a name="3D-Point-Cloud"></a>

# 3D点云（3D-Point-Cloud）

<a name="3DOD"></a>

# 3D目标检测（3D Object Detection）

**《PTT：面向高效时序3D目标检测的点-轨迹Transformer》**
- 论文链接：https://arxiv.org/abs/2312.08371
- 代码仓库：https://github.com/kuanchihhuang/PTT

**《UniMODE：统一单目3D目标检测》**
- 论文链接：https://arxiv.org/abs/2402.18573

<a name="3DOD"></a>

# 3D语义分割（3D Semantic Segmentation）

<a name="Image-Editing"></a>

# 图像编辑（Image Editing）

**《一编即全：交互式批量图像编辑》**
- 项目主页：https://thaoshibe.github.io/edit-one-for-all 
- 论文链接：https://arxiv.org/abs/2401.10219
- 代码仓库：https://github.com/thaoshibe/edit-one-for-all

<a name="Video-Editing"></a>

# 视频编辑（Video Editing）

**《MaskINT：基于插值非自回归掩码Transformer的视频编辑》**
- 项目主页：https://maskint.github.io
- 论文链接：https://arxiv.org/abs/2312.12468

<a name="LLV"></a>

# 低级视觉（Low-level Vision）

**《残差去噪扩散模型》**
- 论文链接：https://arxiv.org/abs/2308.13712
- 代码仓库：https://github.com/nachifur/RDDM

**《基于预训练模型先验的图像恢复性能提升》**
- 论文链接：https://arxiv.org/abs/2403.06793

<a name="SR"></a>

# 超分辨率（Super-Resolution）

**《SeD：面向图像超分辨率的语义感知判别器》**
- 论文链接：https://arxiv.org/abs/2402.19387
- 代码仓库：https://github.com/lbc12345/SeD

**《APISR：受动画制作启发的真实世界动画超分辨率》**
- 论文链接：https://arxiv.org/abs/2403.01598
- 代码仓库：https://github.com/Kiteretsu77/APISR 

<a name="Denoising"></a>

# 去噪（Denoising）

## 图像去噪（Image Denoising）

<a name="3D-Human-Pose-Estimation"></a>

# 3D人体姿态估计（3D Human Pose Estimation）

**《Hourglass Tokenizer：面向高效Transformer-based 3D人体姿态估计》**
- 论文链接：https://arxiv.org/abs/2311.12028
- 代码仓库：https://github.com/NationalGAILab/HoT 

<a name="Image-Generation"></a>

# 图像生成（Image Generation）

**《InstanceDiffusion：面向图像生成的实例级控制》**
- 项目主页：https://people.eecs.berkeley.edu/~xdwang/projects/InstDiff/
- 论文链接：https://arxiv.org/abs/2402.03290
- 代码仓库：https://github.com/frank-xwang/InstanceDiffusion

**《ECLIPSE：面向图像生成的资源高效文本到图像先验》**
- 项目主页：https://eclipse-t2i.vercel.app/
- 论文链接：https://arxiv.org/abs/2312.04655
- 代码仓库：https://github.com/eclipse-t2i/eclipse-inference

**《Instruct-Imagen：基于多模态指令的图像生成》**
- 论文链接：https://arxiv.org/abs/2401.01952

**《残差去噪扩散模型》**
- 论文链接：https://arxiv.org/abs/2308.13712
- 代码仓库：https://github.com/nachifur/RDDM

**《UniGS：面向图像生成与分割的统一表示》**
- 论文链接：https://arxiv.org/abs/2312.01985

**《面向文本到图像合成的多实例生成控制器》**
- 论文链接：https://arxiv.org/abs/2402.05408
- 代码仓库：https://github.com/limuloo/migc

**《SVGDreamer：基于扩散模型的文本引导SVG生成》**
- 论文链接：https://arxiv.org/abs/2312.16476
- 代码仓库：https://ximinng.github.io/SVGDreamer-project/

**《InteractDiffusion：面向文本到图像扩散模型的交互控制》**
- 论文链接：https://arxiv.org/abs/2312.05849
- 代码仓库：https://github.com/jiuntian/interactdiffusion

**《Ranni：驯服文本到图像扩散模型以实现精准提示跟随》**
- 论文链接：https://arxiv.org/abs/2311.17002
- 代码仓库：https://github.com/ali-vilab/Ranni

<a name="Video-Generation"></a>

# 视频生成（Video Generation）

**《Vlogger：让你的梦想成为Vlog》**
- 论文链接：https://arxiv.org/abs/2401.09414
- 代码仓库：https://github.com/Vchitect/Vlogger

**《VBench：面向视频生成模型的综合基准套件》**
- 项目主页：https://vchitect.github.io/VBench-project/ 
- 论文链接：https://arxiv.org/abs/2311.17982
- 代码仓库：https://github.com/Vchitect/VBench

**《VMC：基于时序注意力自适应的文本到视频扩散模型视频运动定制》**
- 项目主页：https://video-motion-customization.github.io/ 
- 论文链接：https://arxiv.org/abs/2312.00845
- 代码仓库：https://github.com/HyeonHo99/Video-Motion-Customization

<a name="3D-Generation"></a>

# 3D生成

**《CityDreamer：无界3D城市的组合生成模型》**
- 项目主页：https://haozhexie.com/project/city-dreamer/ 
- 论文链接：https://arxiv.org/abs/2309.00610
- 代码仓库：https://github.com/hzxie/city-dreamer

**《LucidDreamer：通过区间得分匹配实现高保真文本到3D生成》**
- 论文链接：https://arxiv.org/abs/2311.11284
- 代码仓库：https://github.com/EnVision-Research/LucidDreamer 

<a name="Video-Understanding"></a>

# 视频理解（Video Understanding）

**《MVBench：面向多模态视频理解的综合基准》**
- 论文链接：https://arxiv.org/abs/2311.17005
- 代码仓库：https://github.com/OpenGVLab/Ask-Anything/tree/main/video_chat2 

<a name="KD"></a>

# 知识蒸馏（Knowledge Distillation）

**《知识蒸馏中的对数标准化》**
- 论文链接：https://arxiv.org/abs/2403.01427
- 代码仓库：https://github.com/sunshangquan/logit-standardization-KD

**《基于极大极小扩散的高效数据集蒸馏》**
- 论文链接：https://arxiv.org/abs/2311.15529
- 代码仓库：https://github.com/vimar-gu/MinimaxDiffusion

<a name="Stereo-Matching"></a>

# 立体匹配（Stereo Matching）

**《面向立体匹配的神经马尔可夫随机场》**
- 论文链接：https://arxiv.org/abs/2403.11193
- 代码仓库：https://github.com/aeolusguan/NMRF 

<a name="SGG"></a>

# 场景图生成（Scene Graph Generation）

**《HiKER-SGG：层级知识增强的鲁棒场景图生成》**
- 项目主页：https://zhangce01.github.io/HiKER-SGG/ 
- 论文链接：https://arxiv.org/abs/2403.12033
- 代码仓库：https://github.com/zhangce01/HiKER-SGG

<a name="Video-Quality-Assessment"></a>

# 视频质量评价（Video Quality Assessment）

**《KVQ：面向短视频的万花筒视频质量评价》**
- 项目主页：https://lixinustc.github.io/projects/KVQ/ 
- 论文链接：https://arxiv.org/abs/2402.07220
- 代码仓库：https://github.com/lixinustc/KVQ-Challenge-CVPR-NTIRE2024

<a name="Datasets"></a>

# 数据集（Datasets）

**《面向路侧协同感知的真实世界大规模数据集》**
- 论文链接：https://arxiv.org/abs/2403.10145
- 代码仓库：https://github.com/AIR-THU/DAIR-RCooper

**《基于TSP6K数据集的交通场景解析》**
- 论文链接：https://arxiv.org/pdf/2303.02835.pdf
- 代码仓库：https://github.com/PengtaoJiang/TSP6K 

<a name="Others"></a>

# 其他（Others）

**《目标识别作为下一个令牌预测》**
- 论文链接：https://arxiv.org/abs/2312.02142
- 代码仓库：https://github.com/kaiyuyue/nxtp

**《ParameterNet：参数即全部——面向移动网络大规模视觉预训练》**
- 论文链接：https://arxiv.org/abs/2306.14525
- 代码仓库：https://parameternet.github.io/ 

**《基于混合位置编码的无缝人体运动合成》**
- 论文链接：https://arxiv.org/abs/2402.15509
- 代码仓库：https://github.com/BarqueroGerman/FlowMDM 

**《LL3DA：面向全3D理解、推理与规划的视觉交互式指令微调》**
- 项目主页：https://ll3da.github.io/ 
- 论文链接：https://arxiv.org/abs/2311.18651
- 代码仓库：https://github.com/Open3DA/LL3DA

**《CLOVA：具备工具使用与更新能力的闭环视觉助手》**
- 项目主页：https://clova-tool.github.io/ 
- 论文链接：https://arxiv.org/abs/2312.10908

**《MoMask：3D人体运动的生成式掩码建模》**
- 论文链接：https://arxiv.org/abs/2312.00063
- 代码仓库：https://github.com/EricGuo5513/momask-codes

**《真实场景中的隐式真值与补全》**
- 项目主页：https://www.robots.ox.ac.uk/~vgg/research/amodal/ 
- 论文链接：https://arxiv.org/abs/2312.17247
- 代码仓库：https://github.com/Championchess/Amodal-Completion-in-the-Wild

**《通过自洽解释改进视觉接地》**
- 论文链接：https://arxiv.org/abs/2312.04554
- 代码仓库：https://github.com/uvavision/SelfEQ

**《ImageNet-D：面向扩散合成目标的神经网络鲁棒性基准》**
- 项目主页：https://chenshuang-zhang.github.io/imagenet_d/
- 论文链接：https://arxiv.org/abs/2403.18775
- 代码仓库：https://github.com/chenshuang-zhang/imagenet_d

**《从合成人体群体活动中学习》**
- 项目主页：https://cjerry1243.github.io/M3Act/ 
- 论文链接：https://arxiv.org/abs/2306.16772
- 代码仓库：https://github.com/cjerry1243/M3Act

**《一种跨被试脑解码框架》**
- 项目主页：https://littlepure2333.github.io/MindBridge/
- 论文链接：https://arxiv.org/abs/2404.07850
- 代码仓库：https://github.com/littlepure2333/MindBridge

**《基于低秩专家混合的多任务密集预测》**
- 论文链接：https://arxiv.org/abs/2403.17749
- 代码仓库：https://github.com/YuqiYang213/MLoRE

**《面向广义类别发现的对比均值漂移学习》**
- 项目主页：https://postech-cvlab.github.io/cms/ 
- 论文链接：https://arxiv.org/abs/2404.09451
- 代码仓库：https://github.com/sua-choi/CMS
