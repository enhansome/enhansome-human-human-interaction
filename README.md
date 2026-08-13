# awesome-human-human-interaction with stars

A curated list of awesome human-human interaction (HHI) resources. If you find any errors or problems, please don't hesitate to comment.

## Table of Contents

* [Datasets](#datasets)
* [Papers](#recent-papers)
  * [HHI Generation](#hhi-generation)
  * [Reaction Generation](#reaction-generation)
  * [HHI Reconstruction](#hhi-reconstruction)
  * [HHI Detection](#hhi-detection)
  * [HHI Datasets](#hhi-datasets)
  * [Group Interaction](#group-interaction)
  * [Multi-Human and Objects](#multi-human-and-objects)
  * [Interactive Humanoid](#interactive-humanoid)
  * [Other Applications](#other-applications)

## Datasets

| Dataset                                                                                          | Year | Motions |   Frames   | Texts |   Scheme  |     Modality     |
| ------------------------------------------------------------------------------------------------ | :--: | :-----: | :--------: | :---: | :-------: | :--------------: |
| [UMPM](https://www.projects.science.uu.nl/umpm/)                                                 | 2011 |    36   |    400K    |   No  |   MoCap   |     Skeleton     |
| [SBU Kinect](http://vision.cs.stonybrook.edu/~kiwon/Datasets/SBU_Kinect_Interactions/README.txt) | 2012 |   300   |    7.5K    |   No  |   RGB+D   |     Skeleton     |
| [NTU RGB+D 120](https://rose1.ntu.edu.sg/dataset/actionRecognition/)                             | 2019 |  8,276  |    462K    |   No  |   RGB+D   |     Skeleton     |
| [You2Me](https://vision.cs.utexas.edu/projects/you2me/)                                          | 2020 |    42   |     77K    |   No  |   RGB+D   |     Skeleton     |
| [Chi3D](https://ci3d.imar.ro/chi3d)                                                              | 2020 |   373   |     63K    |   No  |   MoCap   |      SMPL-X      |
| [ExPI](https://team.inria.fr/robotlearn/research/expi-dataset/)                                  | 2022 |   115   |     30K    |   No  | Multi RGB |     Skeleton     |
| [GTA Combat](https://liangxuy.github.io/actformer/)                                              | 2023 |   6.8K  |    2.05M   |   No  | Synthetic |     Skeleton     |
| [Hi4D](https://yifeiyin04.github.io/Hi4D/)                                                       | 2023 |   100   |     11K    |   No  | Multi RGB |       SMPL       |
| [InterHuman](https://tr3e.github.io/intergen-page/)                                              | 2023 |  6,022  |    1.7M    |  Yes  | Multi RGB |       SMPL       |
| [Inter-X](https://liangxuy.github.io/inter-x/)                                                   | 2024 |  11,388 |    8.1M    |  Yes  |   MoCap   | SMPL-X, Skeleton |
| [ReMoCap](https://vcai.mpi-inf.mpg.de/projects/remos/)                                           | 2024 |    87   |   275.7K   |   No  | Multi RGB |     Skeleton     |
| [InterDance](https://inter-dance.github.io/)                                                     | 2025 |    -    | 3.93 hours |   No  |   MoCap   |      SMPL-X      |
| [Embody 3D](https://www.meta.com/emerging-tech/codec-avatars/embody-3d/)                         | 2025 |    -    |  500 hours |  Yes  | Multi RGB |      SMPL-X      |

## Recent Papers

<!-- , __ [[Paper]](), [[Project]](), [[Code]]() -->

### HHI Generation

* Neural Animation Layering for Synthesizing Martial Arts Movements, *SIGGRAPH'21*, [\[Paper\]](https://github.com/sebastianstarke/AI4Animation/blob/master/Media/SIGGRAPH_2021/Paper.pdf) ⭐ 8,831 | 🐛 36 | 🌐 C++ | 📅 2026-04-17

* Local Motion Phases for Learning Multi-Contact Character Movements, *SIGGRAPH'20*, [\[Paper\]](https://github.com/sebastianstarke/AI4Animation/blob/master/Media/SIGGRAPH_2020/Paper.pdf) ⭐ 8,831 | 🐛 36 | 🌐 C++ | 📅 2026-04-17, [\[Code\]](https://github.com/sebastianstarke/AI4Animation/tree/master/AI4Animation/SIGGRAPH_2020) ⭐ 8,831 | 🐛 36 | 🌐 C++ | 📅 2026-04-17

* Human Motion Diffusion as a Generative Prior, *ICLR'24*, [\[Paper\]](https://arxiv.org/abs/2303.01418), [\[Project\]](https://priormdm.github.io/priorMDM-page/), [\[Code\]](https://github.com/priorMDM/priorMDM) ⭐ 524 | 🐛 6 | 🌐 Python | 📅 2026-04-21

* Inter-X: Towards Versatile Human-Human Interaction Analysis, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2312.16051), [\[Project\]](https://liangxuy.github.io/inter-x/), [\[Code\&Data\]](https://github.com/liangxuy/Inter-X) ⭐ 233 | 🐛 12 | 🌐 Python | 📅 2024-08-11

* Duolando: Follower GPT with Off-Policy Reinforcement Learning for Dance Accompaniment, *ICLR'24*, [\[Paper\]](https://arxiv.org/abs/2403.18811), [\[Project\]](https://lisiyao21.github.io/projects/Duolando/), [\[Code\]](https://github.com/lisiyao21/Duolando) ⭐ 113 | 🐛 5 | 🌐 Python | 📅 2024-03-28, [\[Data\]](https://drive.google.com/file/d/1sWc1MeRhRa9LoxarsJVFvt5vxsRk-F_M/view)

* InterControl: Zero-shot Human Interaction Generation by Controlling Every Joint, *NeurIPS'24*, [\[Paper\]](https://arxiv.org/abs/2311.15864), [\[Code\]](https://github.com/zhenzhiwang/intercontrol) ⭐ 83 | 🐛 2 | 🌐 Python | 📅 2025-02-20

* ActFormer: A GAN-based Transformer towards General Action-Conditioned 3D Human Motion Generation, *ICCV'23*, [\[Paper\]](https://arxiv.org/abs/2203.07706), [\[Project\]](https://liangxuy.github.io/actformer/), [\[Code\]](https://github.com/Szy-Young/actformer) ⭐ 67 | 🐛 3 | 🌐 Python | 📅 2024-05-14

* in2IN: Leveraging individual Information to Generate Human INteractions, *CVPRW'24*, [\[Paper\]](https://arxiv.org/abs/2404.09988), [\[Project\]](https://pabloruizponce.github.io/in2IN/), [\[Code\]](https://github.com/pabloruizponce/in2IN) ⭐ 61 | 🐛 2 | 🌐 Python | 📅 2024-07-29

* InterMask: 3D Human Interaction Generation via Collaborative Masked Modeling, *ICLR'25*, [\[Paper\]](https://arxiv.org/abs/2410.10010), [\[Project\]](https://gohar-malik.github.io/intermask/), [\[Code\]](https://github.com/gohar-malik/intermask) ⭐ 53 | 🐛 0 | 🌐 Python | 📅 2025-09-08

* TIMotion: Temporal and Interactive Framework for Efficient Human-Human Motion Generation, *CVPR'25*, [\[Paper\]](https://arxiv.org/abs/2408.17135), [\[Project\]](https://aigc-explorer.github.io/TIMotion-page/), [\[Code\]](https://github.com/AIGC-Explorer/TIMotion) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2026-01-15

* Ponimator: Unfolding Interactive Pose for Versatile Human-human Interaction Animation, *ICCV'25*, [\[Paper\]](https://arxiv.org/abs/2510.14976), [\[Project\]](https://stevenlsw.github.io/ponimator/), [\[Code\]](https://github.com/stevenlsw/ponimator) ⭐ 40 | 🐛 2 | 🌐 Python | 📅 2025-12-10

* Unified Number-Free Text-to-Motion Generation Via Flow Matching, *CVPR'26*, [\[Paper\]](https://arxiv.org/abs/2603.27040), [\[Project\]](https://githubhgh.github.io/umf/), [\[Code\]](https://github.com/Githubhgh/UMF_CVPR/tree/main) ⭐ 35 | 🐛 3 | 🌐 Python | 📅 2026-06-06

* Diffusion Forcing for Multi-Agent Interaction Sequence Modeling, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2512.17900), [\[Project\]](https://von31.github.io/MAGNet/), [\[Code\]](https://github.com/Von31/MAGNet-code) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2026-05-04

* MixerMDM: Learnable Composition of Human Motion Diffusion Models, *CVPR'25*, [\[Paper\]](https://arxiv.org/abs/2504.01019), [\[Project\]](https://pabloruizponce.com/papers/MixerMDM), [\[Code\]](https://github.com/pabloruizponce/MixerMDM) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2026-06-01

* InterMoE: Individual-Specific 3D Human Interaction Generation via Dynamic Temporal-Selective MoE, *AAAI'26*, [\[Paper\]](https://arxiv.org/abs/2511.13488), [\[Code\]](https://github.com/Lighten001/InterMoE) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2026-04-06

* ContactGen: Contact-Guided Interactive 3D Human Generation for Partners, *AAAI'24*, [\[Paper\]](https://arxiv.org/abs/2401.17212), [\[Project\]](https://dongjunku.github.io/contactgen/), [\[Code\]](https://github.com/dongjunKu/ContactGen/) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2024-10-11

* Stability-Driven Motion Generation for Object-Guided Human-Human Co-Manipulation, *CVPR'26*, [\[Paper\]](https://openaccess.thecvf.com/content/CVPR2026/papers/Xu_Stability-Driven_Motion_Generation_for_Object-Guided_Human-Human_Co-Manipulation_CVPR_2026_paper.pdf), [\[Project\]](http://www.buzhenhuang.com/works/StaCOM.html), [\[Code\]](https://github.com/boycehbz/StaCOM) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2026-06-19

* DuetGen: Music Driven Two-Person Dance Generation via Hierarchical Masked Modeling, *SIGGRAPH'25*, [\[Paper\]](https://arxiv.org/abs/2506.18680), [\[Project\]](https://anindita127.github.io/DuetGen/), [\[Code\]](https://github.com/anindita127/DuetGen) ⭐ 14 | 🐛 2 | 🌐 HTML | 📅 2026-01-19

* Invisible Strings: Revealing Latent Dancer-to-Dancer Interactions with Graph Neural Networks, *ICCC'25*, [\[Paper\]](https://arxiv.org/abs/2503.04816), [\[Code\]](https://github.com/humanai-foundation/ChoreoAI/tree/main/ChoreoAI_Duet_ChorAIgraphy_Luis_Zerkowski) ⭐ 5 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2024-09-27

* PhysiGen: Integrating Collision-Aware Physical Constraints for High-Fidelity Human-Human Interaction Generation, *ICASSP'26*, [\[Paper\]](https://arxiv.org/abs/2605.00517), [\[Code\]](https://github.com/iSEE-Laboratory/PhysiGen) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-05-29

* Social Structure Matters in 3D Human-Human Interaction Generation, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2606.24255), [\[Code\]](https://github.com/EngineeringAI-LAB/SocialStructureHHI) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-06-24

* MIME: Multimodal Interactive Motion Encoder, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2607.22702)

* GNOCHI: Generative Neural mOdel for Close Human-Human Interactions, *SCA'26*, [\[Paper\]](https://arxiv.org/abs/2607.10408)

* HiTMM: Generative Temporal Masked Modeling of Human Interactive Motions, *arXiv'26*, [\[Paper\]](https://yunliansun.github.io/papers/HiTMM.pdf), [\[Project\]](https://jiaozicheng.github.io/HiTMM/)

* HINT: Hierarchical Interaction Modeling for Autoregressive Multi-Human Motion Generation, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2601.20383)

* Interact2Ar: Full-Body Human-Human Interaction Generation via Autoregressive Diffusion Models, *CVPR'26*, [\[Paper\]](https://arxiv.org/abs/2512.19692), [\[Project\]](https://www.pabloruizponce.com/papers/Interact2Ar)

* Disentangled Hierarchical VAE for 3D Human-Human Interaction Generation, *ICLR'26 Submission*, [\[Paper\]](https://openreview.net/attachment?id=53eIDko6N5\&name=pdf)

* CODA: Commonsense-Driven Autoregressive Human Interaction Generation, *ICLR'26 Submission*, [\[Paper\]](https://openreview.net/attachment?id=KH32pA5Mr5\&name=pdf)

* Fine-grained text-driven dual-human motion generation via dynamic hierarchical interaction, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2510.08260)

* InterAct: A Large-Scale Dataset of Dynamic, Expressive and Interactive Activities between Two People in Daily Scenarios, *SCA'25*, [\[Paper\]](https://arxiv.org/abs/2509.05747), [\[Project\]](https://hku-cg.github.io/interact/)

* Towards Immersive Human-X Interaction: A Real-Time Framework for Physically Plausible Motion Synthesis, *ICCV'25*, [\[Paper\]](https://arxiv.org/abs/2508.02106), [\[Project\]](https://humanx-interaction.github.io/)

* MDD: A Dataset for Text-and-Music Conditioned Duet Dance Generation, *ICCV'25*, [\[Paper\]](https://arxiv.org/abs/2508.16911), [\[Project\]](https://gprerit96.github.io/mdd-page/)

* PhysiInter: Integrating Physical Mapping for High-Fidelity Human Interaction Generation, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2506.07456)

* InterMamba: Efficient Human-Human Interaction Generation with Adaptive Spatio-Temporal Mamba, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2506.03084)

* Dyadic Mamba: Long-term Dyadic Human Motion Synthesis, *CVPRW'25*, [\[Paper\]](https://arxiv.org/abs/2505.09827)

* Leader and Follower: Interactive Motion Generation under Trajectory Constraints, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2502.11563)

* InterDance: Reactive 3D Dance Generation with Realistic Duet Interactions, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2412.16982), [\[Project\]](https://inter-dance.github.io/)

* Two-in-One: Unified Multi-Person Interactive Motion Generation by Latent Diffusion Transformer, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2412.16670)

* It Takes Two: Real-time Co-Speech Two-person's Interaction Generation via Reactive Auto-regressive Diffusion Model, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2412.02419)

* COLLAGE: Collaborative Human-Agent Interaction Generation using Hierarchical Latent Diffusion and Language Models, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2409.20502)

* Towards Open Domain Text-Driven Synthesis of Multi-Person Motions, *ECCV'24*, [\[Paper\]](https://arxiv.org/abs/2405.18483), [\[Project\]](https://shanmy.github.io/Multi-Motion/)

* InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions, *IJCV'24*, [\[Paper\]](https://arxiv.org/abs/2304.05684), [\[Project\]](https://tr3e.github.io/intergen-page/), [\[Code\&Data\]](https://drive.google.com/drive/folders/1oyozJ4E7Sqgsr7Q747Na35tWo5CjNYk3)

### Reaction Generation

* Inter-X: Towards Versatile Human-Human Interaction Analysis, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2312.16051), [\[Project\]](https://liangxuy.github.io/inter-x/), [\[Code\&Data\]](https://github.com/liangxuy/Inter-X) ⭐ 233 | 🐛 12 | 🌐 Python | 📅 2024-08-11

* ReGenNet: Towards Human Action-Reaction Synthesis, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2403.11882), [\[Project\]](https://liangxuy.github.io/ReGenNet/), [\[Code\]](https://github.com/liangxuy/ReGenNet) ⭐ 72 | 🐛 3 | 🌐 Python | 📅 2024-09-23

* Ready-to-React: Online Reaction Policy for Two-Character Interaction Generation, *ICLR'25*, [\[Paper\]](https://arxiv.org/abs/2502.20370), [\[Project\]](https://zju3dv.github.io/ready_to_react/), [\[Code\]](https://github.com/zju3dv/ready_to_react) ⭐ 55 | 🐛 0 | 🌐 Python | 📅 2025-03-13

* Role-aware Interaction Generation from Textual Description, *ICCV'23*, [\[Paper\]](https://openaccess.thecvf.com/content/ICCV2023/html/Tanaka_Role-Aware_Interaction_Generation_from_Textual_Description_ICCV_2023_paper.html), [\[Code\]](https://github.com/line/Human-Interaction-Generation) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2023-10-20

* ReMoGen: Real-time Human Interaction-to-Reaction Generation via Modular Learning from Diverse Data, *CVPR'26*, [\[Paper\]](https://arxiv.org/abs/2604.01082), [\[Project\]](https://4dvlab.github.io/project_page/remogen/)

* EgoReAct: Egocentric Video-Driven 3D Human Reaction Generation, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2512.22808), [\[Project\]](https://frank-zy-dou.github.io/projects/EgoReAct/index.html)

* ReactMotion: Generating Reactive Listener Motions from Speaker Utterance, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2603.15083), [\[Project\]](https://reactmotion.github.io/)

* ARMFlow: AutoRegressive MeanFlow for Online 3D Human Reaction Generation, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2512.16234)

* ReactionMamba: Generating Short & Long Human Reaction Sequences, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2512.00208)

* Uni-Inter: Unifying 3D Human Motion Synthesis Across Diverse Interaction Contexts, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2511.13032)

* MoReact: Generating Reactive Motion from Textual Descriptions, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2509.23911)

* Reactffusion: Physical Contact-guided Diffusion Model for Reaction Generation, *arXiv'25*, [\[Paper\]](https://dl.acm.org/doi/pdf/10.1145/3746027.3755058)

* Real-time and Controllable Reactive Motion Synthesis via Intention Guidance, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2507.09704)

* MARRS: Masked Autoregressive Unit-based Reaction Synthesis, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2505.11334)

* E-React: Towards Emotionally Controlled Synthesis of Human Reactions, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2508.06093), [\[Project\]](https://ereact.github.io/)

* ReactDance: Hierarchical Representation for High-Fidelity and Coherent Long-Form Reactive Dance Generation, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2505.05589)

* HERO: Human Reaction Generation from Videos, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2503.08270), [\[Project\]](https://jackyu6.github.io/HERO/)

* Think-Then-React: Towards Unconstrained Human Action-to-Reaction Generation, *ICLR'25*, [\[Paper\]](https://arxiv.org/abs/2503.16451), [\[Project\]](https://think-then-react.github.io/)

* Interactive Humanoid: Online Full-Body Motion Reaction Synthesis with Social Affordance Canonicalization and Forecasting, *3DV'25*, [\[Paper\]](https://arxiv.org/abs/2312.08983), [\[Project\]](https://yunzeliu.github.io/iHuman/)

* SocialGen: Modeling Multi-Human Social Interaction with Language Models, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2503.22906), [\[Project\]](https://socialgenx.github.io/)

* ARFlow: Human Action-Reaction Flow Matching with Physical Guidance, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2503.16973), [\[Project\]](https://arflow2025.github.io/)

* PhysReaction: Physically Plausible Real-Time Humanoid Reaction Synthesis via Forward Dynamics Guided 4D Imitation, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2404.01081), [\[Project\]](https://yunzeliu.github.io/PhysReaction/)

* ReMoS: 3D Motion-Conditioned Reaction Synthesis for Two-Person Interactions, *ECCV'24*, [\[Paper\]](https://arxiv.org/abs/2311.17057), [\[Project\]](https://vcai.mpi-inf.mpg.de/projects/remos/)

* Interaction Transformer for Human Reaction Generation, *TMM'23*, [\[Paper\]](https://arxiv.org/abs/2207.01685)

### HHI Reconstruction

* Hi4D: 4D Instance Segmentation of Close Human Interaction, *CVPR'23*, [\[Paper\]](https://arxiv.org/abs/2303.15380v1), [\[Project\]](https://yifeiyin04.github.io/Hi4D/), [\[Code\&Data\]](https://github.com/yifeiyin04/Hi4D) ⭐ 100 | 🐛 1 | 🌐 Python | 📅 2024-05-27

* MultiPhys: Multi-Person Physics-aware 3D Motion Estimation, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2404.11987), [\[Project\]](http://www.iri.upc.edu/people/nugrinovic/multiphys/), [\[Code\]](https://github.com/nicolasugrinovic/multiphys) ⭐ 84 | 🐛 3 | 🌐 Python | 📅 2025-03-24

* Multi-Person Extreme Motion Prediction, *CVPR'22*, [\[Paper\]](https://arxiv.org/abs/2105.08825), [\[Project\]](https://team.inria.fr/robotlearn/multi-person-extreme-motion-prediction/), [\[Code\]](https://github.com/GUO-W/MultiMotion) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2022-03-10

* Closely Interactive Human Reconstruction with Proxemics and Physics-Guided Adaption, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2404.11291), [\[Code\]](https://github.com/boycehbz/HumanInteraction) ⭐ 44 | 🐛 6 | 🌐 Python | 📅 2025-08-03

* Reconstructing Close Human Interactions from Multiple Views, *SIGGRAPH Asia'23*, [\[Paper\]](https://arxiv.org/abs/2401.16173), [\[Code\]](https://github.com/zju3dv/CloseMoCap) ⭐ 40 | 🐛 3 | 📅 2024-01-29

* MAMMA: Markerless & Automatic Multi-Person Motion Action Capture, *CVPR'26*, [\[Paper\]](https://arxiv.org/abs/2506.13040)

* Reconstructing Close Human Interaction with Appearance and Proxemics Reasoning, *CVPR'25*, [\[Paper\]](https://www.buzhenhuang.com/publications/papers/CVPR2025-CloseApp.pdf)

* Harmony4D: A Video Dataset for In-The-Wild Close Human Interactions, *NeurIPS'24*, [\[Paper\]](https://arxiv.org/abs/2410.20294), [\[Project\]](https://jyuntins.github.io/harmony4d/), [\[Data\]](https://huggingface.co/datasets/Jyun-Ting/Harmony4D/tree/main)

* AvatarPose: Avatar-guided 3D Pose Estimation of Close Human Interaction from Sparse Multi-view Videos, *ECCV'24*, [\[Paper\]](https://arxiv.org/abs/2408.02110), [\[Project\]](https://feichilu.github.io/AvatarPose/)

* Capturing Closely Interacted Two-Person Motions with Reaction Priors, *CVPR'24*, [\[Paper\]](https://netease-gameai.github.io/Dual-Human/static/assets/CVPR2024_DualHuman.pdf), [\[Project\]](https://netease-gameai.github.io/Dual-Human/)

* Pose Priors from Language Models, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2405.03689)

### HHI Detection

* Inter-X: Towards Versatile Human-Human Interaction Analysis, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2312.16051), [\[Project\]](https://liangxuy.github.io/inter-x/), [\[Code\&Data\]](https://github.com/liangxuy/Inter-X) ⭐ 233 | 🐛 12 | 🌐 Python | 📅 2024-08-11

* Nonverbal Interaction Detection, *ECCV'24*, [\[Paper\]](https://arxiv.org/abs/2407.08133), [\[Code\]](https://github.com/weijianan1/NVI) ⭐ 31 | 🐛 2 | 🌐 Python | 📅 2024-10-30

* SportsHHI: A Dataset for Human-Human Interaction Detection in Sports Videos, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2404.04565), [\[Code\]](https://github.com/MCG-NJU/SportsHHI) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2024-05-21

* Multiple Human Motion Understanding, *AAAI'26*, [\[Paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/37556)

* IGFormer: Interaction Graph Transformer for Skeleton-based Human Interaction Recognition, *ECCV'22*, [\[Paper\]](https://arxiv.org/abs/2207.12100)

* Human-to-Human Interaction Detection, *arXiv'23*, [\[Paper\]](https://arxiv.org/abs/2307.00464)

### HHI Datasets

* Inter-X: Towards Versatile Human-Human Interaction Analysis, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2312.16051), [\[Project\]](https://liangxuy.github.io/inter-x/), [\[Code\&Data\]](https://github.com/liangxuy/Inter-X) ⭐ 233 | 🐛 12 | 🌐 Python | 📅 2024-08-11

* Hi4D: 4D Instance Segmentation of Close Human Interaction, *CVPR'23*, [\[Paper\]](https://arxiv.org/abs/2303.15380v1), [\[Project\]](https://yifeiyin04.github.io/Hi4D/), [\[Code\&Data\]](https://github.com/yifeiyin04/Hi4D) ⭐ 100 | 🐛 1 | 🌐 Python | 📅 2024-05-27

* ActFormer: A GAN-based Transformer towards General Action-Conditioned 3D Human Motion Generation, *ICCV'23*, [\[Paper\]](https://arxiv.org/abs/2203.07706), [\[Project\]](https://liangxuy.github.io/actformer/), [\[Code\]](https://github.com/Szy-Young/actformer) ⭐ 67 | 🐛 3 | 🌐 Python | 📅 2024-05-14

* Multi-Person Extreme Motion Prediction, *CVPR'22*, [\[Paper\]](https://arxiv.org/abs/2105.08825), [\[Project\]](https://team.inria.fr/robotlearn/multi-person-extreme-motion-prediction/), [\[Code\]](https://github.com/GUO-W/MultiMotion) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2022-03-10

* SportsHHI: A Dataset for Human-Human Interaction Detection in Sports Videos, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2404.04565), [\[Code\]](https://github.com/MCG-NJU/SportsHHI) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2024-05-21

* HHI-Assist: A Dataset and Benchmark of Human-Human Interaction in Physical Assistance Scenario, *RA-L'25*, [\[Paper\]](https://arxiv.org/abs/2509.10096), [\[Project\]](https://sites.google.com/view/hhi-assist/home), [\[Code\]](https://github.com/vita-epfl/HHI-Assist) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-06-30

* InterAct: A Large-Scale Dataset of Dynamic, Expressive and Interactive Activities between Two People in Daily Scenarios, *SCA'25*, [\[Paper\]](https://arxiv.org/abs/2509.05747), [\[Project\]](https://hku-cg.github.io/interact/)

* InterDance: Reactive 3D Dance Generation with Realistic Duet Interactions, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2412.16982), [\[Project\]](https://inter-dance.github.io/)

* ReMoS: 3D Motion-Conditioned Reaction Synthesis for Two-Person Interactions, *ECCV'24*, [\[Paper\]](https://arxiv.org/abs/2311.17057), [\[Project\]](https://vcai.mpi-inf.mpg.de/projects/remos/)

* InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions, *IJCV'24*, [\[Paper\]](https://arxiv.org/abs/2304.05684), [\[Project\]](https://tr3e.github.io/intergen-page/), [\[Code\&Data\]](https://drive.google.com/drive/folders/1oyozJ4E7Sqgsr7Q747Na35tWo5CjNYk3)

* Three-dimensional Reconstruction of Human Interactions, *CVPR'20*, [\[Paper\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fieraru_Three-Dimensional_Reconstruction_of_Human_Interactions_CVPR_2020_paper.pdf), [\[Project\]](https://ci3d.imar.ro/home)

### Group Interaction

* Stochastic Multi-Person 3D Motion Forecasting, *ICLR'23*, [\[Paper\]](https://arxiv.org/abs/2306.05421), [\[Project\]](https://sirui-xu.github.io/DuMMF/), [\[Code\]](https://github.com/Sirui-Xu/DuMMF) ⭐ 54 | 🐛 3 | 🌐 Python | 📅 2023-09-01

* Joint-Relation Transformer for Multi-Person Motion Prediction, *ICCV'23*, [\[Paper\]](https://arxiv.org/abs/2308.04808), [\[Code\]](https://github.com/MediaBrain-SJTU/JRTransformer) ⭐ 28 | 🐛 3 | 🌐 Python | 📅 2023-09-20

* Multi-Person Interaction Generation from Two-Person Motion Priors, *SIGGRAPH'25*, [\[Paper\]](https://arxiv.org/abs/2505.17860), [\[Project\]](https://wenningxu.github.io/multicharacter/), [\[Code\]](https://github.com/wenningxu/multi-person-interaction) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-02-12

* PINO: Person-Interaction Noise Optimization for Long-Duration and Customizable Motion Generation of Arbitrary-Sized Groups, *ICCV'25*, [\[Paper\]](https://arxiv.org/abs/2507.19292), [\[Project\]](https://sinc865.github.io/pino/), [\[Code\]](https://github.com/sinc865/PINO) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2025-10-14

* Unified Number-Free Text-to-Motion Generation Via Flow Matching, *CVPR'26*, [\[Paper\]](https://arxiv.org/abs/2603.27040), [\[Project\]](https://githubhgh.github.io/umf/)

* Large-Scale Multi-Character Interaction Synthesis, *SIGGRAPH'25*, [\[Paper\]](https://arxiv.org/abs/2505.14087), [\[Project\]](https://hubertshum.com/pbl_siggraph2025interaction.htm)

* SocialGen: Modeling Multi-Human Social Interaction with Language Models, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2503.22906), [\[Project\]](https://socialgenx.github.io/)

* Towards Open Domain Text-Driven Synthesis of Multi-Person Motions, *ECCV'24*, [\[Paper\]](https://arxiv.org/abs/2405.18483), [\[Project\]](https://shanmy.github.io/Multi-Motion/)

* Music-Driven Group Choreography, *CVPR'23*, [\[Paper\]](https://arxiv.org/abs/2303.12337), [\[Project\]](https://aioz-ai.github.io/AIOZ-GDANCE/)

### Multi-Human and Objects

* CORE4D: A 4D Human-Object-Human Interaction Dataset for Collaborative Object REarrangement, *arXiv'24*, [\[Paper\]](https://arxiv.org/abs/2406.19353), [\[Project\]](https://core4d.github.io/), [\[Code\]](https://github.com/leolyliu/CORE4D-Instructions) ⭐ 122 | 🐛 5 | 🌐 Python | 📅 2025-07-01

* SynAgent: Generalizable Cooperative Humanoid Manipulation via Solo-to-Cooperative Agent Synergy, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2604.18557v2), [\[Project\]](https://yw0208.github.io/synagent/), [\[Code\]](https://github.com/yw0208/SynAgent) ⭐ 4 | 🐛 1 | 📅 2026-04-16

* Perceiving and Acting in First-Person: A Dataset and Benchmark for Egocentric Human-Object-Human Interactions, *ICCV'25*, [\[Paper\]](https://arxiv.org/abs/2508.04681), [\[Project\]](https://liangxuy.github.io/InterVLA/)

* HOI-M3: Capture Multiple Humans and Objects Interaction within Contextual Environment, *CVPR'24*, [\[Paper\]](https://arxiv.org/abs/2404.00299), [\[Project\]](https://juzezhang.github.io/HOIM3_ProjectPage/)

### Interactive Humanoid

* Learning Whole-Body Human-Humanoid Interaction from Human-Human Demonstrations, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2601.09518)

* SymBridge: A Human-in-the-Loop Cyber-Physical Interactive System for Adaptive Human-Robot Symbiosis, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2502.07358)

* It Takes Two: Learning Interactive Whole-Body Control Between Humanoid Robots, *arXiv'25*, [\[Paper\]](https://arxiv.org/abs/2510.10206), [\[Code\]](https://github.com/ZuhongLIU/Harmanoid) ⭐ 13 | 🐛 1 | 📅 2025-10-11

### Other Applications

* HelloWorld: Enabling Socially Interactive Characters in Video World Models, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2608.05070)

* SocialDirector: Training-Free Social Interaction Control for Multi-Person Video Generation, *arXiv'26*, [\[Paper\]](https://arxiv.org/abs/2605.10079)

* InterEdit: Navigating Text-Guided 3D Dyadic Human Motion Editing, *ECCV'26*, [\[Paper\]](https://arxiv.org/abs/2603.13082), [\[Code\]](https://github.com/YNG916/InterEdit) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2026-04-17

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
