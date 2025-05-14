# wound_segmentation_node
This is a ROS1 package for wound segmentation. The dataset is downloaded from  [wound-segmentation](https://github.com/uwm-bigdata/wound-segmentation), so this repository is build based on [that repository](https://github.com/uwm-bigdata/wound-segmentation).  The architectures tested so far includes: U-Net, MobileNetV2, Mask-RCNN, SegNet, VGG16.

![Intro_Image](https://raw.githubusercontent.com/Pele324/ChronicWoundSeg/master/figures/Intro.png)
![Dataset_Image](https://raw.githubusercontent.com/Pele324/ChronicWoundSeg/master/figures/Dataset.png)

## Usage


## Requirements
tensorflow==2.6.0

## Citation
C. Wang, D.M. Anisuzzaman, V. Williamson, M.K. Dhar, B. Rostami, J. Niezgoda, S. Gopalakrishnan, and Z. Yu, “Fully Automatic Wound Segmentation with Deep Convolutional Neural Networks”, Scientific Reports, 10:21897, 2020. https://doi.org/10.1038/s41598-020-78799-w

## Dataset
The training dataset is built by our lab and collaboration clinic, Advancing the Zenith of Healthcare (AZH) Wound and Vascular Center. With their permission, we are sharing this dataset (./data/wound_dataset/) publicly. This dataset was fully annotated by wound professionals and preprocessed with cropping and zero-padding.  