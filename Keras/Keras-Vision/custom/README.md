# Finetuning of a custom vision model

# Pre-Trained Vision Model using Keras
In this section, I will finetune a pre-trained vision model (that was NOT trained to classify images of clothing) using the Fashion-MNIST dataset of images.

An example of how the MNIST data will be loaded is:
```
# To load the dataset, use this python code
# the datasets library can be installed
# using the environment.yml file in the Fast-AI directory
fashion_mnist = datasets.load_dataset(fashion_mnist)
```

# Custom Vision Model using Keras
I will also be extending the work done in FastAI/Vision-Models by finetuning the object detection model that was trained to classify fashion / articles of clothing from the Fashion-MNIST set with a new set of non-greyscale images from the VITON-Clean dataset (a dataset of colour fashion images) that could potentially improve the generalizability of this model.

[Virtual Try-On Network (VITON) Dataset](https://github.com/sergeywong/cp-vton)


