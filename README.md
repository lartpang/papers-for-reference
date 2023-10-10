# Papers for Reference

## CLIP

### CLIPSelf: Vision Transformer Distills Itself for Open-Vocabulary Dense Prediction

- ArXiv: https://arxiv.org/abs/2310.01403
- Code: https://github.com/wusize/CLIPSelf
- Core: Enhance the local region representation of CLIP for downstream open-vocabulary dense prediction tasks.

> Open-vocabulary dense prediction tasks including object detection and image segmentation have been advanced by the success of Contrastive Language-Image Pre-training (CLIP). CLIP models, particularly those incorporating vision transformers (ViTs), have exhibited remarkable generalization ability in zero-shot image classification. However, **when transferring the vision-language alignment of CLIP from global image representation to local region representation for the open-vocabulary dense prediction tasks, CLIP ViTs suffer from the domain shift from full images to local image regions.** In this paper, we embark on an in-depth analysis of **the region-language alignment** in CLIP models, which is essential for downstream open-vocabulary dense prediction tasks. Subsequently, we propose an approach named CLIPSelf, which adapts the image-level recognition ability of CLIP ViT to local image regions without needing any region-text pairs. CLIPSelf empowers ViTs to distill itself by aligning a region representation extracted from its dense feature map with the image-level representation of the corresponding image crop. With the enhanced CLIP ViTs, we achieve new state-of-the-art performance on open-vocabulary object detection, semantic segmentation, and panoptic segmentation across various benchmarks.

