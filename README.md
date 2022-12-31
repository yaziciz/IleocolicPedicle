# IleocolicPedicle
This repository contains the dataset, code scripts and the article that investigates the real-time segmentation of the ileocolic pedicle from the laparoscopy images by U-Net and Attention U-Net models.

The dataset can be accessed from the following Google Drive link:

https://drive.google.com/drive/folders/1dGCVOSx0DMfsm7YCPa16IAhpMGvBuMMY?usp=share_link

The model weights can be found here:

https://drive.google.com/drive/folders/1kVj6-693NwOF8XVdCIgvtGBppmRIMBwg?usp=share_link

Abstract:

Minimally Invasive Surgery (MIS) is the operation of using computer-aided systems to perform surgeries to increase the comfort of the patients and the recovery rate after the surgery. However, as a drawback, the visibility of the tissues becomes difficult for surgeons due to the limited space in the operation area. To this end, we investigate the Convolutional Neural Network-based segmentation models to perform real- time semantic segmentation of the Ileocolic Pedicle. We compose annotated dataset to perform the training of two state-of-the- art models, U-Net and Attention U-Net. Our results demonstrate that the trained models of U-Net achieved mIoU ranging between 0.948 - 0.957 and 0.748 - 0.957 mIoU for Attention U-Net. We further analyzed the inference time of the models and the implemented backbones. We observed that the inference time was ranging between 100 ms - 760 ms for U-Net, and 100 ms - 1600 ms for Attention U-Net. The achieved results indicate a promising real-time assistive system for surgeons to perform the operations.
