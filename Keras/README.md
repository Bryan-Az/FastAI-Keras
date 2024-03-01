# Utilizing Keras' NLP and Vision Tools

## Keras NLP (Natural Language Processing)
In this directory I build and test Keras NLP for various NLP tasks useful for connecting data to a LLM (Large Language Model). 

I pre-train a single classifier & run an ablation experiment where I finetune this classifier using a variety of finetuning methods (i.e a pretrained 'backbone', then user-controlled preprocessing, and finally custom modules).

## Keras CV (Computer Vision)

Keras also has useful CV tools that can help build a state-of-the-art YOLO (You Only Look Once) object detection model. The YOLO architecture helps speed up object detection for example, when using in a video setting where many frames are being analyzed per second.

I build two classifiers (a pretrained classifier, train my own custom classifier) and then test the pre-trained classifier by fine-tuning it for further use-cases.

### Pre-Trained Vision Model using Keras
In this section, I will finetune a pre-trained vision model (that was NOT trained to classify images of clothing) using the Fashion-MNIST dataset of images.

An example of how the MNIST data will be loaded is:
```
# To load the dataset, use this python code
# the datasets library can be installed
# using the environment.yml file in the Fast-AI directory
fashion_mnist = datasets.load_dataset(fashion_mnist)
```

### Custom Vision Model using Keras
I will train my own custom Keras model to classify fashion / articles of clothing from the Fashion-MNIST set. 

 