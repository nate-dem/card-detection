# Card Detection & Classification

This repository contains our final project for **CS 131 at Stanford**, where we trained a **CNN model** to classify playing cards (suit and rank) using PyTorch.

Before the model can classify each card, we:
  1. Convert the image to grayscale and apply gaussian blur
  2. Apply our Canny edge detector to find edges
  3. Identify contours in the result image to locate each card
  4. Isolate and extract each card in the original image

After this process, we use the model to classify each playing card in the original image. 
Our latest model achieved a rank accuracy of 92.3% and a suit accuracy of 90.2%.

Dataset used for training: https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification

Presentation slides: https://docs.google.com/presentation/d/1TWhKtZeNwcCDfU2GtJPWih7OLRoRUx7tXcZwGZ1axiE/edit#slide=id.p
