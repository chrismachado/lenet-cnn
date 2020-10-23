# LeNet Convolutional Neural Network
This is a learning project that aims to create a model using CNN LeNet. The model will classify the famous MNIST data set.

## Usage

Cloning this repo using
```commandline
git clone https://github.com/chrismachado/lenet-cnn
```

Install python dependencies with pip
```commandline
pip install -r requirements.txt 
```
Then, if you just want to train and test the model, just type
```commandline
python lenet_mnist.py 
```
Or, you can run pre-trained model in output folder by using the following command
```commandline
python lenet_mnist.py --load-model 1 --weights output/lenet_weights.hdf5 
```

For more information about the script, you can use help command
```commandline
python lenet_mnist.py -h 
```

## Author
- Christiano Machado (christianomachado10@gmail.com | github.com/chrismachado)


## References
This tutorial was made by [Adrian Rosebrock](https://www.pyimagesearch.com/2016/08/01/lenet-convolutional-neural-network-in-python/).