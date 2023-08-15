# Deep Learning Tutorials

## Note

In the early days of deep learning, **Theano** played a major role in both practical and educational aspects.
Although Theano is no longer in development, and this deep learning tutorials based on it may not be very practical,
but keeps it as a reference for early deep learning implementations.
The only change here is that the equations have been changed from images to javascript renderings.

[Deep Learning Tutorials](https://taneishi.github.io/DeepLearningTutorials/html/)

Theano itself also has some useful parts for creating new frameworks, such as declarative iteration without explicit loops,
generating source code for `nvcc` and `gcc` to accelerate with GPUs and other accelerators..

## Original Description

Deep Learning is a new area of Machine Learning research, which has been
introduced with the objective of moving Machine Learning closer to one of its
original goals: Artificial Intelligence.  Deep Learning is about learning
multiple levels of representation and abstraction that help to make sense of
data such as images, sound, and text.  The tutorials presented here will
introduce you to some of the most important deep learning algorithms and will
also show you how to run them using Theano.  Theano is a python library that
makes writing deep learning models easy, and gives the option of training them
on a GPU.

[Main development](http://github.com/lisa-lab/DeepLearningTutorials) of this project.

## Project Layout

Subdirectories:

- code - Python files corresponding to each tutorial
- data - data and scripts to download data that is used by the tutorials
- doc  - restructured text used by Sphinx to build the tutorial website
- html - built automatically by doc/Makefile, contains tutorial website
- issues_closed - issue tracking
- issues_open - issue tracking
- misc - administrative scripts

## Build instructions

To build the html version of the tutorials, run `sphinx-build doc html`.
