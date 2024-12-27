# Canny with 3 Thresholds vs HED

## Project Overview
This project aims to compare the Canny edge detection algorithm with three different thresholds against Holistically-Nested Edge Detection (HED).

## Dataset
The dataset used for this project is sourced from Kaggle:
[Berkeley Segmentation Dataset 500 (BSDS500)](https://www.kaggle.com/datasets/balraj98/berkeley-segmentation-dataset-500-bsds500/data)

## Pretrained Model
We load the pretrained model from:
[HED GitHub Repository](https://github.com/s9xie/hed)

## Evaluation Criteria
We use the following metrics to evaluate the model:
- Precision
- Recall
- Mean F1 Score
- Median F1 Score

## References
Xie, Saining and Tu, Zhuowen. "Holistically-Nested Edge Detection." Proceedings of the IEEE International Conference on Computer Vision, 2015.

## Acknowledgements
Thanks to the authors of the HED model for their work!
