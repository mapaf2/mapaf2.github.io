---
title: "&#127807; Class-Incremental Learning of Plant and Disease Detection: Growing Branches with Knowledge Distillation."
collection: publications
permalink: /publication/2023-04-13-Dynamic-Y-KD
excerpt: "This paper investigates the problem of class-incremental object detection for agricultural applications where a model needs to learn new plant species and diseases incrementally without forgetting the previously learned ones."
date: 2023-10-02
venue: 'Workshop on Computer Vision in Plant Phenotyping and Agriculture (CVPPA) at ICCV'
#paperurl: 'https://arxiv.org/pdf/2304.06619.pdf'
#citation: 'Fortin, M. P. (2023). Class-Incremental Learning of Plant and Disease Detection: Growing Branches with Knowledge Distillation. arXiv preprint arXiv:2304.06619.
header:
    teaser: ../images/publications/CVPAA_overview.png
---
<img src="../../images/publications/CVPAA_overview.png" alt="Description" style="max-width:100%;height:auto;">

This paper investigates the problem of class-incremental object detection for agricultural applications where a model needs to learn new plant species and diseases incrementally without forgetting the previously learned ones. We adapt two public datasets to include new categories over time, simulating a more realistic and dynamic scenario. We then compare three class-incremental learning methods that leverage different forms of knowledge distillation to mitigate catastrophic forgetting. Our experiments show that all three methods suffer from catastrophic forgetting, but the recent Dynamic Y-KD approach, which additionally uses a dynamic architecture that grows new branches to learn new tasks, outperforms ILOD and Faster-ILOD in most scenarios both on new and old classes. These results highlight the challenges and opportunities of continual object detection for agricultural applications. In particular, the large intra-class and small inter-class variability that is typical of plant images exacerbate the difficulty of learning new categories without interfering with previous knowledge. We publicly release our code to encourage future work.

[Downloader paper here](https://openaccess.thecvf.com/content/ICCV2023W/CVPPA/papers/Page-Fortin_Class-Incremental_Learning_of_Plant_and_Disease_Detection_Growing_Branches_with_ICCVW_2023_paper.pdf)

Recommended citation: Pagé-Fortin, M. (2023). Class-Incremental Learning of Plant and Disease Detection: Growing Branches with Knowledge Distillation. In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 593-603).