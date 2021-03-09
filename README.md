## Dog Breed Classifier
Multi-Class classification of dog breeds.

## Dataset 
[Kaggle Dataset](https://www.kaggle.com/c/dog-breed-identification)

## Description
Notebook contains:
1. Data Exploration
2. Problem Solutions:
   1. Using Traditional Machine Learning
   2. Using Deep Learning
3. Visualization

## 1. Data Exploration
Checking for null values, unique number of labels.

## 2. Problem Solutions
Comparing the usage of traditional machine learning vs deep learning.

![Traditional vs Deep Learning](![image](https://user-images.githubusercontent.com/25401067/110433329-451b0280-80eb-11eb-9b91-a9935d228f1c.png)
[Link](https://towardsdatascience.com/why-deep-learning-is-needed-over-traditional-machine-learning-1b6a99177063)
Traditional Machine Learning:
- Feature extraction will be done using [InceptionV3](https://keras.io/api/applications/inceptionv3/).
- Classification will be done using Random Forest and Neural Network.

Deep Learning:
- [EfficientNet Neural Network](https://keras.io/api/applications/efficientnet/).


## 3. Visualization
Requires the use of [magick](http://www.besavvy.com/documentation/4-5/Editor/031350_installimgk.htm)

Loading metadata and feature vectors into tensorboard projector will produce the result as below for visualization purposes.

![Tensorboard Projector](https://github.com/junxtjx/Dog-Breed-Classifier/blob/main/Images/tensorboard.PNG)


## Credits
[1](https://machinelearningmastery.com/convolutional-layers-for-deep-learning-neural-networks/)

[2](https://medium.com/@14prakash/understanding-and-implementing-architectures-of-resnet-and-resnext-for-state-of-the-art-image-cf51669e1624)

[3](https://machinelearningmastery.com/rectified-linear-activation-function-for-deep-learning-neural-networks/#:~:text=The%20rectified%20linear%20activation%20function,otherwise%2C%20it%20will%20output%20zero.&text=The%20rectified%20linear%20activation%20function%20overcomes%20the%20vanishing%20gradient%20problem,learn%20faster%20and%20perform%20better)

[4](https://lisaong.github.io/mldds-courseware/01_GettingStarted/numpy-tensor-slicing.slides.html)

[5](https://medium.com/@kumon/visualizing-image-feature-vectors-through-tensorboard-b850ce1be7f1)

[6](https://cloud.google.com/tpu/docs/inception-v3-advanced)

## License
[MIT](https://choosealicense.com/licenses/mit/)
