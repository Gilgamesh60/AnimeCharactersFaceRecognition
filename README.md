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
I have implemented a CNN model in tensorflow and keras. It's giving me almost 80% accuracy. You can see the code template below.

![Screenshot 2022-09-30 130706](https://user-images.githubusercontent.com/104096164/193219818-5c529a0d-a12d-4591-b166-53cd085da197.png)

## Model Performance
