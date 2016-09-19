# Street View House Numbers
- 1-preprocess.ipynb: preprocess SVHN data.
- 2-recognition.ipynb: builds a convolutional neural network to recognize numbers from SVHN dataset

## Dataset

This project uses the [The Street View House Numbers (SVHN) Dataset](http://ufldl.stanford.edu/housenumbers/).

SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting. It can be seen as similar in flavor to MNIST (e.g., the images are of small cropped digits), but incorporates an order of magnitude more labeled data (over 600,000 digit images) and comes from a significantly harder, unsolved, real world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images. 

## Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [TensorFlow](http://www.tensorflow.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [SciPy library](http://www.scipy.org/scipylib/index.html)
- [Six](http://pypi.python.org/pypi/six/)

You will also need to have [iPython Notebook](http://ipython.org/notebook.html) installed to run and execute code

## Code

Code is provided in the following notebook files:
- `1-preprocess.ipynb`
- `2-recognition.ipynb`

## Execute

In a terminal or command window, navigate to the top-level project directory `P5-Capstone/` (that contains this README) and execute following commands:

```jupyter notebook 1-preprocess.ipynb```  
```jupyter notebook 2-recognition.ipynb```

This will open the iPython Notebook and open file in your browser.