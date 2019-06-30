# TweedejaarsprojectKI

### Detection_Execution: Main functionality (full pipeline)
### CNN_on_GRAY: Building CNNs and basic testing for grayscale images
### CNN_on_RGB: Building CNNs and basic testing for RGB images
### draw-predefined-labels: a visualisation of the labels from BitBots-Tagger on the NaoDevils data

### for 2 classes (robotleg or not) in data/:
	- cnn_test
	- cnn_train

### for 3 classes (robotleg, ball, neither) in data/:
	- ball_data  =  all extra images of balls
	- cnn_test2  =	used test set containing original test and extra ball images
	- cnn_train2 =	used train set containing original train and extra ball images

### CNNTest: shows all the coloured bounding boxes around test set according to used model

### for saving the test images with coloured bounding box on them. Color is generated by the label the CNN gives the box.
	- TestBoxes_GRAY: for CNN and test images on gray scaled images
	- TestBoxes_RGB: for CNN and test images on RGB images


### cnn_data5 : images used for either training or testing on original image set

