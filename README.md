# CapsNet-GAN-Tensorflow Implmentation
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
   <del>-If the CapsNetGANs.py does not work on your machine due to GPU Memory constraint, try CapsNetGANs2.py, in this only the discriminator has the CapsNet layer and thus takes much lesser memory.</del> Optimised for memory constraints.
   
   -Added the CapsNet layer to the generative model, but the entire network hogs a lot of GPU memory, need to find a way to reduce it in the next commit.
   
   -Need to tune hyperparameter so that the GAN gets properly trained.
   
   -Add an option to also train on Fashion MNIST dataset
## Reference
   - https://github.com/llSourcell/Generative_Adversarial_networks_LIVE For EZGAN implementation
   - https://github.com/naturomics/CapsNet-Tensorflow For CapsNet Implementation
