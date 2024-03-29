# ucl-machine-learning-projects

Courseworks including jupyter notebooks and PDF reports from courses of my master's at UCL.
The files included are:

- deep_representation_learning/

  - concept-bottleneck-age-brain-mri.ipynb : adopting a [concept-bottleneck modelling](https://github.com/yewsiang/ConceptBottleneck) technique for interpretable prediction of age from brain MRI scans
    - some interesting things I tried was using Bayesian optimization for hyperparameter search.
  - cb-age-prediction-brain-report.pdf: associated report to the above notebook
  - review-antibiotic-discovery review_antibiotic.pdf : a review of the paper on [A deep learning approach for antibiotic discovery](https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1).
    - you can read it as a short tutorial on how graph neural networks work
  -   temperature-prediction-RNN.ipynb : using a simple RNN for predicting temperature from the classical Dehli climate dataset
    - function for auxiliary loss used
  - convolutional-VAE.ipynb : using convolutional VAE architecture from [this source](https://github.com/rasbt/stat453-deep-learning-ss21/blob/main/L17/1_VAE_mnist_sigmoid_mse.ipynb) with the loss function from [this source](https://github.com/vsimkus/pmr2023-vae) for MNIST digit reconstruction
    - the only thing worth noting is to not use the Bernoulli distribution before binarizing MNIST digits.  
- hospital_readmission/
  - hospital_readmission.ipynb
    - code performing data analysis for predicting hospital readmission given patients' physiological features
  - hospital-readmission-report.pdf and appendix-figs.pdf
      - report with associated figures documenting what I performed
  - for further information on this task, please check [Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3996476/)
- biomedical_imaging/
  - diffussion_mri and Figures-dmri.pdf
    - report with associated figures on fitting linear models to brain diffussion MRI data yielding insight into the brain's structure
    - for more information on methods, please watch https://www.youtube.com/watch?v=VyZfhkyKFNQ