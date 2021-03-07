# Awesome-Crowd-Localization
Awesome Crowd Localization

## Contents
* [Misc](#misc)
* [Datasets](#datasets)
* [Papers](#papers)
* [Leaderboard](#leaderboard)

## Misc

### Relaetd Tasks
- [Crowd Counting](https://github.com/gjy3035/Awesome-Crowd-Counting)
- Crowd Analysis
- [Video Surveillance](https://github.com/CommissarMa/Awesome-Public-Safety-in-Vision)
- Dense/Small/Tiny Object Detection

### Challenge
- NWPU-Crowd Localization: [Link](https://www.crowdbenchmark.com/nwpucrowdloc.html)
- The 1st Tiny Object Detection Challenge: [Link](https://github.com/ucas-vg/TinyBenchmark)

### Metrics
- mAP, mAR in [RAZNet](http://www.muyadong.com/paper/cvpr19_0484.pdf) (namely key point evaluation in COCO: fixed sigma)
- F1-m, Precision, Recall in [NWPU-Crowd](https://arxiv.org/abs/2001.03360) (scale-aware sigma)
- MLE in [LSC-CNN](https://arxiv.org/abs/1906.07538) (distance measure)

## Datasets
- NWPU-Crowd (dot, box)
- JHU-CROWD (dot, size)
- FDST (dot, box)

## Papers

### Arxiv
- <a name="RDTM"></a> **[RDTM]** Reciprocal Distance Transform Maps for Crowd Counting and People Localization in Dense Crowd [[paper]](https://arxiv.org/abs/2102.07925) [[code]](https://github.com/dk-liang/RDTM)
- Counting and Locating High-Density Objects Using Convolutional Neural Network [[paper](https://arxiv.org/pdf/2102.04366.pdf)]
- <a name="IIM"></a> **[IIM]**  Learning Independent Instance Maps for Crowd Localization  [[paper](https://arxiv.org/pdf/2012.04164.pdf)] [[code](https://github.com/taohan10200/IIM)]
- <a name='AutoScale'></a> **[AutoScale]** Autoscale: learning to scale for crowd counting  [[paper](https://arxiv.org/pdf/1912.09632.pdf)] [[code](https://github.com/dk-liang/AutoScale)]
- A Strong Baseline for Crowd Counting and Unsupervised People Localization [[paper](https://arxiv.org/abs/2011.03725)]
- Drone-based Joint Density Map Estimation, Localization and Tracking with Space-Time Multi-Scale Attention Network [[paper](https://arxiv.org/abs/1912.01811)][[code](https://github.com/VisDrone)]

### 2021
- <a name="Crowd-SDNet"></a> **[Crowd-SDNet]** A Self-Training Approach for Point-Supervised Object Detection and Counting in Crowds (**T-IP**) [[paper]](https://ieeexplore.ieee.org/abstract/document/9347744/) [[code]]( https://github.com/WangyiNTU/Point-supervised-crowd-detection)
- <a name="TopoCount"></a> **[TopoCount]**  Localization in the Crowd with Topological Constraints (**AAAI2021**) [[paper](https://arxiv.org/abs/2012.12482)][[code](https://github.com/ShahiraAbousamra/TopoCount)]

### 2020 
- <a name="NWPU"></a> **[NWPU]** NWPU-Crowd: A Large-Scale Benchmark for Crowd Counting and Localization (**T-PAMI**) [[paper](https://arxiv.org/abs/2001.03360)][[code](https://gjy3035.github.io/NWPU-Crowd-Sample-Code/)]
- <a name="LSC-CNN"></a> **[LSC-CNN]** Locate, Size and Count: Accurately Resolving People in Dense Crowds via Detection (**T-PAMI**) [[paper](https://arxiv.org/abs/1906.07538)][[code](https://github.com/val-iisc/lsc-cnn)]
- Scale Match for Tiny Person Detection (**WACV**) [[paper](https://openaccess.thecvf.com/content_WACV_2020/papers/Yu_Scale_Match_for_Tiny_Person_Detection_WACV_2020_paper.pdf)][[code](https://github.com/ucas-vg/TinyBenchmark)]


### 2019 
- Point in, Box out: Beyond Counting Persons in Crowds  (**CVPR**) [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Point_in_Box_Out_Beyond_Counting_Persons_in_Crowds_CVPR_2019_paper.pdf)]
- <a name="RAZ_Loc"></a> **[RAZ_Loc]** Recurrent attentive zooming for joint crowd counting and precise localization  (**CVPR**) [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Recurrent_Attentive_Zooming_for_Joint_Crowd_Counting_and_Precise_Localization_CVPR_2019_paper.pdf)] [[Reproduction_code](https://github.com/gjy3035/NWPU-Crowd-Sample-Code-for-Localization)]
- <a name="RDNet"></a> **[RDNet]** Density Map Regression Guided Detection Network for RGB-D Crowd Counting and Localization (**CVPR**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lian_Density_Map_Regression_Guided_Detection_Network_for_RGB-D_Crowd_Counting_CVPR_2019_paper.pdf)][[code](https://github.com/svip-lab/RGBD-Counting)] 

### 2018 
- <a name="CL"></a> **[CL]** Composition Loss for Counting, Density Map Estimation and Localization in Dense Crowds (**ECCV**) [[paper](https://arxiv.org/abs/1808.01050)]
- <a name="LCFCN"></a> **[LCFCN]**  Where are the Blobs: Counting by Localization with Point Supervision (**ECCV**) [[paper](https://arxiv.org/abs/1807.09856)] [[code](https://github.com/ElementAI/LCFCN)]
- SOD-MTGAN: Small Object Detection via Multi-Task Generative Adversarial Network (**ECCV**) [[paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yongqiang_Zhang_SOD-MTGAN_Small_Object_ECCV_2018_paper.pdf)]

### 2017 
- Focal Loss for Dense Object Detection (**ICCV**) [[paper](https://openaccess.thecvf.com/content_ICCV_2017/papers/Lin_Focal_Loss_for_ICCV_2017_paper.pdf)]
- <a name="TinyFaces"></a> **[TinyFaces]** Finding tiny faces (**CVPR**) [[paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Hu_Finding_Tiny_Faces_CVPR_2017_paper.pdf)]
- Perceptual Generative Adversarial Networks for Small Object Detection (**CVPR**) [[paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Perceptual_Generative_Adversarial_CVPR_2017_paper.pdf)]

### 2015 
- <a name="Hydra-CNN"></a>  End-to-end people detection in crowded scenes  (**CVPR**) [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Stewart_End-To-End_People_Detection_CVPR_2016_paper.pdf)] [[code](https://github.com/gramuah/ccnn)]
- <a name="Faster_RCNN"></a> **[Faster-RCNN]** Towards real-time object detection with region proposal networks  (**CVPR**) [[paper](http://agamenon.tsc.uah.es/Investigacion/gram/publications/eccv2016-onoro.pdf)] [[code](https://github.com/gramuah/ccnn)]

## Leaderboard

### NWPU

More detailed results are in this [link](https://www.crowdbenchmark.com/nwpucrowdloc.html).

| Year--Conference/Journal |Methods      |Backbone |F1-measure|Precise|Recall|        A0~A5                 |  Avg. | 
|  --------------------------|----------|---------- | -------  | --------| -------|-------------------------     |-------|
| 2015--NIPS | [Faster RCNN](#RCNN)       |ResNet-101| 6.7      | 95.8    | 3.5    | 0/0.002/0.4/7.9/37.2/63.5    | 18.2  |
| 2017--CVPR | [TinyFaces](#TinyFaces)    |ResNet-101| 56.7     | 52.9    | 61.1   | 4.2/22.6/59.1/90.0/93.1/89.6 | 59.8  |
| 2019--arXiv | [VGG+GPR](#VGG)           |VGG-16    | 52.5     | 55.8    | 49.6   | 3.1/27.2/49.1/68.7/49.8/26.3 | 37.4  |
| 2019--CVPR | [RAZ_Loc](#RAZ_Loc)        |VGG-16    | 59.8     | 66.6    | 54.3   | 3.1/27.2/49.1/68.7/49.8/26.3 | 42.4  |
| 2021--T-IP | [Crowd-SDNet](#Crowd-SDNet) |ResNet-50 | 63.7     | 65.1    | 62.4   | 7.3/43.7/62.4/75.7/71.2/70.2 | 55.1  |
| 2021--arXiv | [RDTM](#RDTM)             |VGG-16    | 69.9     | 75.1    | 65.4   | 11.5/46.3/68.5/74.9/54.6/18.2 | 45.7  |
| 2020--arXiv | [IIM](#IIM)               |VGG-16    | 73.2     | 77.9    | 69.2   | 10.1/44.1/70.7/82.4/83.0/61.4| 58.7  | 
| 2020--arXiv | [IIM](#IIM)               |HRNet     | 76.2     | 81.3    | 71.7   | 12.0/46.0/73.2/85.5/86.7/64.3| 61.3  |  
