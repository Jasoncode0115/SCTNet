# SCTNet
## Offcial implementation of "SCTNet: Structured and causality-guided spatio-temporal diffusion network for unsupervised traffic accident detection".

![pipeline](./SCTNET_files/model.png)
## 1. Dependencies
```
python==3.6.13
scipy==1.5.3
tqdm==4.63.0
yacs==0.1.8
pyyaml==6.0.1
requests==2.27.1
protobuf==3.19.6
torch==1.10.2+cu113
opencv==4.5.3
pillow==6.2.2
matplotlib==3.3.4
scikit-learn==0.24.2
torchvision==0.11.3+cu113
torchaudio==0.10.2+cu113
torch-geometric==2.0.3
numpy==1.19.5
pandas==1.1.5

```
## 2. Usage
### 2.1 Data preparation

![pipeline](./SCTNET_files/dataset.png)

We created a large traffic accident dataset called 4M-TAD containing frame-level labels standardized for unsupervised traffic accident detection.

As the paper is currently in the process of submitting, the dataset needs to be kept confidential for the time being, here we only disclose part of the dataset:

[4M-TAD_Part_1](https://drive.google.com/file/d/1WXcdSDeiVRNw4gcVnvqtQmVdFDpCtecN/view?usp=sharing)

The full dataset will be updated after the acceptance of the article.

### 2.2 Train
The paper is under review and now needs to be kept confidential.
Code will be available soon.
### 2.3 Evaluation
The paper is under review and now needs to be kept confidential.
Code will be available soon.

## 3. Results
AUC is the core indicator.

|     Model      | 4M-TAD | AI City Challenge 2021 | 
| :------------: | :-------: | :---------: | 
|    SCTNet    |   88.89%   |    87.45%    | 

## Acknowledgment
The paper is under review and now needs to be kept confidential.

## Citation
The paper is under review and now needs to be kept confidential.
