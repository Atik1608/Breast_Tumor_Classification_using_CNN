
# Breast Tumor Classification using Convolutional Neural Network (CNN)

### NOTE:- The dataset is not included here, as it was given and performed under the license of Professor's work. The dataset is not publicly available and the project has been performed as a capstone final for Computer Vision coursework.

Designed a deep learning model using Convolutional Neural Network and transfer learning for classifying breast tumor (Benign/Malignant) by looking at real ultra-sound images of tumors.

##### Programming Language: Python
##### Library: Keras with TensorFlow backend

#### Experiments:
___________________

1. Classification using own custom CNN model.

2. Classification using feature extraction based on VGG16. In feature extraction, the convolutional base of the VGG16 has been frozed and by extracting its features, our own custom model has been trained on top of it.

3. Classifiction using Fine-Tuning the VGG16. In Fine-Tuning, we unfrozed last 3 layers of VGG166 convolutional base and trained those 3 layers, plus our own custom classifier to better extract generic features at the starting layers and more specific at the top layers.



###### Special NOTE:- These notebooks can be used as a reference by anyone, who wants to learn these common techniques used when data size is small. By following similar patterns, you can use these notebooks for binary and multi classification of any image data.

