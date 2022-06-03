# Breast-Cancer-Detection-Classification

This project aims to predict whether the cancer tumor is malignant or benign using machine learning models. I used 3 different models (Logistic Regression, Random Forest, ANN) to predict the result. This project's credit goes to HERMES AI Excellence Center in Barcelona for motivating me to finally transform this idea into programs and build a tangible outcome related to AI usage in Healthcare.

# Introduction

Breast cancer, the second most common cancer globally after lung cancer, is by far the most frequent cause of cancer death in women [1]. The best approach to lessen breast tumor passing is to recognize it prior. Early finding requires an exact and solid determination method that enables doctors to recognize breast tumors from dangerous ones without going for surgical biopsy [2]. This project is undertaken to recognize malignant and benign tumors from the given characteristics of breast mass computed from the dataset. Using the Breast Cancer Wisconsin (Diagnostic) Database, we can create a classifier that can help diagnose patients and predict the likelihood of breast cancer [3].

# Project Overview

In order to achieve the goal, the following steps are done:

- Exploratory data analysis
- Preprocess data with feature scaling
- Implement Logistic Regression, Random Forest, and ANN models
- Compare the models with evaluation metrics
- Conclusion & Future Work

## About Dataset
Data can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. 

## [*The code and detailed explanation is on the jupyter file*](https://github.com/BabakBar/Breast-Cancer-ML/blob/main/BreastCancer.ipynb)

# Conclusion

Breast cancer is the second leading cause of death in women and represents 11% of cancers detected in Spain [4]. Improvements in diagnosis and treatments have increased the survival of these patients so that it is necessary to speed up subsequent recovery and quality of life, which would therefore reduce healthcare costs. 

This project aims to show the use of AI in healthcare. We saw how the machine learning models could predict the type of cancer diagnosis to facilitate the process of early detection. In the end, the models’ accuracy scores were compared, and the highest result, 98%, showed a proper outcome. This type of AI implications would benefit the patients and doctors to start the treatment as soon as possible. 

# Limitations

While this study delivered meaningful insights, it reflects possible limitations. First, since this project primarily focused on using the ML models, knowledge of in-depth medical factors was excluded, which means we excluded diving into understanding each variable. 

The challenges would remain in training and continuous refinement regarding the model development. A trained network is only as good as the data it learned from. For instance, the network’s output will be skewed if the dataset is skewed. If it included only high-resolution pictures of cancer tumors, there is no telling how it would respond to lower-resolution images.

It is also notable that these tools are not intended to be a solitary channel for cancer detection. Instead, they should be employed as a support method for more accurate evidence decision-making.

# Future Work 

To get a better result, we can make our models more accurate by refining them. This can be done by leveraging more feature selection, ignoring the negative correlations, or removing outliers. Also, for each model, there are some considerations; for example, for the ANN, we can add more hidden layers or change the units. 

With different models, more flexibility would be provided. For example, other approaches like support-vector networks (SVN) classifications, decision trees, or K-means clustering could also be helpful to see which one serves our needs.

This type of AI tool has the ability to be accessible 24/7 to serve patients and doctors remotely. With more advanced technologies, they have the potential to guide patients with personalized data to help them find the proper medical care. Recommend the best specialized medical centers and hospitals for their needs.

# References

[1] Dubey, A. K., Gupta, U., & Jain, S. (2016). Analysis of k-means clustering approach on the breast cancer Wisconsin dataset. International journal of computer assisted radiology and surgery, 11(11), 2033-2047.

[2] Sayed, S., Ahmed, S., & Poonia, R. (2017, November). Holo entropy enabled decision tree classifier for breast cancer diagnosis using wisconsin (prognostic) data set. In 2017 7th International Conference on Communication Systems and Network Technologies (CSNT) (pp. 172-176). IEEE.

[3] UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29
