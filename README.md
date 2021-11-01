# Breast Cancer Visualization and Classification

## Abstract
Breast cancer is one of the top causes of death among women in developing and under-developing countries alike. Breast cancer identification and classification in its early stages may allow patients to receive appropriate treatment. Using the notion of transfer learning, we proposes a new deep learning framework for the detection and classification of breast cancer in breast cytology images in this study. In general, deep learning architectures are designed to solve a single problem and are implemented in isolation. Transfer learning, in contrast to traditional learning paradigms that develop and yield in isolation, aims to apply the knowledge learned during the solution of one problem to a related problem. In the proposed system, pre-trained CNN architectures, such as GoogLeNet, Visual Geometry Group Network (VGGNet), and Residual Networks (ResNet), extract features from pictures, which are then input into a fully connected layer for average pooling classification of cancerous and benign cells. To evaluate the performance of the proposed framework, experiments are performed on standard benchmark data sets. It has been observed that the proposed framework outclass all the other deep learning architectures in terms of accuracy in detection and classification of breast tumor in cytology images.

## Introduction - A Brief Overview on Breast Cancer
Breast cancer is a cancer that develops in the breast and spreads to other parts of the body. When cells proliferate out of control, cancer develops. Breast cancer cells typically form a tumor, which can be seen on x-rays or felt as a lump. It's critical to remember that the majority of breast lumps are benign and not cancerous (malignant). Breast tumors that aren't cancerous are abnormal growths that don't spread outside of the breast. Although benign breast lumps are not life threatening, they can raise a woman's risk of developing breast cancer. Any lump or change in your breast should be evaluated by a health care specialist to see if it's benign or malignant (cancer) and if it'll alter your cancer risk in the future. 

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