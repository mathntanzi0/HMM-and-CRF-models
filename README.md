# Sequence Labeling Models: CRF and HMM

This repository contains a Jupyter Notebook for training and evaluating two sequence labeling models: Conditional Random Field (CRF) and Hidden Markov Model (HMM). The notebook demonstrates data preprocessing, feature extraction, model training, and evaluation for both models.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Data Preparation](#data-preparation)
- [Feature Extraction](#feature-extraction)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Introduction

Sequence labeling tasks, such as Named Entity Recognition (NER) and Part-of-Speech (POS) tagging, are essential in Natural Language Processing (NLP). This notebook provides a step-by-step guide to train CRF and HMM models for such tasks.

## Requirements

To run the notebook, you need the following libraries:

- `pandas`
- `numpy`
- `nltk`
- `sklearn`
- `sklearn-crfsuite`
- `hmmlearn`

You can install the required libraries using:

```bash
pip install pandas numpy nltk scikit-learn sklearn-crfsuite hmmlearn
