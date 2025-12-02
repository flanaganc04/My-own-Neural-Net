This Neural Network is a digit recognizer for the MNIST handwriting data set. 

Heres the read me, these fist couple of commits are just gonna be initial updates and making sure Im pushing to github from google colab.
Created basic functions, met with Dr. Malec and looking to move towards a class oriented algorithm
Completed MNIST Neural Net class with customizable learning rate, nueron structure, batch sizes, and epochs. Comes as a complete class with example code in the same notebook. Loss function set to categorical cross entropy. Activation set as RELU and SOFT MAX.
Completed hyperparameter tuning with 1 sample

Ideas for the Future: add more loss functions, and more activations, create a grid search function, hyperparameter tune with more than 1 sample (get mean and std for those plot[for loop plus array of values]) think about what that 10 in the one hot encoder means (how can you softcode that for more applications outside of MNIST)

The presentation created in Latex was given as part of a Math Club event for Hood College on 12/3/2025 and was made with Patrick Vasallo.

References:
The test and train digits come from https://www.kaggle.com/competitions/digit-recognizer/overview and are from the MNIST (Modified National Institute of Standards and Technology) handwriting data set.
https://www.w3schools.com/python/ref_math_exp.asp
https://numpy.org/doc/2.1/reference/random/generated/numpy.random.uniform.html
https://numpy.org/doc/2.1/reference/generated/numpy.argmax.html#numpy-argmax
https://stackoverflow.com/questions/6392739/what-does-the-at-symbol-do-in-python
