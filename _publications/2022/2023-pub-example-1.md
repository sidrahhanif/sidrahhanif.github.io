---
title:          "Autonomous Character Region Score Fusion for Word Detection in Camera-captured Handwriting Documents"
date:           2022-01-14 00:01:00 +0800
selected:       true
pub:            "Document Intelligence workshop, ACM SIGKDD"
pub_date:       "2022"
abstract: >- 
Word detection is considered an object detection problem. However,
characters are the basic building block in words, and the presence
of characters makes word detection different from general object
detection problems. Character region scores identification performs
consistently for handwritten text in low-contrast camera-captured
images, But detecting words from characters poses a challenge
because of variable character spacing in words. Nevertheless, considering the only character and ignoring a word’s entirety does not
cope with overlapping words in handwriting text. In our work, we
propose the fusion of character region scores with word detection.
Since the character level annotations are not available for handwritten text, we estimate the character region scores in a weakly supervised manner. Character region scores are estimated autonomously
from the word’s bounding box estimation to learn the character
level information in handwriting. We propose to fuse the character
region scores and images to detect words in camera-captured handwriting images. 

cover:          /assets/images/covers/block_diagram.png
authors:
- Sidra Hanif
- Longin Jan Latecki
links:
  Paper: https://document-intelligence.github.io/DI-2022/files/di-2022_final_17.pdf
---
