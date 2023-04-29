# crypto-clustering-challenge
Module 19 Challenge: Unsupervised Learning


## Introduction

In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.


## Assignment components
_Note: The plots do not show in the notebook on github, so I embedded them in this section_
* Normalizing the data (get all variables to the same z-score scale with a mean of 0 and std of 1)
* Assessing the number of appropriate clusters using the elbow method

<img src=Images/elbow1.png>

* initiating the cluster model, fitting the data, and making cluster predictions, then visualize the results focusing on two features

<img src=Images/scatter1.png>

* Reducing the dimentionality of the data by applying the PCA model (requesting 3 components)
* Assessing the number of appropriate clusters, on the reduced features, using the elbow method

<img src=Images/elbow2.png>

* Initiating the cluster model on the reduced features (the 3 components), fitting the data, and making cluster predictions, then visualize the results focusing on two principal components

<img src=Images/scatter1.png>

* Creating composite plots 
    1) for the elbow method for the original and after employing pca 
    <img src=Images/elbow_composite.png>
    2) for assessing the predicted cluster
    <img src=Images/scatter_composite.png>
* Compare results and assess solutions difference


