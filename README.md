# Awesome-Functional-ML (WIP!)
This repo contains a collection of papers on ML for functional data. 

Functional data, data where an observation is considered as a function, arises in many different fields. Important examples include but are not limited to economics, medicine and chemometrics. For example in a medical study the concentration of a certain protein in the blood of patient n at time t could be considered as a functional observation. With developments in modern technology (among others wearable devices), more and more data are collected continuously over a time interval or discretely at many time points in an interval. This is for example the case in the stock market where price changes occur in fractions of seconds. Another example is the electricity demand measured over time. Longitudinal data is a common type of functional data but not the only one. For example probability distributions over multiple measurements for each subject or images could be considered as functional data. The presence of functional data in many real-world problems requires the study of methods suitable for such data and as a consequence the field of functional data analysis has grown dramatically in the past decades.

Treating data as functions instead of multivariate vectors can be advantageous as it for example allows the evaluation at every time point as well as the use of derivatives. However, another reason is that classical methods can break down when applied to functional data and care must be taken in the development of new methods.

The abundance of functional data and the growing size of data sets require scalable methods for functional data which are able to capture complicated highly non-linear relationships in the data. This is where Machine Learnign and Deep Learning comes in.

P.s.: If you have suggestions for papers to be added to this collection feel free to get in touch or make a PR:)

## Contents
- Resources for FDA
- Papers
  - Theory
  - Unsupervised
    - Generative Models
  - Supervised
    - Regression
    - Classification
   

## Resources for FDA
* [Review of Functional Data Analysis, Wang et al.](https://anson.ucdavis.edu/~mueller/Review151106.pdf)
* [Some Tools for Functional Data Analysis, Ramsay and Dalzell](https://www.jstor.org/stable/2345586)
* [Functional Data Analysis, Ramsay and Silverman](https://link.springer.com/book/10.1007/b98888)
* [Applied Functional Data Analysis: Methods and Case Studies, Ramsay and Silverman](https://www.ece.uvic.ca/~bctill/papers/mocap/Ramsay_Silverman_2002aa.pdf)
* Chapter 2 of [Variational Autoencoders on Hilbert Spaces](https://lorenz-wolf.netlify.app/uploads/FDA_Thesis.pdf)

## Papers

### Theory

### Unsupervised

#### Representation Learning
* [Functional Autoencoders for Functional Data Representation Learning](http://faculty.ist.psu.edu/vhonavar/Papers/FAESDM.pdf)

#### Generative Modelling
##### Evaluation
* [A Kernel Two-Sample Test for Functional Data](https://www.jmlr.org/papers/volume23/20-1180/20-1180.pdf)
  
##### Energy Based Models
* [Energy-Based Models for Functional Data using Path Measure Tilting](https://arxiv.org/abs/2202.01929)

##### Diffusion Generative Models
* [Spectral Diffusion Processes](https://arxiv.org/pdf/2209.14125)
* [Diffusion Probabilistic Fields](https://openreview.net/pdf?id=ik91mY-2GN)
* [Mainfold Diffusion Fields](https://arxiv.org/pdf/2305.15586.pdf)
* [$\infty$-Diff: Infinite Resolution Diffusion with Subsampled Mollified States](http://arxiv.org/abs/2303.18242)
* [Diffusion Generative Models in Infinite Dimensions](http://arxiv.org/abs/2212.00886)
* [Score-based Diffusion Models in Function Space](http://arxiv.org/abs/2302.07400)

### Supervised
* [Modern Non-Linear Function-on-Function Regression](https://arxiv.org/abs/2107.14151)
