# Dependencies

```pip install -r requirements.txt```

# Training
```python tensorflow_binary_image_classification1.py ```

# TensorFlow-Image-Classification-Convolutional-Neural-Networks

You can read all story from https://medium.com/@mubuyuk51/tensorflow-i%CC%87le-i%CC%87kili-binary-resim-s%C4%B1n%C4%B1fland%C4%B1rma-69b15085f92c in Turkish.

This is a repository containing datasets of 6400 training images and 1243 testing images. 

Classes are table & glass.

Classes are equal(3200 glass - 3200 table). 

There is no high-level API like Keras or TFLearn. Just TensorFlow. I highly recommend training on GPU, rather than CPU.

I trained on GTX 1050. 1 epoch lasted 2 minutes approximately.

There is no problematic image in training and testing dataset.

Download dataset from the link below. It is 101 MB:

https://www.dropbox.com/s/ezmsiz0p364shxz/datasets.rar?dl=0

Extract files from datasets.rar . Then put it in TensorFlow-Image-Classification-Convolutional-Neural-Networks .

train_data_bi.npy is containing 6400 training photos with labels.

test_data_bi.npy is containing 1243 testing photos with labels.

Accuracy score reached 90 percent on CV after 50 epochs.

![alt text](https://github.com/MuhammedBuyukkinaci/TensorFlow-Image-Classification-Convolutional-Neural-Networks/blob/master/accuracy.png)

Cross entropy loss is plotted below.

![alt text](https://github.com/MuhammedBuyukkinaci/TensorFlow-Image-Classification-Convolutional-Neural-Networks/blob/master/loss.png)

1 INPUT LAYER, 4 CONVOLUTION LAYER, 4 POOLING LAYER, 2 FULLY CONNECTED LAYER, 2 DROPOUT LAYER, 1 OUTPUT LAYER.
The architecture used in CNN's is below:

![alt text](https://github.com/MuhammedBuyukkinaci/TensorFlow-Image-Classification-Convolutional-Neural-Networks/blob/master/MY_ARCHITECTURE.png) 
