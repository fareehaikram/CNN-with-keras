# CNN-with-keras

The goal is to build a convolution neural network(CNN) based on VGG or ResNet architecture in order to classify intel image classification dataset.
It consists of 25000 images of 150x150 size.Theses are labeld into 6 classes  {'buildings' -> 0, 'forest' -> 1, 'glacier' -> 2, 'mountain' -> 3, 'sea' -> 4, 'street' -> 5 }. The dataset is available for download at https://www.kaggle.com/puneet6060/intel-image-classification.
I have used transfer learning for my model.ImageNet weigths are used for the convolutional base and Classifier is trained for the specific dataset.
The weigths are available at https://drive.google.com/file/d/1Et8TpXiFoCaaE-SpVX6VlFEO719Q3xEL/view?usp=sharing.I have also shared the drive link as https://drive.google.com/drive/folders/1aIgQy0xKHeUtE8NdqfLfBa71WV3jUKKW?usp=sharin.You can use this link to run the code.
Moreover Data augmentation has been used.

<br /> The CNN model achieved test accuracy of 89%.Some visual results are shown
<br/>
![all text](https://github.com/fareehaikram/images/blob/main/adam0001.JPG)
![all text](https://github.com/fareehaikram/images/blob/main/heat.JPG)

