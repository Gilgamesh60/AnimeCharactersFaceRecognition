# Cartoon character classification
___________________________________

## Motivations
   My main motivation behind this project is that there are thousands of cartoon\anime characters from various animes. It becomes extremely frustating to find the name of the character you see on twiiter/instagram. So right now I am doing this project on small scale for only 10 characters.One day I want to execute this on much bigger scale.


## Data preparation
-I have prepared the Data for this project from Google Images. Inorder to achieve more accurate classification, Dataset can be prepared from own Images because Google Images are not always accurate, it might contains Duplicate Images, Misplaced or Misclassified Images and many more which will utlimately affect the accuracy of the Model. Despite of those challenges, this Model can still classify Images with High Accuracy.
-To prepare the Data from Google Images, you will to go [Google Images](https://www.google.co.in/imghp?hl=en&tab=ri&ogbl) and search for the images you are interested in.The more specific you are in your Google Search, the better the results and the less manual pruning you will have to do. Then you should copy and paste the following Javascript.
-For this I have made a web-scraper in python using selenium and collected the images of 10 different cartoon character

## Using Computer vision to detect faces
This includes-face detection and cropping the face out of original images

## Snapshot of input images

![Untitled document (4)-1](https://user-images.githubusercontent.com/104096164/192888515-5c4de528-98b9-4443-bfab-0c845cc019bf.png)


## Training the model 
For this I have implemented two different models. One is a simple CNN model using TensorFlow & Keras. And second a SVM classifier. We will compare  these two models 7 choose the best one. I have included both code templates.
![Screenshot 2022-09-30 133037](https://user-images.githubusercontent.com/104096164/193221783-a32e0183-f2ff-4847-96f8-0c50aa12771e.png)


## Model Performance
Here I am showing the performande of my CNN model on each epoch.

