# Computer Vision
 Computer Vision Projects


## 1. Day and Night Classifier:

<p float="center">
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/1.jpg?raw=true" width="200" /> 
    <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/2.jpg?raw=true" width="200" /> 
</p>

## 2.Regularization and Data Augmentation:

plant images at different resolution captured with a variety of cameras,there are images showing plants with approximatelty 1,2,3,4 and 6 leafs.
<p float="center">
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/7.png?raw=true" width="200" /> 
    <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/8.png?raw=true" width="200" /> 
</p>
We used both classification and regression VGG16 model, the classification model performed better. Hence we made 3 models with different image processing techniques.
- The classification model with batch normalization overfitted.
- The classification model with dropout underfitted
- The classification model with data augmentation overfitted.
Here is the learning curves from left to rigth in order:
<p float="center">
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/9.png?raw=true" width="250" /> 
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/10.png?raw=true" width="250" /> 
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/11.png?raw=true" width="250" /> 
</p>

## 3. Upside Down Detector:

Train a model to detect if images are upside down using the mnist dataset.<br>
The true label is the image is flipped (represents the number 9), while the model sees it as it's non-flipped 6.
The true label is the image is not flipped, while the model sees it as it's flipped 8.

<p float="center">
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/15.png?raw=true" width="250" /> 
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/16.png?raw=true" width="250" /> 
  <img src="https://github.com/khadija267/Computer-Vision/blob/main/images/17.png?raw=true" width="250" /> 
</p>

Model Performance:

              precision    recall  f1-score   support

           0       0.68      0.80      0.73       500
           1       0.77      0.95      0.80       500 


