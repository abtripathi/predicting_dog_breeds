# Predicting Dog Breeds

In this project, a pipeline is built to process real-world, user-supplied images. Given an image of a dog, algorithm will identify an estimate of the canine’s breed. If supplied an image of a human face, the code will identify the resembling dog breed.

I used OpenCV Cascade classifier as a face detection algorithm.I also tried another face detector algorithm using OpenCV 'dnn' module and performance of both the algorithms are measured.

For classifying Dog breeds, I first built a CNN from scratch with the model achieving accuracy of ~ 12% using 60 epochs of training on GPU,then moved on to using VGG16 pretrained network to create a CNN to build a classifier using transfer learning. With 10 epochs of training on GPU device, this model was easily able to get an accuracy of 76%
