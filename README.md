# IASA Champ '24: UI Element Sketch Classification

### [Link to kaggle competition](https://www.kaggle.com/competitions/iasa-champ-24-ui-element-sketch-classification)
* My first data science project and hackathon experience
* Timeline `27.01.2024`-`02.02.2024`

## Overview
The UI Element Sketch Classification Challenge involves classifying hand-drawn and AI-generated sketches of UI elements. 
The dataset comprises images from 21 distinct categories, such as alerts, buttons, and checkboxes. 
The task is to train a classification model capable of accurately identifying the class of a UI element in each image. 

## Dataset Description
* Train folder: Over 15,000 images are divided into folders corresponding to each of the 21 categories.
* Test folder: Includes images from all categories, without class indication.

## Result
Building Sketch Classificator, based on [Convolutional Neural Network (CNN)](https://en.wikipedia.org/wiki/Convolutional_neural_network) model

| ***Dataset***  | ***Accuracy*** |
|:---------------|---------------:|
| Train set      |        `0.848` |
| Validation set |        `0.766` |
| Test set       |        `0.761` |
