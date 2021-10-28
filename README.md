# Breast Cancer Visualization and Classification

## Abstract
Breast cancer is among the leading cause of mortality among women in developing as well as under-developing countries. The detection and classification of breast cancer in the early stages of its development may allow patients to have proper treatment. In this article, we proposed a novel deep learning framework for the detection and classification of breast cancer in breast cytology images using the concept of transfer learning. In general, deep learning architectures are modeled to be problem specific and is performed in isolation. Contrary to classical learning paradigms, which develop and yield in isolation, transfer learning is aimed to utilize the gained knowledge during the solution of one problem into another related problem. In the proposed framework, features from images are extracted using pre-trained CNN architectures, namely, GoogLeNet, Visual Geometry Group Network (VGGNet) and Residual Networks (ResNet), which are fed into a fully connected layer for classification of malignant and benign cells using average pooling classification. To evaluate the performance of the proposed framework, experiments are performed on standard benchmark data sets. It has been observed that the proposed framework outclass all the other deep learning architectures in terms of accuracy in detection and classification of breast tumor in cytology images.


## Introduction - A Brief Overview on Breast Cancer


## Dataset Description
The Breast Cancer (Wisconsin) Diagnosis dataset contains the diagnosis and a set of 30 features describing the characteristics of the cell nuclei present in the digitized image of a of a fine needle aspirate (FNA) of a breast mass.

Ten real-valued features are computed for each cell nucleus:
- radius (mean of distances from center to points on the perimeter);
- texture (standard deviation of gray-scale values);
- perimeter;
- area;
- smoothness (local variation in radius lengths);
- compactness (perimeter^2 / area - 1.0);
- concavity (severity of concave portions of the contour);
- concave points (number of concave portions of the contour);
- symmetry;
- fractal dimension (“coastline approximation” - 1).