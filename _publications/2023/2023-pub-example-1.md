---
title:          "Strokes Trajectory Recovery for Unconstrained Handwritten Documents with Automatic Evaluation."
date:           2023-11-22 00:01:00 +0800
selected:       true
pub:            "International Conference on Pattern Recognition Applications and Methods (ICPRAM)"
pub_date:       "2023"
abstract: >-
  The focus of this paper is offline handwriting Stroke Trajectory Recovery (STR), which facilitates the tasks such as handwriting recognition and synthesis. The input is an image of handwritten text, and the output is a stroke trajectory, where each stroke is a sequence of 2D point coordinates. Usually, Dynamic Time Warping (DTW) or Euclidean distance-based loss function is employed to train the STR network. In DTW loss calculation, the predicted and ground-truth stroke sequences are aligned, and their differences are accumulated. The DTW loss penalizes the alignment of far-off points proportional to their distance. As a result, DTW loss incurs a small penalty if the predicted stroke sequence is aligned to the ground truth stroke sequence but includes stray points/artifacts away from ground truth points. To address this issue, we propose to compute a marginal Chamfer distance between the predicted and the ground truth point sets to penalize the stray points more heavily. Our experiments show that the loss penalty incurred by complementing DTW with the marginal Chamfer distance gives better results for learning STR. We also propose an evaluation method for STR cases where ground truth stroke points are unavailable. We digitalize the predicted stroke points by rendering the stroke trajectory as an image and measuring the image similarity between the input handwriting image and the rendered digital image. We further evaluate the readability of recovered strokes. By employing an OCR system, we determine whether the input image and recovered strokes represent the same words.
cover:          /assets/images/covers/icpram.jpg
authors:
- Sidra Hanif
- Longin Jan Latecki
links:
  Paper: https://cis.temple.edu/~latecki/Papers/SidraICPRAM2023.pdf
---
