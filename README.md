This was a Kaggle competition that my friend and I took up. Apples, one of the most
wildly cultivated fruit crops in the world, are constantly under the threat of being affected by a
large number of insects, pathogens, and a wide range of diseases. The task was to do
multi-label disease classification on the given dataset. We implemented two deep learning
models – InceptionV3 and Xception and compared them with the disease labels being: Scab,
frog-eye-leaf-spot, rust, powdery-mildew, healthy specimen, and complex (affected by too many
diseases). We applied transfer learning by utilizing the convolution layers from the pre-trained
Keras implementations of the classification models, added a custom classifier layer to each
model, and trained the model with the Kaggle dataset. We used the Keras ImageDataGenerator
class which provides data augmentation real-time; the model receives new variations of images
(including transformed ones) at every epoch thus saving the memory overhead. We also used a
Multi-label binarizer from preprocessing module of the sklearn class to convert class label
representations to vectors of 0s and 1s. Xception was found to slightly outperform InceptionV3
and the F1 scores achieved were 95.2 and 94.1 respectively.
Publication details
S. Aravind, S. Harini,Varun kumar K A,. 2021.
“IoT Enabled Efficient Detection and Classification of Foliar Disease in Apple Trees”.
Design Engineering, September, 14011-24.
http://thedesignengineering.com/index.php/DE/article/view/4669
