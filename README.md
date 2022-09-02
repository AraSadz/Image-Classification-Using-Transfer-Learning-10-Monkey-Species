# Image-Classification-Using-Transfer-Learning-10-Monkey-Species
We utilize Transfer Learning to classify the images.  Two pretrained NNs are employed, i.e. MobileNetV2 and Inception V3.

Image Classification Using Transfer Learning: 10 Monkey Species
Author: Arash Sadeghzadeh

Data for this notebook can be retrieved from the following URL: https://www.kaggle.com/datasets/slothkong/10-monkey-species

The dataset consists of two files, training and validation. Each folder contains 10 subforders labeled as n0~n9, each corresponding to a species. Images are 400x300 px or larger and JPEG format.
This dataset is intended as a test case for fine-grain classification tasks
We utilize Transfer Learning to classify the images. Two pretrained NNs are employed, i.e. MobileNetV2 and Inception V3.
Table of Content
Exploring Data
Some Samples
Functions
Using MobileNetV2
Using InceptionV3 Model
Conclusion

Note that you need first to download these two files:
1- mobilenet_v2_weights_tf_dim_ordering_tf_kernels_1.0_224_no_top.h5 \
2- inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5 

These are the weights for trained mobilenetV2 and InceptionV3 models trained using imagenet. The following links can be used to download these files: \
 1- https://storage.googleapis.com/tensorflow/keras-applications/mobilenet_v2/mobilenet_v2_weights_tf_dim_ordering_tf_kernels_1.0_224_no_top.h5 \
 2- https://storage.googleapis.com/tensorflow/keras-applications/inception_v3/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5
 
