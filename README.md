# PyTorch Implementation of “Unsupervised learning by competing hidden units” MNIST classifier, combining with Feedback alignment.
This reprository is a PyTorch implementation of the paper ["Unsupervised learning by competing hidden units"](https://www.pnas.org/content/116/16/7723). By Dmitry Krotov and John J. Hopfield. 

And a simple implementation of ["Random synaptic feedback weights support error backpropagation for deep learning"](https://www.nature.com/articles/ncomms13276) by Timothy P. Lillicrap, Daniel Cownden, Douglas B. Tweed & Colin J. Akerman.

We also very brielfy explore adversarial robustness of models implemented with this method.

# Environment
torch 2.1 + cu118
python 3.9

# Explanation

- bioLearning.ipynb: comparison of different CNN, Bio net, and Feedback alignment architecture.
- fa_linear.py: implementation of the feedback alignment function
- bio_learn.py: core codes implement the different architecture, detailed can be found in inline comments
- 0030_adverserial_1.ipynb: other metric comparison 

unlisted files are for test use.


# Reference code
https://github.com/gatapia/unsupervised_bio_classifier
https://github.com/L0SG/feedback-alignment-pytorch
