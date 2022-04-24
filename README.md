# Machine-Learning_basic_HW4
Machine-Learning_basic_HW4
Pulmonary Disease Detection

# Goal
- Build a convolutional neural network to predict the pulmonary disease of patients from their chest X-ray (CXR) images.
- You need to deal with limited and  imbalanced data. 

# Please keep the data confidential! // So I did it :)
Dataset: MIMIC-CXR
- MIMIC-CXR dataset is a large publicly available dataset of chest X-ray (CXR) images.
- The dataset contains 377,110 JPG format images and structured labels derived from the 227,827 free-text radiology reports associated with these images.
- In this assignment, we randomly extract 12,500 images for you.

# Basic-prediction
- It is a binary classification problem.
- 0: negative; 1: positive
- Use the training data to predict whether the patient has “Edema”. 
- In this part, any existing model architectures are prohibited, but functions for constructing - models are allowed. You should design you own model architecture.
- You will get all 50 points if your prediction achieves f1-score greater than 0.6 in the testing set.

# Bonus
- If you use the demographic data such as age and gender to improve the model performance and f1-score achieve 0.65, you will get extra 10 points as bonus.
- Illustrate how you combine image data with demographic data in the report and submit an extra prediction for bonus part.  

# Advanced-prediction
- It is a multi-label classification problem.
- Use the training data to predict 7 labels.
- In this part, any state-of-the-art model architectures are allowed.
- Points in this part will be given based on the weighted f1-score of your prediction in testing set. 

# supplements
Tensorflow example: https://www.tensorflow.org/tutorials/images/classification
Pytorch example: https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html

