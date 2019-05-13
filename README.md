# SET Card Recognition
Goal: Create a mobile app to take pictures of [SET®](https://www.setgame.com/) cards and recognize if a set exists in the given cards.

Using https://medium.com/@dganais/ready-set-image-recognition-720be22d7051 as a starting point, we want to
explore image recognition strategies and deep learning models to accurately identify SETs in a group of cards.

## Data

There are 81 distinct SET cards. 

The attributes of these cards can be divided into 4 categories:

 * Shapes: diamond (D), oval (O), squiggle (S)
 * Color: red (R), green (G), purple (P)
 * Pattern: full (F), striped (S), empty (E)
 * Number: one (1), two (2), three (3)
 
 *****add image, and describe naming scheme
 
 ### Creating the dataset
 
 We took around 100 photos of each SET card with a variety of backgrounds, lighting conditions, and angles using three different phones.
 
 Our data can be found in two folders, *pre-processed* and *processed*. 
 The original images of our cards are stored in *pre-processed*.
 We resized our images to *size by size* pixels using *OpenCV* and placed them in *processed*.
 
 ## Software
 
 Python (version)  
 OpenCV (version)  
 Tensorflow (version)  
 
 
 ## File Directory
  
 ## Stages
 
 **1. Collect the data.**
 
 Goal is to get at least 100 images for each card type. In addition, we will add images from Anais Dotis's and Tom White's githubs to supplement our data. 
 
 **2. Start with three card types and create a neural network classifier.**
 
 Goal is to learn how to do image processing and create a convolutional neural network that can accurately classify three cards. 
 
 **3. Expand to all 81 card types and develop a neural network classifier.**
 
 **4. Image detection**
 
 **5. Develop the app using Android Studio.**
 
 
 ## Acknowledgements
Anais Dotis  
https://github.com/Anaisdg/OpenCV  
Her fantastic Medium article of her project: https://medium.com/@dganais/ready-set-image-recognition-720be22d7051

Tom White
https://github.com/tomwhite/set-game  
Great blog post of his project: https://blog.cloudera.com/blog/2017/10/understanding-how-deep-learning-learns-to-play-set/
 

