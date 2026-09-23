### Automated Cell Segmentation using Mask R-CNN

#### Overview

Cell instance segmentation on microscopy images using Detectron2 Mask R-CNN. Images were annotated in Roboflow and exported in COCO format.
- **Dataset**: 32 microscopy images
- **Input size**: 512×512
- **Augmentation**: horizontal/vertical flips and Gaussian noise
- **Single class**: cell
- **Model**: Mask R-CNN (Detectron2) with ResNet backbone, FPN, RPN, ROI heads and Mask segmentation head

#### References
- He et al., Mask R-CNN, ICCV 2017.
- Li et al., Mask DINO, CVPR 2023.
