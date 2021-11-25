# Quick navigation

- [repositories](awesome_paper_list_and_repos.md)
- [Datasets](dataset.md)
- [papers](#papers)
  - [Non-DL based approach](non_dl_papers.md)
  - [DL based approach](#DL-based-approach)
    - [2014-2016](2014-2016_papers.md)
    - [2017](2017_papers.md)
    - [2018](2018_papers.md)
    - [2019](2019_papers.md)
    - [2020](2020_papers.md)
    - [2021](#2021)
- [Super Resolution workshop papers](workshops.md)
- [Super Resolution survey](sr_survey.md)

# Awesome-Super-Resolution（in progress）

Collect some super-resolution related papers, data and repositories.

## papers

### DL based approach

Note this table is referenced from [here](https://github.com/LoSealL/VideoSuperResolution/blob/master/README.md#network-list-and-reference-updating)

### 2021
More years papers, plase check Quick navigation

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     |
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|Trilevel Neural Architecture Search for Efficient Single Image Super-Resolution        | TrilevelNAS            | [arxiv](https://arxiv.org/pdf/2101.06658.pdf)            | -              | Trilevel Architecture Search Space      |
|SplitSR: An End-to-End Approach to Super-Resolution on Mobile Devices                  | SplitSR                | [arxiv](https://arxiv.org/pdf/2101.07996.pdf)            | -              | lightweight,on Mobile Devices      |
|Learning for Unconstrained Space-Time Video Super-Resolution                           | USTVSRNet              | [arxiv](https://arxiv.org/pdf/2102.13011.pdf)            | -              | ***VSR***, Unconstrained video super-resolution,general-ized  pixelshuffle  layer.     |
|ClassSR: A General Framework to Accelerate Super-Resolution Networks by Data Characteristic| ClassSR            | [cvpr21](https://arxiv.org/pdf/2103.04039.pdf)           | [code](https://github.com/Xiangtaokong/ClassSR)         | classification，lightweight |
|Collapsible Linear Blocks for Super-Efficient Super Resolution                         | SESR                   | [arxiv](https://arxiv.org/pdf/2103.09404.pdf)            | -              |  Super-Efficient SR, overparameterization|
|Self-Supervised Adaptation for Video Super-Resolution                                  | Adapted VSR            | [arxiv](https://arxiv.org/pdf/2103.10081.pdf)            | -              |  ***VSR***, Self-Supervised Adaptationn|
|Generic Perceptual Loss for Modeling Structured Output Dependencies                    | Generic Perceptual Loss| [cvpr21](https://arxiv.org/pdf/2103.10571.pdf)           | -              |  Random VGG w/o pretrianed, work at semantic segmentation, depthestimation  and  instance  segmentation|
|Large Motion Video Super-Resolution with Dual Subnet and Multi-Stage Communicated Upsampling| U3D-RDN           | [AAAI21](https://arxiv.org/pdf/2103.11744.pdf)           | -              |  ***VSR***, Dual Subnet, Multi-stage Communicated Up-sampling|
|UltraSR: Spatial Encoding is a Missing Key for Implicit Image Function-based Arbitrary-Scale Super-Resolution| UltraSR         | [arxiv](https://arxiv.org/pdf/2103.12716.pdf)            | -              |  Implicit Image Function Based, Arbitrary-Scale|
|D2C-SR: A Divergence to Convergence Approach for Image Super-Resolution                | D2C-SR                 | [arxiv](https://arxiv.org/pdf/2103.14373.pdf)            | -              |  RealSR， divergence stage with a triple loss ，convergence stage|
|Training a Better Loss Function for Image Restoration                                  | MDF loss               | [arxiv](https://arxiv.org/pdf/2103.14616.pdf)            | [code](https://github.com/gfxdisp/mdf)              |  Multi-Scale Discriminative Feature loss|
|Transitive Learning: Exploring the Transitivity of Degradations for Blind Super-Resolution| TLSR                | [arxiv](https://arxiv.org/pdf/2103.15290.pdf)            | [code](https://github.com/YuanfeiHuang/TLSR)        | Blind SR， Transitive Learning   |
|Best-Buddy GANs for Highly Detailed Image Super-Resolution                             | Beby-GAN               | [arxiv](https://arxiv.org/pdf/2103.15295.pdf)            | [code](https://github.com/Jia-Research-Lab/Simple-SR)  |relaxing the immutable one-to-one constraint, Best-Buddy Loss  |
|Flow-based Kernel Prior with Application to Blind Super-Resolution                     | FKP                    | [cvpr21](https://arxiv.org/pdf/2103.15977.pdf)           | [code](https://github.com/JingyunLiang/FKP)            |Blind SR, flow-based kernel prio|
|Conditional Meta-Network for Blind Super-Resolution with Multiple Degradations         | CMDSR                  | [arxiv](https://arxiv.org/pdf/2104.03926.pdf)            | -            |Blind SR, Conditional Meta-Network|
|Image Super-Resolution via Iterative Refinement                                        | SR3                    | [arxiv](https://arxiv.org/pdf/2104.07636.pdf)            | -            |Repeated Refinement, better than  SOTA GAN|
|BAM: A Lightweight and Efficient Balanced Attention Mechanism for Single Image Super Resolution| BAM            | [arxiv](https://arxiv.org/pdf/2104.07566.pdf)            | [code](https://github.com/dandingbudanding/BAM_A_lightweight_but_efficient_Balanced_attention_mechanism_for_super_resolution)            |balanced Attention Mechanism |
|Kernel Agnostic Real-world Image Super-resolution                                      | KASR                   | [arxiv](https://arxiv.org/pdf/2104.09008.pdf)            | -              |realsr, Kernel Agnostic |
|Neural Architecture Search for Image Super-Resolution Using Densely Constructed Search Space: DeCoNAS| DeCoNAS  | [arxiv](https://arxiv.org/pdf/2104.09048.pdf)            | -              |Densely Constructed Search Space  |
|Attention in Attention Network for Image Super-Resolution                              | A2N                    | [arxiv](https://arxiv.org/pdf/2104.09497.pdf)            | [code](https://github.com/haoyuc/A2N)    |Attention in Attention， lightweight  |
|Temporal Modulation Network for Controllable Space-Time Video Super-Resolution         | TMNet                  | [arxiv](https://arxiv.org/pdf/2104.10642.pdf)            | [code](https://github.com/CS-GangXu/TMNet)    | ***VSR***， interpolate frames,  Temporal Modulation Block  |
|A Two-Stage Attentive Network for Single Image Super-Resolution                        | TSAN                   | [arxiv](https://arxiv.org/pdf/2104.10488.pdf)            | [code](https://github.com/Jee-King/TSAN)    | SISR， multi-context attentiveblock  |
|BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and Alignment   | BasicVSR++             | [arxiv](https://arxiv.org/pdf/2104.13371.pdf)            | [code](https://github.com/open-mmlab/mmediting)    | ***VSR***， 3 champions and 1 runner-up in NTIRE 2021   |
|SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models              | SRDiff                 | [arxiv](https://arxiv.org/pdf/2104.14951.pdf)            |    | Diffusion Probabilistic Models   |
|SRWarp: Generalized Image Super-Resolution under Arbitrary Transformation              | SRWarp                 | [cvpr21](https://arxiv.org/pdf/2104.10325.pdf)            |[code](https://github.com/sanghyun-son/srwarp)    |  arbitrary transformation   |
|Cross-MPI: Cross-scale Stereo for Image Super-Resolutionusing Multiplane Images        | Cross-MPI              | [cvpr21](https://arxiv.org/pdf/2011.14631.pdf)            |-   |  RefSR, plane-aware attention, coarse-to-fine guided upsampling    |
|Lightweight Image Super-Resolution with Hierarchical and DifferentiableNeural Architecture Search   | DLSR      | [arxiv](https://arxiv.org/pdf/2105.03939.pdf)            |[code](https://github.com/DawnHH/DLSR-PyTorch)    |  Lightweight   |
|HINet: Half Instance Normalization Network for Image Restoration   | HINet      | [arxiv](https://arxiv.org/pdf/2105.06086.pdf)            |-  |  Half Instance Normalization Block, 1st place on the NTIRE 2021 Image Deblurring Challenge - Track2. JPEG Artifacts   |
|FDAN: Flow-guided Deformable Alignment Network for Video Super-Resolution   | FDAN      | [arxiv](https://arxiv.org/pdf/2105.05640.pdf)            |-  |  ***VSR***, Flowguided Deformable Module  |
|End-to-end Alternating Optimization for Blind Super Resolution   | DAN      | [arxiv](https://arxiv.org/pdf/2105.06878.pdf)            |[code](https://github.com/greatlog/DAN)  |  Blind SR, Restorer and Estimator Alternating Optimization  |
|Anchor-based Plain Net for Mobile Image Super-Resolution   | ABPN      | [arxiv](https://arxiv.org/pdf/2105.09750.pdf)            |[code](https://github.com/NJU-Jet/SR_Mobile_Quantization)  |  MAI2021, mobile device SISR, INT8 Quantization  |
|Extremely Lightweight Quantization RobustReal-Time Single-Image Super Resolution for Mobile Devices   | XLSR      | [arxiv](https://arxiv.org/pdf/2105.10288.pdf)            |-  |  MAI2021, mobile device SISR Winner, INT8 Quantization  |
|Robust Reference-based Super-Resolution via C2-Matching   | C2-Matching      | [arxiv](https://arxiv.org/pdf/2105.09750.pdf)            |[code](https://github.com/yumingj/C2-Matching)  |   RefSR, ransformation gap, contrastive correspondence network, resolution gap, teacher-student  correlation  distillation  |
|MASA-SR: Matching Acceleration and Spatial Adaptation forReference-Based Image Super-Resolution   | MASA-SR      | [cvpr21](https://arxiv.org/pdf/2106.02299.pdf)            |[code](https://github.com/dvlab-research/MASA-SR)  |   RefSR, Match & Extraction Module , Spatial Adaptation Module|
|Noise Conditional Flow Model for Learning the Super-Resolution Space   | NCSR      | [arxiv](https://arxiv.org/pdf/2106.04428.pdf)            |[code](https://github.com/younggeun-kim/NCSR)  |   better than GAN-based model，Flow-based， noise conditional layer |
|Variational AutoEncoder for Reference based Image Super-Resolution   | RefVAE      | [arxiv](https://arxiv.org/pdf/2106.04090.pdf)            |[code](https://github.com/Holmes-Alan/RefVAE)  | Variational AutoEncoder， refsr   |
|Video Super-Resolution Transformer   | VSR-Transformer      | [arxiv](https://arxiv.org/pdf/2106.06847.pdf)            |[code](https://github.com/caojiezhang/VSR-Transformer)  | ***VSR***, spatial-temporal convolutional self-attention layer, bidirectional optical flow-based feed-forward layer   |
|Practical Single-Image Super-Resolution Using Look-Up Table   | SR-LUT      | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Jo_Practical_Single-Image_Super-Resolution_Using_Look-Up_Table_CVPR_2021_paper.pdf)            |-  | SISR, fater than Bicubic,  look-up table  |
|Towards Fast and Accurate Real-World Depth Super-Resolution: BenchmarkDataset and Baseline   | FDSR       | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/He_Towards_Fast_and_Accurate_Real-World_Depth_Super-Resolution_Benchmark_Dataset_and_CVPR_2021_paper.pdf)            |-  |  depth map SR  |
|Image Super-Resolution with Non-Local Sparse Attention   | NLSN      | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Image_Super-Resolution_With_Non-Local_Sparse_Attention_CVPR_2021_paper.pdf)            |-  |  Non-Local Sparse Attention， Spherical LSH  |
|Learning the Non-differentiable Optimization for Blind Super-Resolution   | AMNet, AMGAN       | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Hui_Learning_the_Non-Differentiable_Optimization_for_Blind_Super-Resolution_CVPR_2021_paper.pdf)   |-  |  Blind SR， non-differentiable,  adap-tive modulation network  |
|KOALAnet: Blind Super-Resolution using Kernel-Oriented Adaptive Local Adjustment   | KOALAnet       | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Kim_KOALAnet_Blind_Super-Resolution_Using_Kernel-Oriented_Adaptive_Local_Adjustment_CVPR_2021_paper.pdf)   |-  |  Blind SR, kernel-oriented adaptive local adjustment, learns spatially-variant degradation and restoration kernels  |
|Exploring Sparsity in Image Super-Resolution for Efficient Inference| SMSR                   | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Exploring_Sparsity_in_Image_Super-Resolution_for_Efficient_Inference_CVPR_2021_paper.pdf)    |[code](https://github.com/LongguangWang/SMSR)| Sparse Masks, Efficient SISR|
|LAU-Net: Latitude Adaptive Upscaling Network for Omnidirectional Image Super-resolution| LAU-Net   | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Deng_LAU-Net_Latitude_Adaptive_Upscaling_Network_for_Omnidirectional_Image_Super-Resolution_CVPR_2021_paper.pdf)    |[code](https://github.com/wangh-allen/LAU-Net)| Omnidirectional Image SR|
|Tackling the Ill-Posedness of Super-Resolution through Adaptive Target Generation| AdaTarget     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Jo_Tackling_the_Ill-Posedness_of_Super-Resolution_Through_Adaptive_Target_Generation_CVPR_2021_paper.pdf)    |[code](https://github.com/yhjo09/AdaTarget)| Adaptive Target Generator|
|Single Pair Cross-Modality Super Resolution| CMSR     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Shacht_Single_Pair_Cross-Modality_Super_Resolution_CVPR_2021_paper.pdf)    | - |  single-pair,Cross-Modality |
|End-to-End Learning for Joint Image Demosaicing, Denoising and Super-Resolution| JDNDMSR     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Xing_End-to-End_Learning_for_Joint_Image_Demosaicing_Denoising_and_Super-Resolution_CVPR_2021_paper.pdf)    | - |  joint tasks |
|MR Image Super-Resolution with Squeeze and Excitation Reasoning Attention| SERAN     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_MR_Image_Super-Resolution_With_Squeeze_and_Excitation_Reasoning_Attention_Network_CVPR_2021_paper.pdf)    | - |  MRI SR, squeeze and excitation reasoning attention networks |
|Light Field Super-Resolution with Zero-Shot Learning| -     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Cheng_Light_Field_Super-Resolution_With_Zero-Shot_Learning_CVPR_2021_paper.pdf)    | - |   zero shot, light field SR |
|Scene Text Telescope: Text-Focused Scene Image Super-Resolution| TBSRN     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Scene_Text_Telescope_Text-Focused_Scene_Image_Super-Resolution_CVPR_2021_paper.pdf)    | - |   text-focused SR |
|Interpreting Super-Resolution Networks with Local Attribution Maps| LAM     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Gu_Interpreting_Super-Resolution_Networks_With_Local_Attribution_Maps_CVPR_2021_paper.pdf)    | - |   Interpreting SR,local attribution map |
|Turning Frequency to Resolution: Video Super-resolution via Event Cameras| E-VSR     | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Jing_Turning_Frequency_to_Resolution_Video_Super-Resolution_via_Event_Cameras_CVPR_2021_paper.pdf)    | - |   ***VSR***, Event-based VSR |
|GLEAN: Generative Latent Bank for Large-Factor Image Super-Resolution |GLEAN                   | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Chan_GLEAN_Generative_Latent_Bank_for_Large-Factor_Image_Super-Resolution_CVPR_2021_paper.pdf)  | - | Latent Bank, large scale factor  |
|BasicVSR: The Search for Essential Components in Video Super-Resolution and Beyond |BasicVSR    | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Chan_BasicVSR_The_Search_for_Essential_Components_in_Video_Super-Resolution_and_CVPR_2021_paper.pdf)  | - | **VideoSR**, The Search for Essential Components  |
|AdderSR: Towards Energy Efficient Image Super-Resolution|AdderSR                 | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Song_AdderSR_Towards_Energy_Efficient_Image_Super-Resolution_CVPR_2021_paper.pdf)  |- |  SISR, adder neural networks, Energy Efficient |
|Deep Burst Super-Resolution                                                            | BurstSR                | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Bhat_Deep_Burst_Super-Resolution_CVPR_2021_paper.pdf)            | -              | multi-frame sr, new BurstSR dataset      |
|Pre-Trained Image Processing Transformer |IPT          | [cvpr21](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Pre-Trained_Image_Processing_Transformer_CVPR_2021_paper.pdf)  |[code](https://github.com/huawei-noah/Pretrained-IPT) | Pre-Trained Image Processing Transformer, Imagenet pretrained, dramatically improve performance  |
|Blind Image Super-Resolution via ContrastiveRepresentation Learning   | CRL-SR       | [arxiv](https://arxiv.org/pdf/2107.00708.pdf)     |-  | blind SR, contrastive decoupling encoding， contrastive feature refinement   |
|End-to-End Adaptive Monte Carlo Denoising and Super-Resolution   | -       | [arxiv](https://arxiv.org/pdf/2108.06915.pdf)     |-  | Monte Carlo path tracing    |
|SwinIR: Image Restoration Using Swin Transformer   | SwinIR       | [arxiv](https://arxiv.org/pdf/2108.10257.pdf)     |[code](https://github.com/JingyunLiang/SwinIR)  |SISR， Swin Transformer， SOTA    |
|edge–SR: Super–Resolution For The Masses   | eSR       | [arxiv](https://arxiv.org/pdf/2108.10335.pdf)     |-  |SISR， Edge device SR，one–layer architectures use interpretable mechanisms， Filling the gap between classic and deep learning architectures |
|Memory-Augmented Non-Local Attention for Video Super-Resolution   | CSNLN       | [arxiv](https://arxiv.org/pdf/2108.11048.pdf)     |-  |***VSR***， without frame alignment， memory-augmented attention module |
|Simple and Efficient Unpaired Real-world Super-Resolution using Image Statistics   | -       | [arxiv](https://arxiv.org/pdf/2109.09071.pdf)     |-  |unpair SR,variance matching |
|Improving Super-Resolution Performance using Meta-Attention Layers   | -       | [SPL](https://ieeexplore.ieee.org/document/9552573)     |[code](https://github.com/um-dsrg/Super-Resolution-Meta-Attention-Networks)  | SISR， meta-attention   |
|EFENet: Reference-based Video Super-Resolution with Enhanced Flow Estimation   | EFENet | [arxiv](https://arxiv.org/pdf/2110.07797.pdf)     |[code](https://github.com/IndigoPurple/EFENet)  | RefVSR， Enhanced Flow Estimation   |
|Learning A Single Network for Scale-Arbitrary Super-Resolution | arbSR | [iccv21](https://arxiv.org/pdf/2004.03791.pdf) |[code](https://github.com/LongguangWang/ArbSR) | SISR， scale-arbitrary SR |
|Dual-Camera Super-Resolution with Aligned Attention Modules | - | [iccv21](https://arxiv.org/pdf/2109.01349.pdf) |[code](https://tengfei-wang.github.io/Dual-Camera-SR/index.html) | oral, dual camera SR, RefSR,self-supervised domain adaptation strategy |
|Learning Frequency-aware Dynamic Network for Efficient Super-Resolution | FADN | [iccv21](https://arxiv.org/pdf/2103.08357.pdf) |- | Efficient SR，DCT，Mask Predictor，dynamic resblocks，frequency mask loss |
|Designing a Practical Degradation Model for Deep Blind Image Super-Resolution | BSRNet/BSRGAN | [iccv21](https://arxiv.org/pdf/2103.14006.pdf) |- | randomly shuffled blur, downsampling and noise degradations for degradation model |
|Fourier Space Losses for Efficient Perceptual Image Super-Resolution | - | [iccv21](https://arxiv.org/pdf/2105.09750.pdf) |- | Fourier space supervision loss |
|Omniscient Video Super-Resolution | OVSR | [iccv21](https://arxiv.org/pdf/2103.15683.pdf) |- | ***VSR***， new framework， precursor net and successor net |
|Efficient Video Compression via Content-Adaptive Super-Resolution | SRVC | [iccv21](https://arxiv.org/pdf/2104.02322.pdf) |- | Video Compression， Adaptive Conv |
|Mutual Affine Network for Spatially Variant Kernel Estimation in Blind Image Super-Resolution | MANet | [iccv21](https://arxiv.org/pdf/2108.05302.pdf) |[code](https://github.com/JingyunLiang/MANet) | blind SR, spatially variant and invariant kernel, mutual affine network |
|Hierarchical Conditional Flow: A Unified Framework for Image Super-Resolution and Image Rescaling | HCFlow | [iccv21](https://arxiv.org/pdf/2108.05301.pdf) |[code](https://github.com/JingyunLiang/HCFlow) | SR/Rescale, learns a bijective mapping |
|Deep Reparametrization of Multi-Frame Super-Resolution and Denoising | - | [iccv21](https://arxiv.org/pdf/2108.08286.pdf) |- | Multi-Frame，deep reparametrization of the classical MAP objective |
|Attention-based Multi-Reference Learning for Image Super-Resolution | AMRSR | [iccv21](https://arxiv.org/pdf/2108.13697.pdf) |[code](https://marcopesavento.github.io/AMRSR) | RefSR， without frame alignment， Hierarchical Attention-based Similarity |
| COMISR: Compression-Informed Video Super-Resolution          | COMISR                  | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_COMISR_Compression-Informed_Video_Super-Resolution_ICCV_2021_paper.pdf) | [code](https://github.com/google-research/google-research/tree/master/comisr) | ***VSR***, bi-directional recurrent, warping, detail-preserving flow estimation,  Laplacian enhancement |
|Achieving on-Mobile Real-Time Super-Resolution with Neural Architecture and Pruning Search | - | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhan_Achieving_On-Mobile_Real-Time_Super-Resolution_With_Neural_Architecture_and_Pruning_Search_ICCV_2021_paper.pdf) |- | SISR, real-time sr, NAS |
|Event Stream Super-Resolution via Spatiotemporal Constraint Learning | - | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Event_Stream_Super-Resolution_via_Spatiotemporal_Constraint_Learning_ICCV_2021_paper.pdf) |- | event stream SR |
|Dynamic High-Pass Filtering and Multi-Spectral Attention for Image Super-Resolution | DFSA | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Magid_Dynamic_High-Pass_Filtering_and_Multi-Spectral_Attention_for_Image_Super-Resolution_ICCV_2021_paper.pdf) |- | SISR, SOTA, matrix multi-spectral channel attention |
|Context Reasoning Attention Network for Image Super-Resolution | CRAN | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_Context_Reasoning_Attention_Network_for_Image_Super-Resolution_ICCV_2021_paper.pdf) |- | SISR, SOTA, context reasoning attention |
|EvIntSR-Net: Event Guided Multiple Latent Frames Reconstruction and Super-Resolution | - | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Han_EvIntSR-Net_Event_Guided_Multiple_Latent_Frames_Reconstruction_and_Super-Resolution_ICCV_2021_paper.pdf) |- | EvIntSR |
|Deep Blind Video Super-Resolution | - | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Pan_Deep_Blind_Video_Super-Resolution_ICCV_2021_paper.pdf) |- | ***Blind VSR*** |
|Super Resolve Dynamic Scene From Continuous Spike Streams | MGSR | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_Super_Resolve_Dynamic_Scene_From_Continuous_Spike_Streams_ICCV_2021_paper.pdf) |- | Spike camera SR |
|Benchmarking Ultra-High-Definition Image Super-Resolution | MANet | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_Benchmarking_Ultra-High-Definition_Image_Super-Resolution_ICCV_2021_paper.pdf) |- | UHD SR dataset, 4K, 8K, SISR |
|Lucas-Kanade Reloaded: End-to-End Super-Resolution from Raw Image Bursts | - | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Lecouat_Lucas-Kanade_Reloaded_End-to-End_Super-Resolution_From_Raw_Image_Bursts_ICCV_2021_paper.pdf) |[code](https://github.com/bruno-31/lkburst) | Raw Image Bursts SR |
|Unsupervised Real-World Super-Resolution: A Domain Adaptation Perspective | - | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Unsupervised_Real-World_Super-Resolution_A_Domain_Adaptation_Perspective_ICCV_2021_paper.pdf) |- | unpaired realSR, domain adaptation |
|Real-world Video Super-resolution: A Benchmark Dataset and A Decomposition based Learning Scheme | - | [iccv21](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Real-World_Video_Super-Resolution_A_Benchmark_Dataset_and_a_Decomposition_Based_ICCV_2021_paper.pdf) |[code](https://github.com/IanYeung/RealVSR) | ***RealVSR*** dataset |
|Scale-Aware Dynamic Network for Continuous-Scale Super-Resolution | SADN | [arxiv](https://arxiv.org/pdf/2110.15655.pdf) |[code](https://github.com/hanlinwu/SADN) | Arbitrary scale SR, scale-aware dynamic conv |
|MEGAN: Memory Enhanced Graph Attention Network for Space-Time Video Super-Resolutio |  MEGAN | [arxiv](https://arxiv.org/pdf/2110.15327.pdf) | - | ***space-time  VSR***, long-range memory graph aggregation |
|Normalizing Flow as a Flexible Fidelity Objective for Photo-Realistic Super-resolution |  - | [arxiv](https://arxiv.org/pdf/2111.03649.pdf) | [code](https://www.git.io/AdFlow) | flow-based NLL loss,replace L1 |
|Frequency-Aware Physics-Inspired Degradation Model for Real-World Image Super-Resolution |  - | [arxiv](https://arxiv.org/pdf/2111.03301.pdf) | - |  learn the cutoff frequency of real-world degradation process |
|Local-Selective Feature Distillation for Single Image Super-Resolution |  - | [arxiv](https://arxiv.org/pdf/2111.10988.pdf) | - |  feature distillation , local-selective feature distillation (LSFD) 
|Investigating Tradeoffs in Real-World Video Super-Resolution | RealBasicVSR | [arxiv](https://arxiv.org/pdf/2111.12704.pdf) | [code](https://github.com/ckkelvinchan/RealBasicVSR) | ***RealVSR***  |
