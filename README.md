# Project-BootCamp--dPhi-on-Animal-Classification-Problem
Context
Image recognition is a vital component in robotics such as driverless vehicles or domestic robots.
Image recognition is also important in image search engines such as Google or Bing image search whereby you use rich image content to query for similar stuff. 
Like in Google photos where the system uses image recognition to categorize your images into things like cats, dogs, people and so on so that you can quickly search your albums for things like, “give me photos of my cat”, that's awesome.

Objective
You are working on a robotics project where you are required to train your robot so that it can differentiate between 5 animals or birds. 
Your task here is to build a deep learning model that helps you recognize the animal or bird in images.

About the Data
The training dataset consists of about 9k medium quality animal images belonging to 5 categories: butterfly, sheep, cow, squirrel, elephant. - mucca (cow), pecora (sheep), elefante (elephant), farfalla (butterfly) and scoiattolo (squirrel). All the images have been collected from "google images" and have been checked by human. There is some erroneous data to simulate real conditions (eg. images taken by users of your app).

Dataset Link:https://drive.google.com/file/d/176E-pLhoxTgWsJ3MeoJQV_GXczIA6g8D/view?usp=sharing

From the above link you will be able to download a zip file named ‘animal_dataset_intermediate.zip’. After you extract this zip file, you will get three files:

train - contains five folders each folder containing images around 1000 to 2000 of those 5 five animals.  Each image has a unique name.
test - contains 910 random images of those 5 animals whose predictions you are to submit on DPhi platform.
Testing_set_animals.csv - this is the order of the predictions for each image that is to be submitted on the platform. 
Make sure the predictions you download are with their image’s filename in the same order as given in this file.

summary:

Conclusion:
This model is best fit and able to make the prediction with training dataset with 98% of accuracy.
We have used transfer Learning technique with Inception_V3 and used Image Data generator to load the dataset
