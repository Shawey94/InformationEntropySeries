# Information Entropy Meets Artificial Intelligence
This repository will include the code and experimental setup details for the paper "Exploring the impact of information entropy change in learning systems" across various learning applications, including classification, domain adaptation, domain generalization, semi-supervised learning, etc.

[02/13/2024] I invited experts in the field to join my project. We have applied the proposed method in Image Classification, Domain Adaptation, and semi-supervised learning within computer vision.

For Image Classification, after a deliberate hyperparameter search, we hit a Top 1 accuracy of 97.2% on ImageNet-1K using pretrained-ViT. By utilizing our trained weights of ViT-B and conducting inference on ImageNetV2, we attained a Top 1 accuracy of over 93%.

In Domain Adaptation, we utilized NoisyViT (based on TVT, Yang et al., WACV2023) with Optimal Q and achieved state-of-the-art results on Office-31, Office-Home, and Visda2017 datasets.

For semi-supervised learning, we followed the protocol outlined by USB (Wang et al., NeurIPS2022). Compared to a bunch of Match methods such as FlatMatch, FreeMatch, and FlexMatch, etc. on CIFAR10, CIFAR100, and STL10, our method demonstrated improved performance.

The applications of positive noise in large language models (LLMs) have been accepted in AI venues, and we observe more and more submissions on the way. Some of the coauthors served as reviewers at ICML 2024, and it's interesting to see submissions that utilize our methodology to do operations on embeddings.

We will release the source code and setting instructions once either of our submissions is accepted. We extend our gratitude to readers who provide constructive comments or inquire about technical details. 

[09/29/2023] Semi-supervised learning (SSL) work is currently in progress. Excited to extend the proposed theory for SSL and more.

[08/21/2023] As requested by a reviewer, we conducted tests on ImageNetV2 and achieved a top-1 accuracy of 84.8% (using LinearQ). 

[04/12/2023] Achieved a top 1 accuracy of 95.38% (OptimalQ) on ImageNet-1K with pre-trained weights on ImageNet-21K.

Research, coding, analysis, and maintenance are all on my own, so quite busy usually. Updates will be made periodically.
