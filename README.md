
# Camouflaged Object Detection <a href="https://github.com/sindresorhus/awesome"><img src="https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667" alt="Awesome" style="max-width: 100%;"></a>

A curated list of awesome resources for camouflaged/concealed object detection (COD). We will keep updating it.

:heavy_exclamation_mark: [04/2023] Update CVPR2023 papers for COD and CIS.


--------------------------------------------------------------------------------------

<!--TOC-->

## Content:
<!-- - [Overview](#Overview) -->
- [Camouflaged Object Detection (COD)](#COD)
- [Video Camouflaged Object Detection (VCOD)](#VCOD)
- [Camouflaged Instance Segmentation (CIS)](#CIS)
- [Other Related](#Other-Related)
- [Datasets](#Datasets)
- [Appendix](#Appendix)

--------------------------------------------------------------------------------------



## COD 

<!--Transformer for COD:
  1) [COD] Boosting COD with Boosting Camouflaged Object Detection with Dual-Task Interactive Transformer, ICPR
  2) [COD] High-resolution Iterative Feedback Network for Camouflaged Object Detection, arXiv
  3) [COD] Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection, ICCV21
  4) [CIS] OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers, ECCV22
  5) [COD] Generative Transformer for Accurate and Reliable Salient Object Detection, arXiv
-->


### Preprint

| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| --     | arXiv | Advances in Deep Concealed Scene Understanding   <br> <sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Peng Xu, Ming-Ming Cheng, Christos Sakaridis, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2304.11234)/[Project](https://github.com/DengPingFan/CSU)
| --     | arXiv | SAM Fails to Segment Anything? -- SAM-Adapter: Adapting SAM in Underperformed Scenes: Camouflage, Shadow, and More  <br> <sup><sub>*Tianrun Chen, Lanyun Zhu, Chaotao Ding, Runlong Cao, Yan Wang, Zejian Li, Lingyun Sun, Papa Mao, Ying Zang*</sub></sup> | [Paper](https://arxiv.org/abs/2304.09148)/Code
| --     | arXiv | DQnet: Cross-Model Detail Querying for Camouflaged Object Detection <br> <sup><sub>*Wei Sun, Chengao Liu, Linyan Zhang, Yu Li, Pengxu Wei, Chang Liu, Jialing Zou, Jianbin Jiao, Qixiang Ye*</sub></sup> | [Paper](https://arxiv.org/abs/2212.08296)/Code
| --     | arXiv | CamoFormer: Masked Separable Attention for Camouflaged Object Detection   <br> <sup><sub>*Bowen Yin, Xuying Zhang, Qibin Hou, Bo-Yuan Sun, Deng-Ping Fan, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2212.06570)/Code
| --     | arXiv | Source-free Depth for Object Pop-out  <br> <sup><sub>*Zongwei Wu, Danda Pani Paudel, Deng-Ping Fan, Jingjing Wang, Shuo Wang, Cedric Demonceaux, Radu Timofte, Luc Van Gool*</sub></sup>  | [Paper](https://arxiv.org/abs/2212.05370)/Code
| --     | arXiv | Boundary-aware Camouflaged Object Detection via Deformable Point Sampling  <br> <sup><sub>*Minhyeok Lee, Suhwan Cho, Chaewon Park, Dogyoon Lee, Jungho Lee, Sangyoun Lee*</sub></sup>  | [Paper](https://arxiv.org/abs/2211.12048)/Code
|   --   |  arXiv   | Transformer transforms salient object detection and camouflaged object detection <br> <sup><sub>*Yuxin Mao, Jing Zhang, Yuchao Dai, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2104.10127)/[Code](https://github.com/fupiao1998/TrasformerSOD)
|   --   |  arXiv   | Exploring Depth Contribution for Camouflaged Object Detection <br> <sup><sub>*Mochu Xiang, Jing Zhang, Yunqiu Lv, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2106.13217v3)/Code
|   --   |  arXiv   | Towards Accurate Camouflaged Object Detection with Mixture Convolution and Interactive Fusion <br> <sup><sub>*Bo Dong, Mingchen Zhuge, Yongxiong Wang, Hongbo Bi, Geng Chen*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.05687.pdf)/[Code](https://github.com/BigHeartDB/MCIFNet)  
|   --   |  arXiv   | Boundary-Aware Segmentation Network for Mobile and Web Applications <br> <sup><sub>*Xuebin Qin, Deng-Ping Fan, Chenyang Huang, et al.*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.04704.pdf)/[Code](https://github.com/xuebinqin/BASNet) 



### 2023


| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2023  | CVPR | Feature Shrinkage Pyramid for Camouflaged Object Detection with Transformers  <br> <sup><sub>*Zhou Huang, Hang Dai, Tian-Zhu Xiang, Shuo Wang, Huai-Xin Chen, Jie Qin, and Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.14816)/[Code](https://github.com/ZhouHuang23/FSPNet)
| 2023  | CVPR | Camouflaged Object Detection with Feature Decomposition and Edge Reconstruction   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | Paper/[Code](https://github.com/ChunmingHe/FEDER)
| 2023  | CVPR | Explicit Visual Prompting for Low-Level Structure Segmentations  <br> <sup><sub>*Weihuang Liu, Xi Shen, Chi-Man Pun, Xiaodong Cun*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.10883)/[Code](https://github.com/NiFangBaAGe/Explicit-Visual-Prompt)
| 2023  | CVPR | Indiscernible Object Counting in Underwater Scenes   <br> <sup><sub>*Guolei Sun, Zhaochong An, Yun Liu, Ce Liu, Christos Sakaridis, Deng-Ping Fan, Luc Van Gool*</sub></sup>  | Paper/[Code](https://github.com/GuoleiSun/Indiscernible-Object-Counting)
| 2023  | AAAI | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations  <br> <sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.14083)/[Code](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations)
| 2023  |  AAAI   | High-resolution Iterative Feedback Network for Camouflaged Object Detection <br> <sup><sub>*Xiaobin Hu, Deng-Ping Fan, Xuebin Qin, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2203.11624)/[Code](https://github.com/HUuxiaobin/HitNet) 
| 2023 | WACV | MFFN: Multi-view Feature Fusion Network for Camouflaged Object Detection   <br> <sup><sub>*Dehua Zheng, Xiaochen Zheng, Laurence T. Yang, Yuan Gao, Chenlu Zhu, Yiheng Ruan*</sub></sup> | [Paper](https://arxiv.org/abs/2210.06361)/[Code](https://github.com/dwardzheng/MFFN_COD)
| --  | -- | -- | -- |
| 2023 | TCSVT | MSCAF-Net: A General Framework for Camouflaged Object Detection via Learning Multi-Scale Context-Aware Features  <br> <sup><sub>*Yu Liu; Haihang Li; Juan Cheng; Xun Chen*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10045692)/[Code](https://github.com/yuliu316316/MSCAF-COD) 
| 2023 | TCSVT | Go Closer To See Better: Camouflaged Object Detection via Object Area Amplification and Figure-ground Conversion  <br> <sup><sub>*Haozhe Xing; Yan Wang; Xujun Wei; Hao Tang; Shuyong Gao; Wenqiang Zhang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10065514)/[Code](https://github.com/Haozhe-Xing/SARNet)
| 2023 | TCSVT | Towards Deeper Understanding of Camouflaged Object Detection `CVPR21 (LSR) extension` <br> <sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, Nick Barnes, Deng-Ping Fan*</sub></sup> | [Paper](https://arxiv.org/abs/2205.11333)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)





### 2022 

| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2022   |  NeurIPS | Exploring Figure-Ground Assignment Mechanism in Perceptual Organization   <br> <sup><sub>*Wei Zhai, Yang Cao, Jing Zhang, Zheng-Jun Zha*</sub></sup> | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6cc31b44d88dce8380d36e81485cd07f-Abstract-Conference.html)/Code
|   2022   |   MM     | PreyNet: Preying on camouflaged objects <br> <sup><sub>*M Zhang, S Xu, Yongri Piao, D Shi, S Lin, H Lu*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548178)/[Code](https://github.com/sxu1997/PreyNet)
|   2022   |  IJCAI   | Boundary-Guided Camouflaged Object Detection <br> <sup><sub>*Yujia Sun, Shuo Wang, Chenglizhao Chen, Tian-Zhu Xiang*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2022/186)/[Code](https://github.com/thograce/BGNet)
|   2022   |   CVPR   | Segment, Magnify and Reiterate: Detecting Camouflaged Objects the Hard Way <br> <sup><sub>*Qi Jia, S. Yao, Yu Liu, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Jia_Segment_Magnify_and_Reiterate_Detecting_Camouflaged_Objects_the_Hard_Way_CVPR_2022_paper.pdf)/[Code](https://github.com/dlut-dimt/SegMaR) 
|   2022   |   CVPR   | Detecting Camouflaged Object in Frequency Domain <br> <sup><sub>*Yijie Zhong, Bo Li, Lv Tang, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Detecting_Camouflaged_Object_in_Frequency_Domain_CVPR_2022_paper.pdf)/Code
|   2022   |   CVPR   | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup> | [Paper](https://arxiv.org/abs/2203.02688)/[Code](https://github.com/lartpang/ZoomNet) |
|   2022   |  AAAI    | I can find you! Boundary-guided Separated Attention Network for Camouflaged Object Detection <br><sup><sub>*Hongwei Zhu, Peng Li, Haoran Xie, Mingqiang Wei, et al.*</sub></sup> | [Paper](https://www.aaai.org/AAAI22Papers/AAAI-6565.ZhuH.pdf)/[Code](https://github.com/WolfberryCoke/BSA-Net) | 
|   2022   |  WACV    | Modeling Aleatoric Uncertainty for Camouflaged Object Detection <br> <sup><sub>*Jiawei Liu, Jing Zhang, Nick Barnes*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Liu_Modeling_Aleatoric_Uncertainty_for_Camouflaged_Object_Detection_WACV_2022_paper.pdf)/[Code](https://github.com/Carlisle-Liu/OCENet)
|  2022    |  ICME   | Finding the Achilles Heel: Progressive Identification Network for Camouflaged Object Detection  <br> <sup><sub>*Mu-Chun Chou, Hung-Jen Chen, Hong-Han Shuai*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9859854)/[Code](https://github.com/michael861227/PINet)
| --  | -- | -- | -- | 
|   2022   |   PAMI   | **Concealed Object Detection** `COD10K`                       <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Ming-Ming Cheng, Ling Shao*</sub></sup>                             | [Paper](https://arxiv.org/abs/2102.10274)/[Code](https://github.com/GewelsJI/SINet-V2)                                                   |
|   2022   |  TIP | Feature Aggregation and Propagation Network for Camouflaged Object Detection <br> <sup><sub>*Tao Zhou, Yi Zhou, Chen Gong, Jian Yang, Yu Zhang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9940173)/[Code](https://github.com/taozh2017/FAPNet)
|   2022   |  TIP | FindNet: Can You Find Me? Boundary-and-Texture Enhancement Network for Camouflaged Object Detection  `AAAI22 (BSANet) extension` <br> <sup><sub>*Peng Li, Xuefeng Yan, Hongwei Zhu, Mingqiang Wei, Xiao-Ping Zhang, Jing Qin*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9923635/)/Code
|   2022   |  TIP | MGL: Mutual Graph Learning for Camouflaged Object Detection `CVPR2021 extension`   <br><sup><sub>*Qiang Zhai; Xin Li; Fan Yang; Zhicheng Jiao; Ping Luo; Hong Cheng; Zicheng Liu*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9962828)/[Code](https://github.com/fanyang587/MGL) 
|   2022   | MIR  | Deep Gradient Learning for Efficient Camouflaged Object Detection <br> <sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Yu-Cheng Chou, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2205.12853)/[Code](https://github.com/GewelsJI/DGNet)
|   2022   | TCSVT | Camouflaged Object Detection via Context-aware Cross-level Fusion `C2FNet Extension`  <br> <sup><sub>*Geng Chen, Si-Jie Liu, Yu-Jia Sun, Ge-Peng Ji, Ya-Feng Wu, Tao Zhou*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.13362)/[Code](https://github.com/Ben57882/C2FNet-TSCVT)
|   2022   |  TMM  | Deep Texton-Coherence Network for Camouflaged Object Detection <br> <sup><sub>*Wei Zhai, Yang Cao, HaiYong Xie, Zheng-Jun Zha*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9815160)/Code
|   2022   |  KBS     | Boundary-guided network for camouflage object detection <br> <sup><sub>*Tianyou Chen, Jin Xiao, Xiaoguang Hu, Guofeng Zhang, Shaojie Wang*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705122004294)/[Code](https://github.com/clelouch/BgNet)
|   2022   |  PR      | CubeNet: X-shape connection for camouflaged object detection <br> <sup><sub>*Mingchen Zhuge, Xiankai Lu, Yiyou Guo, Zhihua Cai, Shuhan Chen*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S003132032200125X?dgcid=raven_sd_recommender_email)/[Code](https://github.com/mczhuge/CubeNet)
|   2022   |  PR      | Fast Camouflaged Object Detection via Edge-based Reversible Re-calibration Network <br><sup><sub>*Ge-Peng Ji, Lei Zhu, Mingchen Zhuge, Keren Fu*</sub></sup> | [Paper](https://arxiv.org/abs/2111.03216)/[Code](https://github.com/GewelsJI/ERRNet) 
|   2022   |  TOMM | Frequency-aware Camouflaged Object Detection <br> <sup><sub>*Jiaying Lin, Xin Tan, Ke Xu, Lizhuang Ma, Rynson W.H. Lau*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3545609)/Code 



### 2021

| **Year** | **Pub.** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2021   |   ICCV   | Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection <br><sup><sub>*Fan Yang, Qiang Zhai, Xin Li, Rui Huang, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Uncertainty-Guided_Transformer_Reasoning_for_Camouflaged_Object_Detection_ICCV_2021_paper.pdf)/[Code](https://github.com/fanyang587/UGTR)                                                   |
|   2021   |   CVPR   | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection <br><sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Bowen Liu, Tong Zhang, Yuchao Dai*</sub></sup>                     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Uncertainty-Aware_Joint_Salient_Object_and_Camouflaged_Object_Detection_CVPR_2021_paper.html)/[Code](https://github.com/JingZhang617/Joint_COD_SOD) |
|   2021   |   CVPR   | Simultaneously Localize, Segment and Rank the Camouflaged Objects `NC4K`  <br><sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)                                                   |
|   2021   |   CVPR   | Mutual Graph Learning for Camouflaged Object Detection       <br><sup><sub>*Qiang Zhai, Xin Li, Fan Yang, Chenglizhao Chen, Hong Cheng, Deng-Ping Fan*</sub></sup>                                   | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Mutual_Graph_Learning_for_Camouflaged_Object_Detection_CVPR_2021_paper.pdf)/[Code](https://github.com/fanyang587/MGL)                                                   |
|   2021   |   CVPR   | Camouflaged Object Segmentation with Distraction Mining      <br><sup><sub>*Haiyang Mei, Ge-Peng Ji, Ziqi Wei, Xin Yang, Xiaopeng Wei, Deng-Ping Fan*</sub></sup>                               | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Camouflaged_Object_Segmentation_With_Distraction_Mining_CVPR_2021_paper.pdf)/[Code](https://mhaiyang.github.io/CVPR2021_PFNet/index)                                                   |
|   2021   |  IJCAI   | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup>                                  | [Paper](https://arxiv.org/abs/2105.12555)/[Code](https://github.com/thograce/C2FNet) |
|   2021   |   AAAI   | Inferring Camouflaged Objects by Texture-Aware Interactive Guidance Network <br><sup><sub>*Jinchao Zhu, Xiaoyu Zhang, Shuo Zhang, Junnan Liu*</sub></sup>                                           | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16475)/Code |
| 2021 | AAAI | CamouFinder: Finding Camouflaged Instances in Images `Demo` <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)/[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA)
|   2021   | TIFS | Integrating Part-Object Relationship and Contrast for Camouflaged Object Detection  <br><sup><sub>*Yi Liu, Dingwen Zhang, Qiang Zhang, and Jungong Han*</sub></sup> | [Paper](https://www.researchgate.net/profile/Yi-Liu-35/publication/355923462_Integrating_Part-Object_Relationship_and_Contrast_for_Camouflaged_Object_Detection/links/625cb1221c096a380d0c8f91/Integrating-Part-Object-Relationship-and-Contrast-for-Camouflaged-Object-Detection.pdf)/[Code](https://github.com/liuyi1989/TSPORTNet)
|   2021   | TIE | D2C-Net: A Dual-branch, Dual-guidance and Cross-refine Network for Camouflaged Object Detection <br><sup><sub>*Kang Wang, Hongbo Bi, Yi Zhang, Cong Zhang, Ziqi Liu, Shuang Zheng*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9430677)/[Code](https://github.com/MS-KangWang/COD-D2Net)
|   2021   |  TCSVT   | Deep Texture-Aware Features for Camouflaged Object Detection <br><sup><sub>*Jingjing Ren, Xiaowei Hu, Lei Zhu, Xuemiao Xu, et al.*</sub></sup>  | [Paper](https://arxiv.org/pdf/2102.02996.pdf)/Code 
|  2021   |  TCSVT  | Rethinking Camouflaged Object Detection: Models and Datasets <br><sup><sub>*Hongbo Bi, Cong Zhang, Kang Wang, Jinghui Tong, Feng Zheng*</sub></sup>   | [Paper](https://ieeexplore.ieee.org/document/9598866)/Code
|   2021   |   Access | MirrorNet: Bio-Inspired Camouflaged Object Segmentation <br><sup><sub>*Jinnan Yan, Trung-Nghia Le, Khanh-Duy Nguyen, Minh-Triet Tran, Thanh-Toan Do, Tam V. Nguyen*</sub></sup>  | [Paper](https://arxiv.org/abs/2007.12881)/[Proj](https://sites.google.com/view/ltnghia/research/camo)


### Before 2020 

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2020   |   CVPR   | **Camouflaged Object Detection** `COD10K`                            <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Guolei Sun, Ming-Ming Cheng, Jianbing Shen, Ling Shao*</sub></sup>                                         | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf)/[Code](https://github.com/DengPingFan/SINet)           |
|   2020   |   AAAI   | Deep Camouflage Images                                       <br><sup><sub>*Qing Zhang, Gelin Yin, Yongwei Nie, Wei-Shi Zheng*</sub></sup>                             | [Paper](https://ojs.aaai.org//index.php/AAAI/article/view/6981)/Code |
|   2019   |   CVIU   | Anabranch network for camouflaged object segmentation `CAMO` <br><sup><sub>*Trung-Nghia Le, Tam V. Nguyen, Zhongliang Nie, Minh-Triet Tran, Akihiro Sugimoto*</sub></sup>  | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf)/[Code](https://sites.google.com/view/ltnghia/research/camo)
|   2019   |   SPL    | Detection of People With Camouflage Pattern Via Dense Deconvolution Network `CPD1K` <br><sup><sub>*Yunfei Zheng, Xiongwei Zhang, Feng Wang, Tieyong Cao, Meng Sun, Xiaobing Wang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/8336933)/Code
|   2018   |   TIP    | A Fusion Framework for Camouflaged Moving Foreground Detection in the Wavelet Domain <br><sup><sub>*Shuai Li, Dinei Florencio, Wanqing Li, Yaqin Zhao, Chris Cook*</sub></sup>                                              | [Paper](https://arxiv.org/abs/1804.05984)/Code                                                   |
|   2016   |   IJCV   | <span style="white-space:nowrap;">Partially Camouflaged Object Tracking using Modified Probabilistic Neural Network and Fuzzy Energy based Active Contour&emsp;&emsp;&emsp;</span> <br><sup><sub>*Ajoy Mondal, Susmita Ghosh, Ashish Ghosh*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s11263-016-0959-5)/Code                                                   |



## VCOD

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2022   |   CVPR   | Implicit Motion Handling for Video Camouflaged Object Detection `MoCA-Mask` <br> <sup><sub>*Xuelian Cheng, Huan Xiong, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://dengpingfan.github.io/papers/[2022][CVPR]VCOD_MoCA-Mask.pdf)/[Code](https://github.com/XuelianCheng/SLT-Net)
|   2022   |   CVPR   | A Deeper Dive Into What Deep Spatiotemporal Networks Encode: Quantifying Static vs. Dynamic Information <br> <sup><sub>*Matthew Kowal, Mennatullah Siam, Md Amirul Islam, Neil D. B. Bruce, Richard P. Wildes, Konstantinos G. Derpanis*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Kowal_A_Deeper_Dive_Into_What_Deep_Spatiotemporal_Networks_Encode_Quantifying_CVPR_2022_paper.html)/[Code](https://github.com/YorkUCVIL/Static-Dynamic-Interpretability/)/<br>[Journal](https://arxiv.org/abs/2211.01783)
|   2022   |   PAMI   | EM-driven unsupervised learning for efficient motion segmentation <br> <sup><sub>*Etienne Meunier, Anaïs Badoual, Patrick Bouthemy*</sub></sup> | [Paper](https://arxiv.org/abs/2201.02074)/[Code](https://github.com/Etienne-Meunier-Inria/EM-Flow-Segmentation)
|   2021   |   ICCV   | Self-supervised Video Object Segmentation by Motion Grouping <br> <sup><sub>*Charig Yang, Hala Lamdouar, Erika Lu, Andrew Zisserman, Weidi Xie*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Yang_Self-Supervised_Video_Object_Segmentation_by_Motion_Grouping_ICCV_2021_paper.html)/[Code](https://charigyang.github.io/motiongroup/)
|   2021   |   BMVC   | Segmenting Invisible Moving Objects <br> <sup><sub>*Hala Lamdouar, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://www.bmvc2021-virtualconference.com/assets/papers/0056.pdf)/[Proj](https://www.robots.ox.ac.uk/~vgg/research/simo/)
|   2020	 |   ACCV	  | Betrayed by Motion: Camouflaged Object Discovery via Motion Segmentation `MoCA` <br> <sup><sub>*Hala Lamdouar, Charig Yang, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://arxiv.org/abs/2011.11630)/[Code](https://www.robots.ox.ac.uk/~vgg/data/MoCA/)
|   2016   |  ECCV   | It’s Moving! A Probabilistic Model for Causal Motion Segmentation in Moving Camera Videos <br> <sup><sub>*Pia Bideau, Erik Learned-Miller*</sub></sup>  | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_26)/[Code](http://vis-www.cs.umass.edu/motionSegmentation/)


## CIS 

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2023     | CVPR     | Camouflaged Instance Segmentation via Explicit De-camouflaging  <br> <sup><sub>*Naisong Luo, Yuwen Pan, Rui Sun, Tianzhu Zhang, Zhiwei Xiong, Feng Wu*</sub></sup>  | Paper/Code
|   2022   |  ECCV    | OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers <br> <sup><sub>*Jialun Pei, Tianyang Cheng, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2207.02255)/[Code](https://github.com/PJLallen/OSFormer)
|   2022   |  TIP  | Camouflaged Instance Segmentation In-The-Wild: Dataset, Method, and Benchmark Suite <br> <sup><sub>*Trung-Nghia Le, Yubo Cao, Tan-Cong Nguyen, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2103.17123)/[Proj](https://sites.google.com/view/ltnghia/research/camo_plus_plus)


## Other Related 
| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2023   |   arXiv  | CamDiff: Camouflage Image Augmentation via Diffusion Model  <br> <sup><sub>*Xue-Jing Luo, Shuo Wang, Zongwei Wu, Christos Sakaridis, Yun Cheng, Deng-Ping Fan, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2304.05469)/Code 
|   2022   |  arXiv   | GANmouflage: 3D Object Nondetection with Texture Fields <br> <sup><sub>*Rui Guo, Jasmine Collins, Oscar de Lima, Andrew Owens*</sub></sup>  | [Paper](https://arxiv.org/abs/2201.07202)/[Proj](https://rrrrrguo.github.io/ganmouflage/)
|   2022   |   CVPR   | DTA: Physical Camouflage Attacks using Differentiable Transformation Network <br> <sup><sub>*Naufal Suryanto, Yongsu Kim, Hyoeun Kang, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2203.09831)/Code
|   2022   |  TMM     | Location-Free Camouflage Generation Network <br> <sup><sub>*Yangyang Li, Wei Zhai, Yang Cao, Zheng-jun Zha*</sub></sup> | [Paper](https://arxiv.org/abs/2203.09845)/[Code](https://github.com/Tale17/LCG-Net) 





## Datasets

| **Name** | **Year** | **Pub.** | **Links** | **Type** | **#Annot. Img.(Cam./Non)** | **Bbox** | **Obj. Mask** | **Ins. Mask** | **Comments**
| :------: | :------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
[CAMO++](https://sites.google.com/view/ltnghia/research/camo_plus_plus?authuser=0) | 2021 | TIP | [Paper](https://arxiv.org/abs/2103.17123) | Image | 2,700/2,800 | &check; | &check; | &check; | <small>Not Open</small>
[NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) | 2021 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf) | Image | 4,121 | &check; | &check; | &check; |
[COD10K](http://dpfan.net/camouflage/) | 2020 | CVPR | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf) | Image | 5,066/4,934 | &check; | &check; | &check; |
[CAMO](https://sites.google.com/view/ltnghia/research/camo) | 2019 | CVIU | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf) | Image | 1,250/1,250 | &cross; | &check; | &cross; |
[CPD1K](https://github.com/xfflyer/Camouflaged-people-detection) | 2018 | SPL | [Paper](https://ieeexplore.ieee.org/document/8336933)  | Image | 1,000 | &cross; | &check; | &cross; | 
[CHAMELEON](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | 2017 | —— | [Webpage](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | Image | 76 | &cross; | &check; | &cross; | 
|  |  |  |  |  |  |  |  |  |
[MoCA-Mask](https://xueliancheng.github.io/SLT-Net-project/) | 2022 | CVPR | [Paper](https://arxiv.org/abs/2203.07363) | Video | 4,691 | &check; | &check; | &cross; | <!--87 clips, 22,939 images-->
[MoCA](https://www.robots.ox.ac.uk/~vgg/data/MoCA/) | 2020 | ACCV | [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.html) | Video | 7,617 | &check; | &cross; | &cross; | <!--141 clips, 37K images-->
[CamouflagedAnimals](http://vis-www.cs.umass.edu/motionSegmentation/) | 2016 | ECCV | [Paper](http://vis-www.cs.umass.edu/motionSegmentation/) | Video | 181 | &cross; | &check; | &check; |  <!--9 clips, 839 images-->  



## Appendix

- [Awesome List for Camouflaged Object Detection](https://github.com/GewelsJI/SINet-V2/blob/main/AWESOME_COD_LIST.md)

