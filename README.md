# Food-Classification

Build a model to classify different types of famous and delicious food by looking at the images of the dishes.

## Demo
<div align="center">
  <img src="https://raw.githubusercontent.com/elfphabet621/Food-Classification/main/food_demo.gif"/>
</div>

## Goal

From the [The Food-101 Data Set (https://pytorch.org/vision/main/generated/torchvision.datasets.Food101.html). I focus only on 4 classes (lagsana, pho, ramen, pad thai), because I want to quickly apply what I have learned to create a deep learning model.

## Project's Flow

1. Create a small dataset (about 150 images for each class) from the original Dataset
2. Take a quick look at the data, then visualize them for better understanding
3. Load Images in two ways: use ImageFolder provided by Pytorch, build a custom ImageFolder
4. Build two 2 models based on VGG model: one with no data augmentation, the other does use augmentation
5. Training and Ploting
6. Deploy the model using Streamlit

## Conclusion
After a few epochs (10), both models did prety well. I would say that the augmented model performed better and more stable. 
