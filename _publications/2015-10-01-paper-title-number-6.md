---
title: "🖼️ Continual Semantic Segmentation Leveraging Image-level Labels and Rehearsal"
collection: publications
permalink: /publication/2022-07-30-Continual-Semantic-Segmentation
excerpt: 'We propose a weakly-supervised mechanism for continual semantic segmentation that can leverage cheap image-level annotations and a novel rehearsal strategy that intertwines the learning of past and new classes. Specifically, we explore two rehearsal technique variants: 1) imprinting past objects on new images and 2) transferring past representations in intermediate features maps.'
date: 2022-07-30
venue: 'International Joint Conference on Artificial Intelligence (IJCAI)'
#paperurl: 'https://www.ijcai.org/proceedings/2022/0177.pdf'
#citation: 'Fortin, M. P., & Chaib-draa, B. (2022). Continual Semantic Segmentation Leveraging Image-level Labels and Rehearsal. In Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence, IJCAI-22. International Joint Conferences on Artificial Intelligence Organization (Vol. 2).'
header:
    teaser: ../images/publications/ijcai.png
---
Despite the remarkable progress of deep learning models for semantic segmentation, the success of these models is strongly limited by the following aspects: 1) large datasets with pixel-level annotations must be available and 2) training must be performed with all classes simultaneously. Indeed, in incremental learning scenarios, where new classes are added to an existing framework, these models are prone to catastrophic forgetting of previous classes. To address these two limitations, we propose a weakly-supervised mechanism for continual semantic segmentation that can leverage cheap image-level annotations and a novel rehearsal strategy that intertwines the learning of past and new classes. Specifically, we explore two rehearsal technique variants: 1) imprinting past objects on new images and 2) transferring past representations in intermediate features maps. We conduct extensive experiments on Pascal-VOC by varying the proportion of fully- and weakly-supervised data in various setups and show that our contributions consistently improve the mIoU on both past and novel classes. Interestingly, we also observe that models trained with less data in incremental steps sometimes outperform the same architectures trained with more data. We discuss the significance of these results and propose some hypotheses regarding the dynamics between forgetting and learning.

[Download paper here](https://www.ijcai.org/proceedings/2022/0177.pdf)

Recommended citation: Fortin, M. P., & Chaib-draa, B. (2022). Continual Semantic Segmentation Leveraging Image-level Labels and Rehearsal. In Proceedings of the Thirty-First <i>International Joint Conference on Artificial Intelligence</i>, IJCAI-22. International Joint Conferences on Artificial Intelligence Organization (Vol. 2).