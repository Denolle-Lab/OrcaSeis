# ORCASEIS


This project aims to develop an ML orca unsupervised and supervised classifier ysing hydrophone and DAS data.

We start from this project: https://github.com/orcasound/orcadata/wiki


Project team:
- Marine Denolle (mdenolle at uw.edu)
- Anjani Mirchandani 


## Data

First, we will pull data from there a training data set: https://github.com/orcasound/orcadata/wiki/Orca-training-data

## Order for running CNN
1. data_cleaning.ipynb
2. cnn_pytorch.ipynb / cnn_tensorflow.ipynb

## Order for running SVM
1. data_cleaning.ipynb
2. creating_spectrograms.ipynb
3. test_svc_classifier.ipynb

## Install dependencies
```bash
    pip install -r requirements.txt
```