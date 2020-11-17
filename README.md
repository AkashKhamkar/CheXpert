# CheXpert
### ABOUT:
#### The CheXpert dataset contains Xrays for 14 different Feature Classes, the goal is to identify each label(i.e. feature class) from just passing the Xray image as an Input.
#### The Size of the dataset is 11GB and contains 2,23,414 imaegs for training and 234 images for validation , as the size is quite large it takes a lot of time to compute. Hence only 10% of the dataset was used in this project.
#### The (10%)dataset was then split into train and test with 22,341 and 500 images respectively.

```
(Nvidia's GTX 1060 6GB was used for training)
```
### **ROC**
![OUTPUT](https://github.com/AkashKhamkar/CheXpert/blob/main/images/roc.PNG)

### **Visualizing feature maps for Transition layer 1**
![OUTPUT](https://github.com/AkashKhamkar/CheXpert/blob/main/images/feature_maps_t1.PNG)

### Outputs:
#### 1. For Class Support Devices
![OUTPUT](https://github.com/AkashKhamkar/CheXpert/blob/main/images/support_devices.PNG)
#### 2. For Class No Finding
![OUTPUT](https://github.com/AkashKhamkar/CheXpert/blob/main/images/no_finding.PNG)

