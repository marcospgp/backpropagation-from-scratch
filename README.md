# backpropagation-from-scratch
 A python notebook that implements backpropagation from scratch and achieves 85% accuracy on MNIST with no regularization or data preprocessing.
 
 The neural network being used has two hidden layers and uses sigmoid activations on all layers except the last, which applies a softmax activation. The cost function used is cross entropy, and the layer sizes (in neurons) are 784 (input), 32, 32, and 10.
 
 Includes [a PDF](/backpropagation-from-scratch.pdf) with the theoretical foundations, also available [on mathcha](https://www.mathcha.io/editor/vrmV3C1KFnvu2Dx3ewh7rgr54fBOvJL2TzoNWNe).
 
## Why I made this

I decided it was important to build an intuitive understanding of backpropagation, and to be able to derive everything on paper in case I was suddenly transported back to victorian London.

## How long it took me

One month, during which I noticed an obvious increase in my ability to turn element-wise expressions into linear algebra using the power of imagination.
