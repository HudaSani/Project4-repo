
# Cell Nuclei Detection using Semantic Segmentation with U-Net
## Summary
##### This project aim to detect nucleus in medical image by image segmentation. In the field where a thorough understanding of an image is required, semantic segmentation is best to applied. medical scanning or imaging is one of the application where segmentation of cells and tissues are needed to diagnose medical conditions. Therefore, semantic segmentation with U-Net architecture is employed in this project. [2018 Data Science Bowl](https://www.kaggle.com/c/data-science-bowl-2018) data set is used to train the model.
##
### 1. IDE and Framework
##### This project is created using [Google colab](https://colab.research.google.com/). The frameworks used in this project are Numpy, OpenCV, TensorFlow and Scikit-Learn.
### 2. Methodology
#### 2.1 Data Pipeline
##### Data is uploaded and sorted. It came with training set and testing set for both input images and masks. Since google colab did not load the data in order, sorting need to be done to make sure that the input image matches the mask.

