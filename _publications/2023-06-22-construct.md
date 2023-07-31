---
title: "Construct-vl: Data-free continual structured vl concepts learning."
collection: publications
permalink: /publication/2023-06-22-construct
excerpt: ''
date: 2023-06-21
venue: 'CVPR'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Smith_ConStruct-VL_Data-Free_Continual_Structured_VL_Concepts_Learning_CVPR_2023_paper.pdf'
citation: 'Smith, J.S., Cascante-Bonilla, P., Arbelle, A., Kim, D., Panda, R., Cox, D., Yang, D., Kira, Z., Feris, R. and Karlinsky, L., 2023. Construct-vl: Data-free continual structured vl concepts learning. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 14994-15004).'

---
# Abstract
Recently, large-scale pre-trained Vision-and-Language (VL) foundation models have demonstrated remarkable capabilities in many zero-shot downstream tasks, achieving competitive results for recognizing objects defined by as little as short text prompts. However, it has also been shown that VL models are still brittle in Structured VL Concept (SVLC) reasoning, such as the ability to recognize object attributes, states, and inter-object relations. This leads to reasoning mistakes, which need to be corrected as they occur by teaching VL models the missing SVLC skills; often this must be done using private data where the issue was found, which naturally leads to a data-free continual (no task-id) VL learning setting. In this work, we introduce the first Continual Data-Free Structured VL Concepts Learning (ConStruct-VL) benchmark and show it is challenging for many existing data-free CL strategies. We, therefore, propose a data-free method comprised of a new approach of Adversarial Pseudo-Replay (APR) which generates adversarial reminders of past tasks from past task models. To use this method efficiently, we also propose a continual parameter-efficient Layered-LoRA (LaLo) neural architecture allowing no-memory-cost access to all past models at train time. We show this approach outperforms all data-free methods by as much as 7% while even matching some levels of experience-replay (prohibitive for applications where data-privacy must be preserved). Our code is publicly available at https://github.com/jamessealesmith/ConStruct-VL

[Download paper here](https://openaccess.thecvf.com/content/CVPR2023/papers/Smith_ConStruct-VL_Data-Free_Continual_Structured_VL_Concepts_Learning_CVPR_2023_paper.pdf)

Recommended citation:
@inproceedings{smith2023construct,
  title={Construct-vl: Data-free continual structured vl concepts learning},
  author={Smith, James Seale and Cascante-Bonilla, Paola and Arbelle, Assaf and Kim, Donghyun and Panda, Rameswar and Cox, David and Yang, Diyi and Kira, Zsolt and Feris, Rogerio and Karlinsky, Leonid},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={14994--15004},
  year={2023}
}