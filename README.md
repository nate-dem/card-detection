# Card Detection & Classification

This repository contains our final project for **CS 131 at Stanford**, where we trained a **CNN model** to classify playing cards (suit and rank) using PyTorch.

Before the model can classify each card, we:
  1. Convert the image to grayscale
  2. Apply our Canny edge detector to find edges
  3. Identify contours in the result image to locate each card
  4. Isolate and extract each card in the original image

After this process, we use the model to classify each playing card in the original image. 

Dataset used for training: https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification
