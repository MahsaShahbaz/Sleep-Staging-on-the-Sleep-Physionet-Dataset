# Sleep Staging on the Sleep Physionet Dataset

This repository contains a project that demonstrates how to train a convolutional neural network (CNN) on raw EEG data to classify sleep stages. It is based on well-established examples from [MNE-Python](https://mne.tools/stable/auto_tutorials/sample-datasets/plot_sleep.html) and [Braindecode](https://braindecode.org/auto_examples/plot_sleep_staging.html), with additional implementation details inspired by:

> Chambon, S., Galtier, M. N., Arnal, P. J., Wainrib, G., & Gramfort, A. (2018). A deep learning architecture for temporal sleep stage classification using multivariate and multimodal time series. IEEE Transactions on Neural Systems and Rehabilitation Engineering, 26(4), 758-769.

## Project Overview

Sleep staging involves identifying sleep stages by analyzing EEG signals. This project applies deep learning techniques to automate and enhance the accuracy of sleep staging using raw EEG data from the Sleep Physionet dataset.

## Features
- Preprocessing raw EEG signals with MNE-Python.
- Training a CNN for sleep stage classification.
- Leveraging the `mne-torch` library for efficient model implementation.

## Dataset
This project utilizes the [Sleep Physionet Dataset](https://physionet.org/content/sleep-edfx/1.0.0/), which provides EEG recordings for sleep staging research.
