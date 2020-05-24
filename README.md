# Dog-Breed-Classification
Classification of Dog breeds using image files provided
Disaster Response Pipeline-figure 8

Table of Contents

Libraries
Project overview
File Descriptions
Results
Acknowledgements


Python 3 is required to run the anlaysis Python libraries that are used/requires are as follows:

Libraries used:
Numpy
Pandas
np_utils from keras.utils 
glob
cv2 
matplotlib
ResNet50,preprocess_input, decode_predictions from keras.applications.resnet50
image from keras.preprocessing                 
tqdm from tqdm
models, transforms from torchvision
Images and Imagefiles from PIL
Conv2D, MaxPooling2D, GlobalAveragePooling2D, Dropout, Flatten, Dense from keras.layers
Sequential from keras.models import 
ModelCheckpoint from keras.callbacks 


## Project overview

The aim of the project is to classifiy the images into either humans or dogs. If the provided image is a dog, it model should classify it as a dog and provide the relavent breed. If the image is of a human, the model should provide the relavent breed of a dog. If the image passed is neither a dog nor a human face, the model should say the same.

## File Descriptions
dog_app_final- the python notebook illustrated the flow of developing the model and testing it as instructed by the udacity

## Results:
· The final model was able to detect human faces and provide the relevant dog breed.
· It was also able to identify dog faces and proved the probable dog breed they belong to.
· However, the classification among dog breeds was only 60% accurate imposing further improvements.
· Model successfully distinguished the images that are neither dogs nor humans.

## Acknowledgements

This poject is a part of Udacity Nano Degree. Code, templates, and data are provided for the purpose of the project source by Udacity.

## Disclamir

This answer here provided is only for refrence purposes.
