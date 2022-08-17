# Project-4-Nuclei-Segmentation-AI07
A model for semantic segmentation of cell neuclei-containing images

# Summary

In order to develop the process of segment the nuclei, the goal of this study is to identify the variety of nuclei in biomedical photographs.
Drug testing will be more effective, and it will take less time to introduce a new drug to the market. 
Because the nuclei varied in size and form. The suitable technique for this project would therefore be semantic segmentation.

# Dataset

The dataset used was a dataset for 
[2018 Data Science Bowl][1] Kaggle competition

[1]:https://www.kaggle.com/competitions/data-science-bowl-2018/data


# Methodology

Preparing the Dataset

Dataset contain stage_1 train and test dataset 

Convert into Numpy array

Then we proceed with resizing the dataset as shown below

![image](https://user-images.githubusercontent.com/110074843/185026125-d7a2b413-7bd1-42c6-8534-6d9c405579b7.png)

Next, we expand the mask dimension and convert the value label to 0 & 1
