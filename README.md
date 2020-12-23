# The mushroom image detector

This app is just a proof of concept (POC)!
The image classification model can be further optimized. The goal of the project was to develop a POC-model and deploy it on [MyBinder](https://mybinder.org/)

## Introduction
- There are 9 folders of images of most common Northern European mushrooms genuses inside of the dataset. Each folder consist of 300 to 1500 selected images of mushrooms genuses. 
- The link to the dataset is [here](https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images)

## Overview
- 01_mushroom_detector.ipynb: create model in Google Colab and try which app layout (GUI) works fine
- 02_mushroom_frontend.ipynb: Load model from Google Colab and start GUI
- 02_mushroom_frontend_binder_1.ipynb: Jupyter notebook to start GUI (NOT RELEVANT)
- 02_mushroom_frontend_binder_2.ipynb: Jupiter notebook to start GUI

### Detectable Mushrooms
The image classifier can classify the following mushrooms:
- Agaricus = Champignons
- Amanita = Wulstlinge
- Boletus = Steinpilze
- Cortinarius = Schleierlinge
- Entoloma = Rötlinge
- Hygrocybe = Saftlinge
- Lactarius = Milchlinge
- Russula = Täublinge
- Suillus = Schmierröhrlinge

## App runs on MyBinder
- [Link to App](https://hub.gke2.mybinder.org/user/raminparker-mushroom_detector-5erim21f/notebooks/02_mushroom_frontend_binder_2.ipynb)






