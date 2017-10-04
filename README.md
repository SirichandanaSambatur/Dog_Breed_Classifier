# Dog Breed Classifier
Using Convolutional Neural Networks (CNN) a pipeline is built that can be used within a web or a mobile app to process real world images.
In this project, around 133 different dog breed can be identified from the dog images given to the model. For this project, the pre trained Xception model from
keras has been used.

## Software Requirements
- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- [keras](https://keras.io/)

## Running the Project
1) Clone the repository and navigate to the downloaded folder.
2) Obtain the necessary Python packages, and switch Keras backend to Tensorflow.

For Mac/OSX:

	conda env create -f requirements/aind-dog-mac.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
  
For Linux:

	conda env create -f requirements/aind-dog-linux.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
  
For Windows:

	conda env create -f requirements/aind-dog-windows.yml
	activate aind-dog
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
  
3) Open the notebook and follow the instructions.

	jupyter notebook dog_app.ipynb

