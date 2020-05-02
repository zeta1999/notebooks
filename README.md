# notebooks
---

These notebooks complement the working paper *Differential Machine Learning* by Brian Huge and Antoine Savine (2020), including code, practical implementation considerations and extensions. 

**DifferentialML.ipynb** is the main demonstration notebook for the concepts and ideas of the working paper. We provide a simple, yet fully functional implementation of twin networks and differential training, and apply them to some textbook examples, including the reproduction of the Bachelier example in the section 3.1 of the article. We also discuss the details of a practical implementation, including the important matters of initialization, optimization and normalization, which are not covered in the paper. This notebook is based on TensorFlow 1.x and built to run on GPU, either locally or on Google Colab. 

<a href="https://colab.research.google.com/github/differential-machine-learning/notebooks/blob/master/DifferentialML.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


**DifferentialRegression.ipynb** applies differential learning in the context of classic regression models. In the article, we applied the new ideas to deep neural networks, hinting that the methodology applies to arbitrary regression models, including classic linear regression and neural architectures of arbitrary complexity, without showing other numerical results than feedforward networks. This notebook applies the differential machine learning to polynomial regression in the context of a basket option in a correlated Bachelier model. We see that, in this context too, differential training offers a  massive performance improvement, without the need for additional regularization, or hyperparameter optimization. 

<a href="https://colab.research.google.com/github/differential-machine-learning/notebooks/blob/master/DifferentialRegression.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
 
We also posted additional material [here](https://differential-machine-learning.github.io/appendices/), including mathematical proofs, various extensions and considerations for an implementation in production.
          
[github.com/differential-machine-learning](https://github.com/differential-machine-learning)
<img src="differential.png">
