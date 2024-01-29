# CNN-on-Handwritten-Numbers

# About Dataset

Set of hand drawn images from MNIST Dataset
Label
- Corresponding to the number present in image (0-9)
- Drawn

Feature
- Each image has 1 grayscale channel with a size of 28 x 28
- Each pixel ranges from 0-1, with 0 representing black and 1 representing white

Shape of dataset
[70000, 28, 28]

- There are 70,000 image records
- Each image has 1 grayscale channel with a size of 28 x 28
- Each pixel ranges from 0-1 


# Visualization of Dataset

![Unknown](https://github.com/Dionisio1013/CNN-on-Handwritten-Numbers/assets/106797659/e58779f5-9623-48f5-99ef-d3f6bfd7c598)

# CNN Structure
![IMG_2566](https://github.com/Dionisio1013/CNN-on-Handwritten-Numbers/assets/106797659/5daf0724-a8a8-409c-ae58-ac0ddbe1bac8)


# Data Preparation

Splitting the Data into Training and Testing Set

<img width="386" alt="Screenshot 2024-01-28 at 5 47 18 PM" src="https://github.com/Dionisio1013/CNN-on-Handwritten-Numbers/assets/106797659/8f99ee83-c954-4e0d-88af-31c707acd570">

Training: 60,000 records
Testing: 10,000 records

Split into batches of 100 records shuffled for both training and testing

Why do we split into batches?

Helps with Stochiatic Gradient Descent
- 



# Training Model


# Testing Results


Epoch Results
