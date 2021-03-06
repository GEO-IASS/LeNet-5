# LeNet-5
卷积神经网络之LeNet-5实现，代码参考了tiny-cnn（https://github.com/nyanp/tiny-cnn ），tiny-cnn这份开源代码质量还是挺高的，但是由于整个项目采用面向对象程序设计思路，外加c++泛型技术，如果想吃透整个项目，除了需要花些时间外，还需要技术功底的。本人在编写LeNet-5网络过程中，有些代码摘录自该项目，相比较而言，本工程更小巧，代码非常容易懂，也非常容易移植，完全不依赖第三方库。

但注意，实际在开发过程中没有用到F6层，主要包括2个卷积层、2个池化层、1个全连接层，外加输入及输出，共7层网络。实际训练时采用最大值池化、双曲正切激活函数，经过8轮迭代训练，手写数字识别准确率即达到99%。

The LeNet-5 implementation of the convolutional neural network is based on tiny-cnn (https://github.com/nyanp/tiny-cnn). Some of the code is extracted from this project. In comparison, my project is more compact, the code is very easy to understand, is also very easy to transplant, completely independent of third-party libraries.

But note that the actual development process is not used in the F6 layer, including two convolutions layers, two pool layers, a fully connected layer, and the input and output layer, a total of seven layers of the network. In practice, the maximal pooling and hyperbolic tangent activation function are adopted. After 8 rounds of iterative training, the accuracy of handwritten numeral recognition is 99%.

![image](https://github.com/uusky/LeNet-5/blob/master/TestLeNet/lenet-5.png)
