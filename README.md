# MSDS19033_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

## Part 1
## DataSet
https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK&authuser=0

## Tuning Weights Link

https://drive.google.com/open?id=1TFjIwvYr7faSxU7sfkuofxHjJRdPB51w

## Accuracies and Confusion Matrix

## Addition of FC layers and Fine Tuning of FC layers only

###### VGG-16:

No. of Layers fined tuned = All FC layers

- Validation:
  
  Confusion matrix:
  
   ![](images/vgg1.png)

  Accuracy = 59%
  
  F1 Score = 32%
  
- Testing:

  Confusion Matrix:
    
   ![](images/vgg2.png)

    
  Accuracy = 59%
  
  F1 Score = 44%
  
###### Res-Net18:


No. of Layers fined tuned = All FC layers

- Validation

  Confusion matrix:
    
  ![](images/rss1.png)

    
  Accuracy = 91%
  
  F1 Score = 89%
  
- Testing

  Confusion Matrix:
  
  ![](images/rss2.png)

  Accuracy = 96%
  
  F1 Score = 99%

## Fine Tuning of Entire Network

###### VGG-16:

No. of Layers fined tuned = All FC Layers + Conv Layers

- Validation

  Confusion matrix:
  
   ![](images/vgg3.png)

  Accuracy = 59%
  
  F1 Score = 23%
  
- Testing

  Confusion Matrix:
  
   ![](images/vgg4.png)

  Accuracy = 59%
  
  F1 Score = 32%
  
###### ResNet18:

- Validation

  Confusion matrix:
  
  ![](images/rss3.png)

  Accuracy = 91%
  
  F1 Score = 89%
  
- Testing

  Confusion Matrix:
  
   ![](images/rss4.png)

  Accuracy = 96%
  
  F1 Score = 100%
  
## Fine Tuning of Few Layers

###### VGG16

No. of Layers fined tuned = All FC Layers + Few Conv Layers

- Validation

  Confusion matrix:
  
   ![](images/vgg5.png)

  Accuracy = 55%
  
  F1 Score = 49%
  
- Testing

  Confusion Matrix:
  
   ![](images/vgg6.png)

  Accuracy = 56%
  
  F1 Score = 49%

###### ResNet18:

- Validation

  Confusion matrix:
  
  ![](images/rss5.png)

  
  Accuracy = 91%
  
  F1 Score = 89%
  
- Testing

  Confusion Matrix:

  ![](images/rss6.png)

  Accuracy = 96%
  
  F1 Score = 100%
  
## Part 2

## DataSet
https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view

## Weights Link
https://drive.google.com/drive/folders/1xTIQqC-7zRdrmzLrQH9JVOgaWU0G4mE3?usp=sharing

## BCEWithLogitsLoss 

- VGG-16

  ![](images/simplevgg.PNG)
  
  
- ResNet18

  ![](images/simpleres.PNG)
  
## Focal Loss

- VGG-16

  ![](images/focalvgg.PNG)

- ResNet18

  ![](images/focalres.PNG)
