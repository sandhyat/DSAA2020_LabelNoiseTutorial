# DSAA2020_LabelNoiseTutorial

This repository contains the slides and link to the recording of the tutorial that was presented at DSAA conference 2020. The tutorial proposal is also included in the repository.

Tutorial Link  [https://www.youtube.com/watch?v=ejGnQPGz0qk]

The outline of the tutorial is as follows:

1) Started with the problem setting of standard 0-1 binary classification and outline some historical background.
2) Three strands of literature presented:
   1) Identification of label noise robust loss functions and corresponding sufficient conditions. We also discuss about various modifications proposed to surrogate loss functions like unbiasedness, importance re-weighting, etc. These methods are theoretically sound and demonstrate good empirical performance. However, they either assume true noise rates or estimate them, which might not be accurate. The noise considered in this setup is either symmetric across all classes or it is only dependent on class. Also, the setting is empirical risk minimization (ERM) framework.
  2) In this part, we generalize the noise setting to instance dependent noise and ERM setup to deep networks. In instance dependent noise case, a major result available is the noise robustness of Isotron algorithm. Another approach taken is via consistency, where k-NN and SVM are shown to be noise robust. With respect to deep networks, various perspectives have been proposed in addition to the existing way of showing inherent robustness of loss function and modification of loss functions. One approach here is to understand the basic working of neural networks in terms of dimensionality and modify the algorithm. Another approach assumes that there is a small amount of clean data available which can be used along with noisy data for training a deep network.
  3) In the last part, we discussed the effect of label noise on cases beyond standard classifications like cost sensitive binary classification, generative models, learning from positive and unlabelled data and active learning. For each of these cases, we will briefly explain the problems and the efforts made to solve them in terms of loss functions or the learning approach.
3) Finally, we concluded by discussing some issues while designing and evaluating the label noise robust algorithms.
