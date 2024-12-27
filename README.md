# Canny with 3 Thresholds vs HED

## Project Overview
This project aims to compare the Canny edge detection algorithm with three different thresholds against Holistically-Nested Edge Detection (HED).

## Dataset
The dataset used for this project is sourced from Kaggle:
[Berkeley Segmentation Dataset 500 (BSDS500)](https://www.kaggle.com/datasets/balraj98/berkeley-segmentation-dataset-500-bsds500/data)

## Canny method
We provide the canny detection algorithm manually implemented to show how it works.

## Pretrained Model
We load the pretrained model from:
[HED GitHub Repository](https://github.com/s9xie/hed)
You can download via this link.

## Evaluation Criteria
We use the following metrics to evaluate the model:
- Mean Precision, Median Precision
- Mean Recall, Median Recall
- Mean F1 Score, Median F1 Score

## Layers Check
We check how many layers in HED，and same as RELU fuction to see how the algorithm works. It contains 19 convolutional Layers, 13 RELU layers. Which use Vgg16 as backbones without pooling layer, and use 5 convolution layers without RELU，use skip connection convolution instead.

## References
Xie, Saining and Tu, Zhuowen. "Holistically-Nested Edge Detection." Proceedings of the IEEE International Conference on Computer Vision, 2015.

## Acknowledgements
Thanks to the authors of the HED model for their work!
