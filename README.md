# Applying Transfer Learning on Dogs vs Cats Dataset

## Transfer Learning 
In practice, very few people train an entire Convolutional Network from scratch (with random initialization), because it is relatively rare to have a dataset of sufficient size. Instead, it is common to pretrain a ConvNet on a very large dataset (e.g. ImageNet, which contains 1.2 million images with 1000 categories), and then use the ConvNet either as an initialization or a fixed feature extractor for the task of interest.

## Project Overview
In this project i have constructed a model that will classify a dog and cat.For this i haved used this dataset https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip which consist of 2000 images for training set and 1000 images for test set.

## Dependencies
- tqdm
- tensorflow
- keras
- google Colab
- matplotlib
- numpy

## Usage
Finish the training process and save the model in "h5" format and test the model....

## Result
> print("Accuracy after transfer learning: {}".format(valid_accuracy))
> Accuracy after transfer learning: 0.9409999847412109
