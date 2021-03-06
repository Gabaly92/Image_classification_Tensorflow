# Machine Learning Engineer Nanodegree
# Deep Learning
## Project: Image classifiaction with TensorFlow

### Install

This project requires **Python 3.xx and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [TensorFlow](https://www.tensorflow.org) 

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

Template code is provided in the `image_classification.ipynb` notebook file. You will also be required to use the included `helper.py` Python file and the `cifar-10` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project.

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook image_classification.ipynb
```  
or
```bash
jupyter notebook image_classification.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

In this project, you'll classify images from the CIFAR-10 dataset. The dataset consists of airplanes, dogs, cats, and other objects. The dataset will need to be preprocessed, then train a convolutional neural network on all the samples. You'll normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, you'll see their predictions on the sample images.

**Target Variable**
- `Image Class`: airplane, dog, cat, and other objects.
