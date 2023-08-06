# Pytorch---DL-framework.
- Classification of 10 categories of images from Fashish MNIST dataset of Pytorch.
- Dataset contains 60000 trainingset grayscale images(28*28) and 10000 testset images.
- Created a model using Pytorch, with 1 input(784*128), 1 Hidden(128*64) Relu, 1 Hidden(64*10) ReLu, 1 Output Layer with 10 nodes and LogSoftmax activation function.
- Also used Autograd functionality of Pytorch to calculate the gradients at backward pass and an optimzer to update the weights accordingly.
- Used the batch size of 64 images.
- Tensors craeted using torch python library are liner with the numpy aarays as they both can point to the same memory location.
- The model created gives an cummulative accuarcy of 85% when inference on gthe 10000 test images is done.

  <img width="640" alt="image" src="https://github.com/priteshjain1990/Pytorch---DL-framework./assets/88549036/329ec349-c13d-4fea-9042-28ec3bbe04a9">

