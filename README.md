# 3D Heart Classification

ACDC Challenge from https://www.creatis.insa-lyon.fr/Challenge/acdc/

In the ACDC challenge, our focus was on the classification of five distinct cardiac diseases: normal cases, heart failure with infarction, dilated cardiomyopathy, hypertrophic cardiomyopathy, and abnormal right ventricle. Our approach aimed at achieving this classification automatically through advanced techniques.

We pursued both machine learning and deep learning methodologies for this task. The data we worked with was in the form of 3D files (.nii format).

**Machine Learning:**

- **Feature Extraction:** We extracted ventricle volume and cardiac mass from the 3D files and calculated the ejection fraction based on the extracted values.

- **Classification Methods:** To ensure robust results, we employed various classification techniques including random forest, XGBoost (XGB), multi-layer perceptron (MLP), support vector machine (SVM), logistic regression, and k-nearest neighbors (KNN) classifier.

- **Achievements:** Utilizing machine learning techniques, we achieved remarkable accuracy, with our highest recorded accuracy reaching an impressive 0.97.

**Deep Learning:**

- **Data Preprocessing:** For the deep learning approach, we focused on uniformity in data size by preprocessing the 3D dataset. Furthermore, data augmentation techniques were applied to enhance the dataset's diversity.

- **Model Architecture:** Our classification was performed using a 3D ResNet-18 model, a well-known deep learning architecture.

- **Achievements:** Through deep learning, we achieved competitive results, although slightly lower than the machine learning approach. Our highest accuracy recorded with this method was 0.60. 
