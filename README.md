# Dog breed classificaiton

## Understanding the business:
- There is a number of photos of dogs and humans, defining the proper class for the picture will help us to apply the same knowledge in other areas of object classificaiton.

## Understanding the data:
- We have the images of dogs and humans to build models to detect them and we have other images hwich are not dogs or humans to test the models.

## Preparation of data:

- The data consists of images for dogs and humans (2 datasets) in the form of training set, validation set and testing set for the dog dataset. The human dataset is human faces files to test premade model. The data was already labelled and required to transform them to the correct type and shape in order to be used in the training/testing processes. 

## Modeling:
- Many models have been tested to find the model with the highest accuracy. Firstly, we tried to create a classificaiton model from the scratch using CNN, then Transfer learning using VGG16 and finally transfer learning using VGG19.


## Evaluation:

- After finishing all the training, the models have been evaluated on the testing dataset. The models accuracies were around 5%, 42%, 72% for raw CNN model, VGG16, and VGG19 respectively.   

## Deployment:

- The results of this analysis have been deployed in form of Jupyter notebook and can be used in making Desktop/Web/Mobile application to predict the dog breeds.  

## Final Results:
- Using neural networks is quite powerful espcially in image recognition systems. Despite the fact that they require big datasets and high computionally power but having a classificaiton accuracy around 72% is a great start and there is a huge chance for improvement. The final VGG19 model can classify dogs by breeds.

# Technical aspects:

## **Libraries used in the project:** 
- Pandas
- matplotlib.pyplot
- seaborn
- numpy
- sklearn
- keras
- glob
- random
- cv2