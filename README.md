# PlantPathology

## Problem Statement

Apples are one of the most important temperate fruit crops in the world. Foliar (leaf) diseases pose a major threat to the overall productivity and quality of apple orchards. The current process for disease diagnosis in apple orchards is based on manual scouting by humans, which is time-consuming and expensive.

Although computer vision-based models have shown promise for plant disease identification, there are some limitations that need to be addressed. Large variations in visual symptoms of a single disease across different apple cultivars, or new varieties that originated under cultivation, are major challenges for computer vision-based disease identification. These variations arise from differences in natural and image capturing environments, for example, leaf color and leaf morphology, the age of infected tissues, non-uniform image background, and different light illumination during imaging etc.

Plant Pathology 2020-FGVC7 challenge competition had a pilot dataset of 3,651 RGB images of foliar disease of apples. For Plant Pathology 2021-FGVC8, we have significantly increased the number of foliar disease images and added additional disease categories. This year’s dataset contains approximately 23,000 high-quality RGB images of apple foliar diseases, including a large expert-annotated disease dataset. This dataset reflects real field scenarios by representing non-homogeneous backgrounds of leaf images taken at different maturity stages and at different times of day under different focal camera settings.

## Objective

The main objective is to develop machine learning-based model to accurately classify a given leaf image from the test dataset to a particular disease category, and to identify an individual disease from multiple disease symptoms on a single leaf image.

## Methodology

In this project, I have used Convolutional Neural Networks to solve this multi-class classification problem. CNNs have defied expectations and risen to the throne as the most advanced computer vision technique. CNNs are by far the most common of the various forms of neural networks (others include recurrent neural networks (RNN), long short term memory (LSTM), artificial neural networks (ANN), and so on). The image data space is crowded with convolutional neural network models. They excel at image classification, object identification, and image recognition, among other computer vision activities.

## Dataset

train.csv - the training set metadata.
* image - the image ID.
* labels - the target classes, a space delimited list of all diseases found in the image. Unhealthy leaves with too many diseases to classify visually will have the complex class, and may also have a subset of the diseases identified.

train_images - The training set images.

test_images - The test set images.

## Contributors

* Devyani Barde
