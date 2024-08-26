# Project Title

## Table of Contents
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [Acknowledgments](#acknowledgments)

## Dataset
We used the [Flickr8k Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k) from Kaggle, which contains 8,000 images and 40,000 captions.

## Model Architecture
The model utilizes ResNet-152 as a feature extractor and LSTM as the caption generator.

![image](https://github.com/user-attachments/assets/561e989f-7ffb-4770-8784-419df7abcae1)


## Training
We split the dataset into 90% for training and 10% for validation. The loss function used is categorical cross-entropy, and the optimizer is Adam.

## Results

![image](https://github.com/user-attachments/assets/b45cdec5-c5b8-407a-aa6c-a2187afa8b2b)

![image](https://github.com/user-attachments/assets/b3cecbff-4df4-4582-b160-ecc427e2dadb)

![image](https://github.com/user-attachments/assets/f02f4ebf-7b0a-483d-a5e4-ed29ddd37b36)

