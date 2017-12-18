# Human-Activity-Recognition
Recognizing human activities using Deep Learning

## Dataset
[Recognition of Human Actions](http://www.nada.kth.se/cvap/actions/)

- [Walking.zip](http://www.nada.kth.se/cvap/actions/walking.zip)
- [Jogging.zip](http://www.nada.kth.se/cvap/actions/jogging.zip)
- [Running.zip](http://www.nada.kth.se/cvap/actions/running.zip)
- [Boxing.zip](http://www.nada.kth.se/cvap/actions/boxing.zip)
- [Handwaving.zip](http://www.nada.kth.se/cvap/actions/handwaving.zip)
- [Handclapping.zip](http://www.nada.kth.se/cvap/actions/handclapping.zip)

There are a total of 599 videos, with each category having 100 videos (with the exception of `Handclapping` having 99 videos).

All the videos were captured at *25fps* frame rate. Each video has a spatial resolution of 160x120 pixels.

## Instructions
1. Clone the repository and navigate to the downloaded folder.

	```
		git clone https://github.com/MrinalJain17/Machine-Learning-Nanodegree.git
		cd Machine-Learning-Nanodegree/capstone_proposal
	```
2. Unzip the compressed data files and store in the format as mentioned [here](https://github.com/MrinalJain17/Machine-Learning-Nanodegree/blob/master/capstone_proposal/Directory%20Structure%20for%20Data.txt)
	- Use the helper function `download_files()` present in `data_utils.py` as follows to do this in your current working directory automatically. (The function will delete the compressed files after they are successfully extracted)

	```python
		import data_utils
		
		data_utils.download_files()
	```
3. The following file is corrupted which gives an error when being loaded. **Delete it before proceeding**.

	`'person01_boxing_d4_uncomp.avi'` (present in `Data/Boxing/`)

## Requirements
`Python 3.x` (preferably from the [Anaconda Distribution](https://www.anaconda.com/download/))

Install `FFmpeg` on your machine

For **Linux**:

		$ sudo apt-get update
		$ sudo apt-get install libav-tools

For **Windows or MAC/OSX**:  
Download the required binaries from [here](https://www.ffmpeg.org/download.html). Extract the zip file and add the location of binaries to the `PATH` variable

### Additional Libraries:

- [Scikit-video](http://www.scikit-video.org/stable/)

	```
		pip install sk-video
	```

- [Tensorflow](https://www.tensorflow.org/install/)

	```
		pip install tensorflow
	```
	For GPU support or a custom installation, follow the instructions given on the Tensorflow website.

- [Keras](https://keras.io/#installation)

	```
		pip install keras
	```
- [tqdm](https://pypi.python.org/pypi/tqdm#installation) - Required for displaying the progress bar.

	```
		pip install tqdm
	```
