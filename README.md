# TensorflowExamples
* Implements of famous deepleanrning models using tensorflow
* Some models' implements are from book "TensorFlow实战",黄文坚、唐源，电子工业出版社

## Environment required
   All models are tested based on Tensorflow 1.0.0, other verison may have some API change

## File Introduction
1. Mnist_Softmax.py
   Using softmax to solve Mnist handwritten digits classification
   The MNIST database of handwritten digits, has a training set of 60,000 examples,
   and a test set of 10,000 examples. It is a subset of a larger set available from NIST.
   The digits have been size-normalized and centered in a fixed-size image.
   http://yann.lecun.com/exdb/mnist/

2. Mnist_MLP.py
   Using MLP to solve Mnist handwritten digits classification
   Using dropout and one hidden layer

3. Mnist_LeNet.py
   Using LeNet5 to solve Mnist handwritten digits classification
   LeNet is a Convolutional Neural Network, using maxpooling and conv2d
   http://yann.lecun.com/exdb/lenet/

4. Mnist_AlexNet.py
   - [AlexNet Paper](http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
    AlexNet implements

### If you think this repo may help you, may you star on my project :)