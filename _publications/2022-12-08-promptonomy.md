---
title: "Promptonomyvit: Multi-task prompt learning improves video transformers using synthetic scene data"
collection: publications
permalink: /publication/2022-12-08-promptonomy
excerpt: ''
date: 2022-12-08
venue: 'ArXiv'
paperurl: https://arxiv.org/pdf/2212.04821
citation: 'Herzig, R., Abramovich, O., Ben-Avraham, E., Arbelle, A., Karlinsky, L., Shamir, A., Darrell, T. and Globerson, A., 2022. Promptonomyvit: Multi-task prompt learning improves video transformers using synthetic scene data. arXiv preprint arXiv:2212.04821.'

---
# Abstract

Action recognition models have achieved impressive results by incorporating scene-level annotations, such as objects, their relations, 3D structure, and more. However, obtaining annotations of scene structure for videos requires a significant amount of effort to gather and annotate, making these methods expensive to train. In contrast, synthetic datasets generated by graphics engines provide powerful alternatives for generating scene-level annotations across multiple tasks. In this work, we propose an approach to leverage synthetic scene data for improving video understanding. We present a multi-task prompt learning approach for video transformers, where a shared video transformer backbone is enhanced by a small set of specialized parameters for each task. Specifically, we add a set of "task prompts", each corresponding to a different task, and let each prompt predict task-related annotations. This design allows the model to capture information shared among synthetic scene tasks as well as information shared between synthetic scene tasks and a real video downstream task throughout the entire network. We refer to this approach as "Promptonomy", since the prompts model a task-related structure. We propose the PromptonomyViT model (PViT), a video transformer that incorporates various types of scene-level information from synthetic data using the "Promptonomy" approach. PViT shows strong performance improvements on multiple video understanding tasks and datasets.


[Download paper here](https://arxiv.org/pdf/2212.04821)

Recommended citation:

@article{herzig2022promptonomyvit,
  title={Promptonomyvit: Multi-task prompt learning improves video transformers using synthetic scene data},
  author={Herzig, Roei and Abramovich, Ofir and Ben-Avraham, Elad and Arbelle, Assaf and Karlinsky, Leonid and Shamir, Ariel and Darrell, Trevor and Globerson, Amir},
  journal={arXiv preprint arXiv:2212.04821},
  year={2022}
}