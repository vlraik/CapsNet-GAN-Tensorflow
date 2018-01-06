# CapsNet-GAN-Tensorflow
An experimental Generative Adversarial Network implementation of the Capsule Neural Network. It is based on the recent works on Dynamic Routing between Capsules:
reference: [Dynamic routing between capsules](https://arxiv.org/abs/1710.09829v1) by **Sara Sabour, Nicholas Frosst, Geoffrey E Hinton**

## Requirements
  - Tensorflow
  - Numpy
  - Pandas
  - DateTime
  - Matplotlib
 
## Installation
  `pip install -r requirements.txt`
 
## Training
   python CapsNetGANs.py

## Training Details
   Currently the initial commit is implemented to train on the domains of the MNIST Dataset.

## Results
   Resulting generated images of the network are on the way. I'll soon commit them.
  
## Note
   -As of the initial commit, only the discriminator is has the CapsNet implementation, in the next update, I'll change the generative model also have CapsNet layer in order to make the GAN more stable.
   -Need to tune hyperparameter so that the GAN gets properly trained.
   
   -Add an option to also train on Fashion MNIST dataset
## Reference
   - https://github.com/llSourcell/Generative_Adversarial_networks_LIVE For EZGAN implementation
   - https://github.com/naturomics/CapsNet-Tensorflow For CapsNet Implementation
