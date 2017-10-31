[//]: # (Image References)

[image1]: ./images/for_README_1.PNG "Sample Dog Image"
[image2]: ./images/for_README_2.PNG "Sample Human Image"

Dog Breed Classifier
====================

Built an algorithm to identify canine breed given an image of a dog. If given image of a human, the algorithm identifies a resembling dog breed.

Techniques Implemented
----------------------

1. Deep Convolutional Neural Networks
2. Transfer Learning

Project Overview
----------------

Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. 

![Sample Dog Image][image1]

If supplied an image of a human, the code will identify the resembling dog breed.

![Sample Human Image][image2]

Project Instructions
--------------------

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/MrinalJain17/Machine-Learning-Nanodegree.git
		cd dog-project
	```
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/`.
3. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/`.
4. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.
5. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  

	For __Mac/OSX__:
	```
		conda env create -f requirements/aind-dog-mac.yml
		source activate aind-dog
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Linux__:
	```
		conda env create -f requirements/aind-dog-linux.yml
		source activate aind-dog
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f requirements/aind-dog-windows.yml
		activate aind-dog
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
	```
6. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```

__Note:__ Some code was already been implemented in the project. The cells marked as `(Implementation)` were implemented by me.