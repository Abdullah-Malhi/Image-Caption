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

## Dataset <a id="dataset"></a>
We used the [Flickr8k Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k) from Kaggle, which contains 8,000 images and 40,000 captions.
We used the same dataset for all these models.

## Model Architectures <a id="model-architecture"></a>
1-The model utilizes ResNet-152 as a feature extractor and LSTM as the caption generator.
![image](https://github.com/user-attachments/assets/561e989f-7ffb-4770-8784-419df7abcae1)
2-Another Model used was Resnet 18 with Transformer decoder.
![image](https://github.com/user-attachments/assets/adf3c07a-ebdb-423c-8ca7-ff6b2ab1e980)

3-Last approach was Resnet 152 along with Transformer decoder.

## Training <a id="training"></a>
We split the dataset into 90% for training and 10% for validation. The loss function used is categorical cross-entropy, and the optimizer is Adam.

## Results <a id="results"></a>
For Renset 152 LSTM
![image](https://github.com/user-attachments/assets/b3cecbff-4df4-4582-b160-ecc427e2dadb)
![image](https://github.com/user-attachments/assets/f02f4ebf-7b0a-483d-a5e4-ed29ddd37b36)
For Resnet 18 Transformer
![image](https://github.com/user-attachments/assets/9247fc2f-ee65-4b0a-91a0-9e4ce1693b03)
![image](https://github.com/user-attachments/assets/e373c0b4-19a8-4f27-9021-8387aea75357)
For Resnet 152 Transformer
![image](https://github.com/user-attachments/assets/f065721e-f9c2-46a7-b235-600c14fb612a)







