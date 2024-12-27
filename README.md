# Canny-with-3-thresholds-V.S.-HED
The project aims to compare the canny detection algorithmn with 3 different thresholds and HED (Holistically-Nested Edge Detection). 
The dataset is from kaggle:
https://www.kaggle.com/datasets/balraj98/berkeley-segmentation-dataset-500-bsds500/data
We load the pretrained model from:
https://github.com/s9xie/hed
Thanks for their work!
And we use the precision, recall, mean and median F1 scores as the criteria for evaluating the model.

**References**
Xie, Saining and Tu, Zhuowen. "Holistically-Nested Edge Detection." Proceedings of the IEEE International Conference on Computer Vision, 2015.
