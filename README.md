# Toxic-Comment-Classification

## LSTM + Max-Pooling
Recurrent Neural Networks have been widely used in Text Classification Problems. The variant of RNN known as Long Short term Memory has become popular over the last few years because of its ability to forget and update features that allow it to overcome vanishing and exploding gradient problems. In our problem, Bi-directional LSTM allows us to learn important features in long comments. Moreover, with our use of the 1-D max-pooling layer, we have effectively reduced the dimensionality of the output of the LSTM layer which has improved the ability of the neural network to learn features.

## 2D CNN + Fast Text
2D convolution has been growing in popularity for text classification problems. [13] Its function is to lessen the number of parameters and computation of the spatial size of the representation. The ability of CNNs to take into account spatial and temporal locality of features has made it an excellent tool for text classification problems[8]. We have used four 2D Convolution layers with embedding generated using FastText[3]. In addition, we have set four max-pooling layers to reduce the dimensionality of outputs of convolution layers. 2D CNN has proven to be the most viable classifier for Toxic Comment Classification as per experiments.
