---
title:          "Image retrieval with similar object detection and local similarity to detected objects"
date:           2019-08-23 00:01:00 +0800
selected:       true
pub:            "Pacific Rim International Conference on Artificial Intelligence"
pub_date:       "2019"
abstract: >-
  Commercial image search applications like eBay and Pinterest allow users to select the focused area as bounding box over the query images, which improves the retrieval accuracy. The focused area image retrieval strategy motivated our research, but our system has three main advantages over the existing works. (1) Given a query focus area, our approach localizes the most similar region in the database image and only this region is used for computing image similarity. This is done in a unified network whose weights are adjusted both for localization and similarity learning in an end-to-end manner. (2) This is achieved using fewer than five proposals extracted from a saliency map, which speedups the pairwise similarity computation. Usually hundreds or even thousands of proposals are used for localization. (3) For users, our system explains the relevance of the retrieved results by locating the regions in the database images that are the most similar to the query object. Our method achieves significantly better retrieval performance than the off-the-shelf object localization-based retrieval methods and end-to-end trained triplet method with a region proposal network. Our experimental results demonstrate 86% retrieval rate as compared to 73% achieved by the existing methods on PASCAL VOC07 and VOC12 datasets. Extensive experiments are also conducted on the instance retrieval databases Oxford5k and INSTRE, where we exhibit competitive performance. Finally, we provide both quantitative and qualitative results of our retrieval method demonstrating its superiority over commercial image search systems.
cover:          /assets/images/covers/pricai.jpg
authors:
- Sidra Hanif
- Chao Li
- Anis Alazzawe
- Longin Jan Latecki
links:
  Paper: https://dl.acm.org/doi/abs/10.1007/978-3-030-29894-4_4
---
