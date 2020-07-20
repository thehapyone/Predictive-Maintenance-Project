# Thesis Project - Representation Learning and Predicitive Maintenance of Vehicles

## Abstract (from Paper)
Automobile Predictive Maintenance (PdM) necessitates the storage and analysis of large amounts ofsensor data, a requirement can be challenging in deploying PdM algorithms onboard the vehiclesdue to limited storage and computational power on the hardware of the vehicle. 
Hence, this project seek to obtain low dimensional descriptive features from high dimensional data using Representation Learning. The low dimensional representation can now be used for predicting vehicle faults, specifically Turbocharger related failures in this project.
A Parallel Stacked Autoencoder based architecture is presented with the aim of producing better representations when compared to individual serial Autoencoders. Also, Embeddings are employed on Categorical Variables to improve the performance of the Artificial Neural Networks (ANN) models by introducing continuity into the data. 
This architecture is shown to achieve excellent performance, and in close standards to the previous state-of-the-art research. Significant improvement in Turbocharger failure prediction is obtained along with reduction insize of input data using our novel deep learning ANN architecture

## Repository Structure
This repository contains the codes, models, files and every related content during the course of the project development. For privacy and NDA reasons, the original data used for this project has been removed. A sample data has been provided though after our data engineering proposes.

The repository is structured in a self explanatory folder structure, with each folder name explaining what its contents does as much as possible. 

* The Codes Directory: This folder contains all related codes mostly in jupyter notebooks used during the course of this project have been sub-divided into self explanatory groups: The **Extras** folder contains some helpful codes used for data processing, **Trained Models** contains all the saved models if you decide to run your own test or experiements, **Data Engineering** houses all the codes used for missing value analysis, data preperation, understanding the nature of the data, sorting and several others. The remaining folders are self explanatory. 
* Generated Data Directory: Holds some of the data that were generated during the cours eof the work. Some examples are the csv holding the mappings from categorical values to label encoding values, also another one is the csv holding the embeddings dimension used for each categorical feature. A sample testing data has been included to give an idea of what sort of data we worked with.
* Others Directory: Here, we included some information about the results achieved, images of different sections, and other unaccounted file.
* Unorganized Directory: More of a dump yard of stuffs.

## Software Overview
During the course of this work, a number of platforms, libraries, and software system was used. The below higlights those information. 
### Language
Python was the primary development language, athough we played around R for an experiement. 

### Libraries
* Matplotlib
* Numpy
* Scipy
* Tensorflow 2
* Keras (Built on top of Tensorflow 2.0)
* Seaborn
* Scikit-learn

### Platform
* Pycharm
* Notepad ++
* Google Colab
* Python 3

### Highlevel Architecture

## Project Results

### Embeddings Results

### Comparison with other Dimensionality Reduction Methods

### Compression Evaluation 

## Issues & Help

We understand it might be tricky to navigate or even understand how some of the codes work. If you need help please raise an issue or send a private mail to us. 