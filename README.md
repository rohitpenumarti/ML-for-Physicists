# ML-for-Physicists

1. [Chi-square Fitting of Noisy Data and Likelihood Modeling of Supernova Neutrino Data](#chi-square-fitting-of-noisy-data-and-likelihood-modeling-of-supernova-neutrino-data-link)
2. [Non-linear Least Squares Fitting of Temperature Data](#non-linear-least-squares-fitting-of-temperature-data-link)
3. [Outlier Treatment and Bootstrapping, MCMC, and PCA](#outlier-treatment-and-bootstrapping-mcmc-and-pca-link)
4. [Gaussian Process Regression, Mixture Modeling and Bootstrapping, and Model Selection](#gaussian-process-regression-mixture-modeling-and-bootstrapping-and-model-selection-link)

### Chi-square Fitting of Noisy Data and Likelihood Modeling of Supernova Neutrino Data ([link](https://github.com/rohitpenumarti/ML-for-Physicists/blob/master/Homework%20%231.ipynb))
For the first homework assignment, we were tasked with completing two problems. The goal of this problem set was to become familiarized with chi-squared fitting of data and creating and visualizing likelihood models of data. 

The first problem was concerned with chi-square fitting of noisy data. The first part asked me to simulate and graph random uniformly sampled points between -1 and 1 with gaussian noise added to is. Then, I was asked to fit the data using a chi-square fitting test, ignoring errors in x data. The next part, involved fitting the data with the correct errors whereas the next part involved fitting with incorrect errors. Lastly, I was tasked with simulating the data again, but with a slight twist and asked to model this data with different errors.

The second problem was concerned with likelihood estimation of data and its visualization. I was tasked with formulating the log-likelihood function of a set of arbitrary data on supernovae. The next part involved differentiating to find analytic expressions for the maximum likelihood values of parameters. Finally I had to create contour plots of the likelihood function and then marginalize to obtain a one-dimensional probability distribution for one parameter.

### Non-linear Least Squares Fitting of Temperature Data ([link](https://github.com/rohitpenumarti/ML-for-Physicists/blob/master/Homework%20%232.ipynb))
This project focused on non-linear least square fitting of cosmic dawn temperature data. This was done with real world data obtained by researchers publishing an article on searching for signals of the cosmic dawn. This signal was characterized by a drop in brightness of the radio sky at around 80 MHz. The first part was concerned with using non-linear least squares to estimate model parameters.

The second part involved estimating the same thing but with a slightly altered model for the temperature with and without uncorrelated errors accounted for. The final part involved addressing a problem with the analysis prior. The use of uncorrelated errors a non-physically motivated model resulted in less accurate parameter estimation. So, accounting for correlated errors and a better model resulted in better results using the same non-linear least squares method of parameter optimization. 

### Outlier Treatment and Bootstrapping, MCMC, and PCA ([link](https://github.com/rohitpenumarti/ML-for-Physicists/blob/master/Homework%20%233.ipynb))
This project was focused on Gaussian Mixture Models (GMM) in cluster analysis and bootstrapping to estimate errors, and an introduction to MCMC and PCA. 

In the first part GMM was used to appropriately identify outliers in galaxy data estimate parameters of the galaxy such as proper motions parallax of stars. Bootstrap resampling was used to estimate errors in estimated parameters. Then posterior probability was used to determine membership probability of stars in the cluster.

The second part was an introduction to MCMC. It involved the same dataset used in the previous assignment and we were tasked with again estimating parameters of the model using the Metropolis-Hastings algorithm.

The last part of the assignment involved an introduction to PCA. It involved dimensionality reduction on a sequence of images of stars. Then it was used to analyze principal components of the data.

### Gaussian Process Regression, Mixture Modeling and Bootstrapping, and Model Selection ([link](https://github.com/rohitpenumarti/ML-for-Physicists/blob/master/HW4%20(Final%20Project).ipynb))
This assignment involved gaussian process regression (GPR), mixture models and bootstrapping again, and model evaluation techniques.

The first part of the assignment involved GPR to fix image data with bad pixels. Median replacement was analyzed with respect to GPR to see better methods for dealing with bad pixels. Then to make the GPR model better, I used hyperparameter tuning. To test efficiency of the model, I used a smaller subset of the data to see how much smaller of a dataset can be used before sacrifice of accuracy.

The second part of the assignment involved GMM and bootstrap resampling for cluster data, similar to the first part of the previous assignment. Similar methods were used to solve the problems brought up here.

The last part of the project introduced metrics for analyzing the effectiveness of the models. I had to analyze a study and used two different metrics to see the effectiveness of the models chosen by them.
