# SNN_tests
This tests are defined to understand [SpikingJelly](https://github.com/fangwei123456/spikingjelly) library.

## MNNIST
This SNN is for number recognition.

To execute the code first you need to go to the folder:

`cd MNIST_tests`

After that, the call needs the model and a image to test what is the number passed. This is a example with the data available:

`python testMNIST.py lif_snn_mnist_simple.ckpt three.png`

The final output is corresponds to a vector from 1 to 9 with a score for the number that has come closest. In the example executed, this is the output:

`[0. 0. 0. 1. 0. 0. 0. 0. 0. 0.]`
