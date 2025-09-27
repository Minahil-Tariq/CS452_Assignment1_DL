# A1-CS452 - <FastID> <YourName>

This repository contains the code and report for Assignment 1 (Deep Learning).
It implements a multi-task CNN to perform facial expression classification (8 classes)
and valence/arousal regression.

## Contents
- notebook/assignment1.ipynb — main notebook (data loading, training, evaluation)
- code/ — optional modular python files
- results/ — CSV of metrics and saved models
- figures/ — training curves
- report/22i2012_MinahilTariq_A1-CS452.pdf — final report

## How to run
1. Use Google Colab (recommended with GPU).  
2. Upload `DL_Assignment1_Dataset.zip` when prompted in notebook.  
3. Run all cells.  
4. For faster runs set IMG_SIZE to (128,128) and epochs to 3. For final runs use (224,224) and epochs 20–30.

## Dependencies
- Python 3.8+
- tensorflow >= 2.10
- numpy, scikit-learn, opencv-python, matplotlib
