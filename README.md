# Image-Recognition-for-Gender-Detection

Overview

This project aims to develop a Machine Learning Algorithm utilizing Convolutional Neural Networks (CNN) to predict the gender of celebrities from given images. It leverages the InceptionV3 architecture for image recognition, focusing on facial attributes for gender identification.

Dataset Description

The dataset used in this project comprises:

202,599 face images of various celebrities.

10,177 unique identities with undisclosed names.

40 binary attribute annotations per image (e.g., smiling, glasses, etc.).

5 landmark locations for facial features (left eye, right eye, nose, left mouth, right mouth).

Data Files

img_align_celeba.zip: Contains cropped and aligned face images.

list_eval_partition.csv: Suggested partitioning of images into training, validation, and testing sets.

list_bbox_celeba.csv: Bounding box information for each image (coordinates, width, and height).

list_landmarks_align_celeba.csv: Landmark coordinates for facial features.

list_attr_celeba.csv: Attribute labels for each image (positive and negative representations for 40 attributes).
