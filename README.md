# Lacuna Masakhane Parts of Speech Classification Challenge - 2nd place

## Description
This repository contains the 2nd place solution for the Lacuna Masakhane Parts of Speech Classification Challenge competition. The challenge focused on classifying part of speech (POS) tags for an out-of-distribution and underrepresented African Languages.

**Competition Link:** [Lacuna Masakhane Parts of Speech Classification Challenge](https://zindi.africa/competitions/lacuna-masakhane-parts-of-speech-classification-challenge/leaderboard)

## Problem Statement
The objective of this challenge is to create a machine learning solution that correctly classifies 14 parts of speech for the unrelated Luo and Setswana languages. We need to build one solution that applies to both languages, not two solutions, one for each language.

The training set of 19 languages is available at this repo: https://github.com/masakhane-io/masakhane-pos

The testing set is made of Luo and Setswana (not included in train)
![Alt text](images/image.png){:width="5%", :height="20%"}

## Solution
![Alt text](images/image-1.png){:width="100px"}

## Repository Files
- `dataset.py`: PyTorch class for the customized dataset.
- `model.py`: Implementation of the XLM-Roberta-Large + Custom Residual-LSTM Head model.
- `infer.py`: Script to prepare the submission file.
- `utils.py`: Scripts for  data preparation, preprocessing...
- `postprocess.py`: Postprocess the model predictions.
- `train.py`: Training Engine.
- `Train.ipynb`: Notebook for interactive training of different stages (train --> pseudolabel --> train).

## How to Use
1. **Clone the Repository:**
```
git clone https://github.com/Iheb-ch/Zindi-Lacuna-Masakhane-POS-Challenge.git
```
2. **Navigate to the Repository:**
```
cd Zindi-Lacuna-Masakhane-POS-Challenge
```
3. **Run the Notebook Train.ipynb:**


## Acknowledgments
- Special thanks to [Zindi](https://zindi.africa/) for hosting the competition.

Feel free to explore the code and contribute to the development of the POS tagging models for low-resourced  African languages.
