# deep-representation-learning-courseworks
Courseworks including jupyter notebooks and PDF reports on topics surrounding deep representation learning for my master's at UCL.
The files included are:
- concept-bottleneck-age-brain-mri.ipynb : adopting a [concept-bottleneck modelling](https://github.com/yewsiang/ConceptBottleneck) technique for interpretable prediction of age from brain MRI scans
  - some interesting things I tried was using Bayesian optimization for hyperparameter search.
- cb-age-prediction-brain-report.pdf: associated report to the above notebook
- review-antibiotic-discovery review_antibiotic.pdf : a review of the paper on [A deep learning approach for antibiotic discovery](https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1).
  - you can read it as a short tutorial on how graph neural networks work
-   temperature-prediction-RNN.ipynb : using a simple RNN for predicting temperature from the classical Dehli climate dataset
  - function for auxiliary loss used
- convolutional-VAE.ipynb : using convolutional VAE architecture from [this source](https://github.com/rasbt/stat453-deep-learning-ss21/blob/main/L17/1_VAE_mnist_sigmoid_mse.ipynb) with the loss function from [this source](https://github.com/vsimkus/pmr2023-vae) for MNIST digit reconstruction
   - the only thing worth noting is to not use the Bernoulli distribution before binarizing MNIST digits.  
