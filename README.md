# Image Classifier
#### A Convolutional Neural Networks based Image Classifier
## Why CNN is used?
Image classification involves extracting features from the image to observe some patterns in the dataset. Using an ANN for image classification would be very costly in terms of computation since the trainable parameters become extremely large. Filters help us exploit the spatial locality of a particular image by enforcing a local connectivity pattern between neurons.

## Dataset Used - 
The CIFAR-10 Dataset (https://www.cs.toronto.edu/~kriz/cifar.html) <br>
 The CIFAR-10 dataset consists of 60000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining photos in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.<br>
![Screenshot 2023-07-10 173034](https://github.com/saksham1000-mish/Image_Classifier/assets/114898997/f44f3efe-f522-45c1-a291-c93104b8bdf3)

 ## Accuracy and Graphs
 The training data acquired an accuracy of 82.94% which contains 50000 examples <br>
 The test data acquired an accuracy of 70.21% which contains 10000 examples<br>

![graph1](https://github.com/saksham1000-mish/Image_Classifier/assets/114898997/6da83e68-bdc8-4414-ae65-f68c5d9061cc)
![graph 2](https://github.com/saksham1000-mish/Image_Classifier/assets/114898997/ebd00f9b-fb15-495d-88af-640b824e576d)

## Predictions made by the model <br>
#### Here are some of the predictions made by the model

![deer](https://github.com/saksham1000-mish/Image_Classifier/assets/114898997/756e1e92-7782-4476-be65-23e4a04bf135)
![horse](https://github.com/saksham1000-mish/Image_Classifier/assets/114898997/96787805-d484-4e61-b01b-b4e05acb903e)
![bird](https://github.com/saksham1000-mish/Image_Classifier/assets/114898997/d7f9ad74-31e4-4fa1-b813-f056a375369d) <br>

## Conclusion <br>
In conclusion, CNN image classification has revolutionized the field of computer vision, enabling accurate recognition of objects within images. With its ability to automatically learn and extract complex features, CNNs have become a powerful tool for various applications.

