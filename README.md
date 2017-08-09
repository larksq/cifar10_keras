
# CIFAR10 Keras
This project is for the CIFAR10 Kaggle Competition. The model and best weight in the notebook can guarantee you a 75% accuracy at least. So have fun with that.

## about the test dataset

The Kaggle Competition test dataset has a crazy size of 600,000 images. We have to predict all those images and submit the result. Baking these images into numpy array can cost about 7G space to store and about 20 hours to finish all the transformation. So I split them into pieces to make sure the notebook will not crash at the 19th hour.

## about quiver visualization

[quiver](https://github.com/keplr-io/quiver) is a great tool to visualize my model. See the images in the 'tmp' folder for a glance. The images in 'testvis' are used for generating these black and white images.

# todo
- will HSV space works better than the RGB space?

