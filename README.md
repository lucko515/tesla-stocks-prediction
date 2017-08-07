# Predicting Tesla stock prices with RNNs

This is an example on how to use RNNs to predict stock market price.

I've used LSTM as a type of RNN.

![](lstm_cell.png)
*This LSTM cell image is from [Colah's blog.](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)*

## Dataset

The dataset used in this project is Tesla stocks history (From August 2014 - August 2017). I have downloaded this file from Google stocks, but you have *csv* file inside the project folder. Name of the file is **tesla_stocks.csv**.

## Install

### &nbsp;&nbsp;&nbsp; Supported Python version
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Python version used in this project: 3.5+

### &nbsp;&nbsp;&nbsp; Libraries used

> *  [Pandas](http://pandas.pydata.org) 0.18.0
> *  [Numpy](http://www.numpy.org) 1.10.4
> *  [Matplotlib](https://matplotlib.org) 1.5.1
> *  [Scikit-learn](http://scikit-learn.org/stable/) 0.17.1
> *  [TensorFlow](https://www.tensorflow.org) 1.2.0

## Code

This project has 2 different implementations.

1. Implementation by using Tensorflow built-in RNN functions. This is a version which you would use in an industry. This implementation can be found inside **tensorflow_lstm.ipynb**.

2.  Implementation number 2 has been done without using any high level functions from TensorFlow. This implementation is good for understanding how RNNs are working. This implementations is in file **lstm_from_scratch_tensorflow.ipynb**.

## Run

To run this project you will need some software, like Anaconda, which provides support for running .ipynb files (Jupyter Notebook).

After making sure you have that, you can run from a terminal or cmd next lines:

For the 1st version of the code:

`ipython notebook tensorflow_lstm.ipynb`

or

`jupyter notebook tensorflow_lstm.ipynb`

For the 2nd version of the code:

`ipython notebook lstm_from_scratch_tensorflow.ipynb`

or

`jupyter notebook lstm_from_scratch_tensorflow.ipynb`


## License

IT License

Copyright (c) 2017 Luka Anicin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
