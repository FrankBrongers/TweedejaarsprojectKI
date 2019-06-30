# TweedejaarsprojectKI

### Main functionality (full pipeline): Detection_Execution
### Building CNNs and basic testing for grayscale images: CNN_on_GRAY
### Building CNNs and basic testing for RGB images: CNN_on_RGB

### for 2 classes (robotleg or not) in data/:
	- cnn_test
	- cnn_train

### for 3 classes (robotleg, ball, neither) in data/:
	- ball_data  =  all extra images of balls
	- cnn_test2  =	used test set containing original test and extra ball images
	- cnn_train2 =	used train set containing original train and extra ball images

### CNNTest: shows all the coloured bounding boxes around test set according to used model
