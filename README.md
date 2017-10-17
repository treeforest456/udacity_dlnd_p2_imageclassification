# udacity_dlnd_p2_imageclassification
udacity_dlnd_p2_imageclassification

## Project Overview
In this project, I classified images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html). The dataset consists of airplanes, dogs, cats, and other objects. The dataset was preprocessed, then trained a convolutional neural network on all the samples. I normalized the images, one-hot encode the labels, built a convolutional layer, max pool layer, and fully connected layer. At then end, I saw their predictions on the sample images.

## Steps

1. Get the data and explore
```python
Stats of batch 1:
Samples: 10000
Label Counts: {0: 1005, 1: 974, 2: 1032, 3: 1016, 4: 999, 5: 937, 6: 1030, 7: 1001, 8: 1025, 9: 981}
First 20 Labels: [6, 9, 9, 4, 1, 1, 2, 7, 8, 3, 4, 7, 7, 2, 9, 9, 9, 3, 2, 6]

Example of Image 13:
Image - Min Value: 0 Max Value: 244
Image - Shape: (32, 32, 3)
Label - Label Id: 2 Name: bird
```

2. Preprocess the data
	* Normalize
	* One-Hot Encode

3. Build the Network
	* Input layer
	* Convolution and Max Pooling Layer
	* Flatten Layer
	* Fully-Connected Layer
	* Output Layer
	* Create Convolutional Model
		* Apply 1, 2, or 3 Convolution and Max Pool layers
		* Apply a Flatten Layer
		* Apply 1, 2, or 3 Fully Connected Layers
		* Apply an Output Layer
		* Return the output
		* Apply [TensorFlow's Dropout](https://www.tensorflow.org/api_docs/python/tf/nn/dropout) to one or more layers in the model using keep_prob

4. Train the Network
	* Single Optimization
	* Show Stats
	* Hyperparameters
	* Train

5. Test the model
* Testing Accuracy: 0.686807753164557
