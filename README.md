# An End-to-End DNN for ASR with CTC
[![GPL-3.0 Licensed](https://img.shields.io/badge/License-GPL3.0-blue.svg?style=flat)](https://opensource.org/licenses/GPL-3.0) [![TensorFlow Version](https://img.shields.io/badge/Tensorflow-1.4+-blue.svg)](https://www.tensorflow.org/) [![Keras Version](https://img.shields.io/badge/Keras-2.0+-blue.svg)](https://keras.io/) [![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/) 

## Introduction
In this notebook, we will build a deep neural network (CNN + GRU + CTC) that functions as part of an end-to-end automatic speech recognition (ASR) pipeline on Keras framework.

## Data Sets 
[LibriSpeech ASR corpus](http://www.openslr.org/12)

## Modeling step
- We begin by investigating the LibriSpeech dataset that will be used to train and evaluate the models. 
- Algorithm will first convert the raw audio data to feature representations (Spectrograms and MFCCs) that are commonly used for ASR. 
- Build and compare the performance of various neural networks that map the audio features to transcribed text. 

* **To run **
Simply run `asr_notebook.ipynb` and results will be automatically saved in the `results` folder.

## Python libraries that need importing

* python_speech_features
* TensorFlow
* Keras
* Numpy
* time
* glob
* seaborn
* json
* matplotlib
* librosa
* Scipy
* random
* os
* soundfile
* signal
* contextlib
* requests
* \_pickle


