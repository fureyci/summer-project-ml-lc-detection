# Investigating machine learning methods for light curve classification of unusual transients
## Supernova and Transient Research Group at Trinity College Dublin
### Ciaran Furey, 14/06/2021 - 06/08/2021

In this repository, you will find jupyter notebooks demonstrating what I got up to over the course of my summer project. 

Working with the Supernova and Transient Research Group at Trinity College Dublin, the goal of this project was to investigate different machine learning methods in order to improve the classification of less common type II and type Ib/c supernovae from their light curve.

Traditionally, transients are classified based off their spectra - the presence or absence of different elements indicate which type of supernova is being observed. However, spectroscopic classification is a time consuming process, and as new surveys come online, such as the LSST, data will be obtained at an unprecedented rate. Therefore, we must turn to classifying transients from their light curves - a quicker and less computationally expensive process. To keep up with the rate at which data is being obatined, machine learning methods must be used to perform this light curve classification.

In this project, data was obtained from the open source [Open Astronomy Catalog API](https://github.com/astrocatalogs/OACAPI), and the machine learning models were provided by [Sci-kit Learn](https://github.com/scikit-learn/scikit-learn). 

Firstly, a class was created, `OpenSN`, that loads light curves and tidies the data. Then, different machine learning methods were examined. Finally, the different machine learning methods were compared in order to examine which ones perform well and which ones do not. 
