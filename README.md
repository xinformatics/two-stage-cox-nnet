#  Two-stage cox-nnet

This is the package of 2-stage coxnnet, which is an extension of original coxnnet developed by Travers. (https://github.com/traversc/cox-nnet)

### Two-stage cox-nnet has two phases:
* Train Cox-nnet on image data (*1st phase*)
* Train Cox-nnet on gene data (*1st phase*)
* Hidden nodes integration of two data types
* Train Cox-nnet on integrated hidden features (2nd phase)

### Package Requirements
* Python 2.7 
* Theano 1.0.0
* Run faster on GPU
