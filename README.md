# FastAI-Keras
Using libraries & building custom and pre-trained models using FastAI, HuggingFace transformers, and Keras for a variety of deep learning tasks.

# Tabular

Using FastAI & HuggingFace transformers. The data for this section was taken from the secondary Kaggle dataset source 'Corporate Environmental Impact' by Arman and Rebecca Verghese.

[Kaggle Link](https://www.kaggle.com/datasets/mannmann2/corporate-environmental-impact/data)

The primary sources for this dataset are found at:
1. [Harvard Buisness School, *Impact Weighted Accounts Project*](https://www.hbs.edu/impact-weighted-accounts/Pages/default.aspx)
2. “Freiberg, David and Park, DG and Serafeim, George and Zochowski, Rob. 2020. Corporate Environmental Impact: Measurement, Data and Information. Harvard Business School, Impact-Weighted Accounts Project report.”

# Text

Using FastAI, HuggingFace, and Keras-NLP.

## Fast AI

### Product Recommendation

In the *FastAI/Text-Model* directory, I build and test an Amazon fashion products recommendation text model using Fast AI. The primary source for this data in this section was taken from Prof. Julian McAuley's database in the department of computer science at UC San Diego. The data is also used in McAuley et.al.'s research paper.

1. [UC San Diego Link](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/)

2. [Justifying recommendations using distantly-labeled reviews and fined-grained aspects](https://cseweb.ucsd.edu/~jmcauley/pdfs/emnlp19a.pdf)
Jianmo Ni, Jiacheng Li, Julian McAuley
Empirical Methods in Natural Language Processing (EMNLP), 2019

## Keras 

### NLP (Natural Language Processing)
In the */Keras/Keras-NLP* directory I test & finetune a pre-trained Language Model using Keras NLP, useful for connecting and inferring insights from text data using a language model. 

Similar to the product recommendation model used in the Fast AI section, the pre-trained NLP model built with Keras will be tested & finetuned on the [Amazon fashion products dataset](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/).

# Vision

Using FastAI, HuggingFace, and Keras-Vision. The open-source Fashion MNIST dataset of greyscale images are used to train (a custom model) and finetune (a pre-trained model).

Source: 
[Fashion MNIST "Modified National Institute of Standards and Technology"](https://github.com/zalandoresearch/fashion-mnist)

## Fast AI
In the */Fast-AI/Vision-Models* directory I build a custom object detection vision model as well as segmentation vision model.

## Keras
In the */Keras/Keras-Vision* directory I build a custom
 YOLO (You Only Look Once) object detection model, and finetune a pre-trained Keras model.

# Audio

Using HuggingFace transformers.
