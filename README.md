# NeoPolyp-Segmentation
Developing a Deep Learning model for problems in Image Segmentation for detecting neoplastic or non-neoplastic  polyps in an image. It’s a part of the competition “BKAI-IGH NeoPolyp” on Kaggle
Using OpenCV and Pytorch to pre-processing and preparation for data loader before training Segmentation model. After experimenting multiple segmentation models, for example FCN, Unet, Unet++, DeepLabv3,…, with different encoder, I get the best score of approximately 0.82 by DeepLabv3++ with encoder is timm-RegNety-160.
