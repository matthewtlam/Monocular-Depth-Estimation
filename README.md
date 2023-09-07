# Self Supervised Monocular Depth Estimation

Matthew Lam - University of Waterloo CS 484 Computational Vision


Similar to semantic segmentation problems, the unavailability of accurate ground truth data poses a significant obstacle when applying deep learning techniques to monocular depth estimation. This notebook presents a PyTorch implementation of the monocular depth estimation network proposed by Godard et al. in their 2017 paper titled "Unsupervised Monocular Depth Estimation with Left-Right Consistency" (https://arxiv.org/pdf/1609.03677v3.pdf). The development of this notebook took reference from the official repository named "Monodepth" (https://github.com/mrharicot/monodepth).

The objective of this notebook is to provide a comprehensive explanation and practical demonstration of the functioning of Godard et al.'s depth estimation network. The notebook emphasizes clarity and aims to facilitate learning on the topic.

After conducting training for 5 epochs, using a limited subset of the KITTI dataset comprising 3318 left/right image pairs, the obtained results are presented. It is important to note that by extending the training duration to cover the entire dataset, substantial enhancements in performance can be achieved.

