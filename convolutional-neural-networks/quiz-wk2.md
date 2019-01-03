###### 1. Which of the following do you typically see as you move to deeper layers in a ConvNet?
- *n<sub>H</sub>* and *n<sub>W</sub>* decrease, while *n<sub>C</sub>* increases
###### 2. Which of the following do you typically see in a ConvNet? (Check all that apply.)
- Multiple CONV layers followed by a POOL layer
- FC layers in the last few layers
###### 3. In order to be able to build very deep networks, we usually only use pooling layers to downsize the height/width of the activation volumes while convolutions are used with “valid” padding. Otherwise, we would downsize the input of the model too quickly.
- False
###### 4. Training a deeper network (for example, adding additional layers to the network) allows the network to fit more complex functions and thus almost always results in lower training error. For this question, assume we’re referring to “plain” networks.
- False
###### 5. The following equation captures the computation in a ResNet block. What goes into the two blanks above?
###### *a<sup>[l+2]</sup>=g(W<sup>[l+2]</sup>g(W<sup>[l+1]</sup>a<sup>[l]</sup>+b<sup>[l+1]</sup>)+b<sup>l+2</sup>+_______ )+_______*
- a<sup>[l]</sup> and 0, respectively
###### 6. Which ones of the following statements on Residual Networks are true? (Check all that apply.)
- Using a skip-connection helps the gradient to backpropagate and thus helps you to train deeper networks
- The skip-connection makes it easy for the network to learn an identity mapping between the input and the output within the ResNet block
###### 7. Suppose you have an input volume of dimension 64x64x16. How many parameters would a single 1x1 convolutional filter have (including the bias)?
- 17
###### 8. Suppose you have an input volume of dimension *n<sub>H</sub> x n<sub>W</sub> x n<sub>C</sub>*. Which of the following statements you agree with? (Assume that “1x1 convolutional layer” below always uses a stride of 1 and no padding.)
- You can use a pooling layer to reduce *n<sub>H</sub>, n<sub>W</sub>* but not *n<sub>C</sub>* 
- You can use a 1x1 convolutional layer to reduce *n<sub>C</sub>* but not *n<sub>H</sub>, n<sub>W</sub>*
###### 9. Which ones of the following statements on Inception Networks are true? (Check all that apply.)
- 
###### 10. Which of the following are common reasons for using open-source implementations of ConvNets (both the model and/or weights)? Check all that apply.
- 
