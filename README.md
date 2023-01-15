# Energy-based-confidence (To be continue)
When segmentation models were trained on missing labels, we introduced energy scores to measure the confidence of predictions.

> We will complete the introduction of our code in this month (2023.01).

## Data

### Download path: https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest/download/

### generate Missing labels: generate_missing_label.ipynb

## Encoder and Decoder

### Encoder: model/backbones/mit.py

### Decoder: model/decode_heads/mla_head.py

## Loss function

model/loss.py: contains all the loss functions we proposed in our paper

## train

train.py
