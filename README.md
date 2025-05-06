# Prototypical Networks for One-Shot, Few-Shot, and Self-Supervised Learning on ChestMNIST

This repository contains the code and experiments for a comparative study on **One-Shot**, **Few-Shot**, and **Self-Supervised Learning (RotNet)** methods using **Prototypical Networks** for **multi-label classification** on the ChestMNIST dataset.

## Objective

Evaluate the performance of Prototypical Networks in low-data settings and examine whether self-supervised pretraining enhances few-shot learning in medical imaging.

## Models 

- **Prototypical Network One-Shot Learning** (k=1)
- **Prototypical Network Few-Shot Learning** (k=5)
- **RotNet pretraining + Self-Supervised Learning** (k=5)

## Evaluation Metrics

All models are evaluated using:

- F1-Score
- AUROC
- Precision
- Recall

## Dataset

- [MedMNIST - ChestMNIST](https://medmnist.com/)
- Multi-label classification of 14 thoracic disease labels using chest X-ray images.
