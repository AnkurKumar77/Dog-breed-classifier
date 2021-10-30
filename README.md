# Dog-breed-classifier

[This is the capstone project for Udacity Data Scientist Nanodegree Program]

## Libraries Used

```
Tensorflow
Matplotlib
sklearn
pandas
Keras
OpenCV
Numpy
tqdm
cv2
glob
```
## Project Motivation

Identifying a dog’s breed is such a difficult task that even a human is confused sometimes.In this project, we build a pipeline which can process images of dogs given by the user. 
The algorithm will give an estimate for the dog's breed. If the image includes a human, then the algorithm will give the resembling dog breed.

The project consists of the following steps:

### Step 1:
Detecting presence of human faces in the given image.

### Step 2:
Detecting presence of dog in the given image.

### Step 3: 
Building a CNN architecture from scratch for predicting dog breeds.

### Step 4:
Using transfer learning to create a CNN to classify dog Breeds.

## File Description

```
haarcascade   : contains the haarcascade xml file which detects human faces
saved_model   : includes models saved during the training process
testing_images: images which were used to get the model predictions
dog_app.html  : Copy of dog_app.ipynb in html format
dog_app.ipynb : Jupyter notebook which contains the analysis and model training code
```

## Summary

we trained a custom CNN from scratch but due to lack of data and time we could only get test accuracy of around 8%.
To tackle the above problem, we used a very powerful technique known as transfer learning to train our model which showed incredible improvement and got test accuracy of 82% approx.

Detailed discussion can be found at this [blog](https://medium.com/@ankur_kumar/identify-the-dogs-breed-using-neural-network-d571cd7f1459)


