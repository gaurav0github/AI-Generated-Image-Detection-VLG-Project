# AI Generated Image Detection
>## Open Projects 2023
## Problem Statement
With the advent of generative AI, it has become easily difficult to separate real data from AI-Generated.<br>
The goal is to develop a model that can identify a fake photo created by AI.

## Motivation
With the rise of generative AI, fake identities can be easily created using sophisticated algorithms. This has led to an increase in identity fraud, as fake identities can be used to gain access to online services and commit fraudulent activities. Thus, the purpose is to contribute to the development of more secure and reliable online services for everyone.

## Architecture
The architecture follows the common pattern for a convolutional neural network (CNN) designed for image classification tasks. It consists of alternating convolutional and pooling layers to extract and downsample features, followed by fully connected layers for classification. Dropout layers are added to reduce overfitting, and the softmax activation function in the output layer provides class probabilities.

![imagef](https://github.com/gaurav0github/AI-Generated-Image-Detection-VLG-Project/assets/111301879/5539befa-e496-4850-9001-384d4b21c1bc)

## Prerequisites
- Install the necessary dependencies by using the following command:<br>
  `pip install numpy pandas tensorflow scikit-learn`
- The code assumes that the drive you will be mounting contains the `train.csv` and `test.csv` files

## Results
- Best Accuracy: 85.23%
- Best f1 score: 73.49%
