# Project 2 — CNN Image Classification & Transfer Learning

This project investigates **convolutional neural networks for image classification** using a subset of the CIFAR-100 dataset.

The original course handout is not included. The public notebook keeps the student's code, experiments, results and observations while replacing assignment-instruction wording with original summaries.

## Architectures

Four models are implemented and compared: LeNet, AlexNet, VGG, and a custom CNN called MyCNN. The models are trained under a common experimental protocol and evaluated primarily with **F1-score**.

## Experiments

The notebook studies training and validation behaviour, optimizer choice, batch size, model complexity, generalization, and test-set F1-score.

## Overfitting mitigation

The custom CNN is evaluated with dropout, data augmentation, and their combination. The combined approach produced the strongest reported test F1-score in the notebook.

## Transfer learning

Transfer-learning experiments use pretrained VGG19 and EfficientNetB0 models. Two strategies are explored: training a new classification head on a frozen convolutional backbone, and fine-tuning a selected subset of deeper layers.

The notebook concludes with a discussion of **TFRecord** and scalable TensorFlow input pipelines.

## Notebook

**image_video_analysis_2nd_lab.ipynb**
