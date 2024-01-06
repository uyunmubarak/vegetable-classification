# Optimizing Vegetable Classification with Multilayer Perceptron: A Comparative Study - Deep Learning


---
### -  Introduction/Background
Indonesia is an agricultural country that is rich in agricultural products. The diversity of vegetables has become an important element in everyday life. With a wide variety of vegetables growing in abundance, sometimes identifying each type of vegetable can be a challenging task. Therefore, the vegetable image classification project provides a practical solution by automatically identifying and distinguishing different types of vegetables based on images.

### - Dataset Description
The dataset used comes from Vegetable Image Dataset (kaggle.com). The vegetables that are chosen for the experimentation are- bean, bitter gourd, bottle gourd, brinjal, broccoli, cabbage, capsicum, carrot, cauliflower, cucumber, papaya, potato, pumpkin, radish and tomato. A total of 21000 images from 15 classes are used where each class contains 1400 images of size 224×224 and in *.jpg format. The dataset split 70% for training, 15% for validation, and 15% for testing purpose. 

### - Conclusion
Based on the experimental results, it can be concluded that the Multilayer Perceptron MLP model with Adam optimizer shows good performance. The model is effective in learning patterns from training data, reflected by the increased accuracy on the validation dataset. The use of Adam optimizer is effective in overcoming overfitting problems and accelerating model convergence. MLP model with Adam optimizer achieved training accuracy of 88.40% and validation of 79.66%. However, hyperparameter selection can be a complex process and the results obtained may vary depending on the dataset used.
