---
title: "Incorporating structured representations into pretrained vision & language models using scene graphs"
collection: publications
permalink: /publication/2023-04-10-struct_rep
excerpt: ''
date: 2023-04-10
venue: 'Nature Methods'
paperurl: https://arxiv.org/pdf/2305.06343
citation: Herzig, R., Mendelson, A., Karlinsky, L., Arbelle, A., Feris, R., Darrell, T. and Globerson, A., 2023. &quot;Incorporating structured representations into pretrained vision & language models using scene graphs.&quot; arXiv preprint arXiv:2305.06343.

---
# Abstract

Vision and Language (VL) models have demonstrated remarkable zero-shot performance in a variety of tasks. However, recent studies have shown that even the best VL models struggle to capture aspects of scene understanding, such as object attributes, relationships, and action states. In contrast, obtaining structured annotations, e.g., scene graphs (SGs) that could improve these models is time-consuming, costly, and tedious, and thus cannot be used on a large scale. Here we ask, can small datasets containing SG annotations provide sufficient information for enhancing structured understanding of VL models? We show that it is indeed possible to improve VL models using such data by utilizing a specialized model architecture and a new training paradigm. Our approach captures structure-related information for both the visual and textual encoders by directly supervising both components when learning from SG labels. We use scene graph supervision to generate fine-grained captions based on various graph augmentations highlighting different compositional aspects of the scene, and to predict SG information using an open vocabulary approach by adding special ``Adaptive SG tokens'' to the visual encoder. Moreover, we design a new adaptation technique tailored specifically to the SG tokens that allows better learning of the graph prediction task while still maintaining zero-shot capabilities. Our model shows strong performance improvements on the Winoground and VL-checklist datasets with only a mild degradation in zero-shot performance.

[Download paper here](https://arxiv.org/pdf/2305.06343)

Recommended citation:

@article{herzig2023incorporating,
  title={Incorporating structured representations into pretrained vision \& language models using scene graphs},
  author={Herzig, Roei and Mendelson, Alon and Karlinsky, Leonid and Arbelle, Assaf and Feris, Rogerio and Darrell, Trevor and Globerson, Amir},
  journal={arXiv preprint arXiv:2305.06343},
  year={2023}
}