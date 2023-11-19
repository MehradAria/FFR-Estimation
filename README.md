# FFR-Estimation
## Non-Invasive Fractional Flow Reserve Estimation using Deep Learning on Intermediate Left Anterior Descending Coronary Artery Lesion Angiography Images

This repository contains an end-to-end deep learning model for estimating the value of fractional flow reserve (FFR) using angiography images to classify left anterior descending (LAD) branch angiography images with average stenosis between 50% and 70% into two categories: FFR>80 and FFR≤80. In this study 3625 images were extracted from 41 patients’ angiography films. Ten pre-trained convolutional neural networks (CNN), including `DenseNet-121`, `InceptionResNetV2`, `VGG-16`, `VGG-19`, `ResNet50V2`, `Xception`, `MobileNetV3Large`, `InceptionV3`, `DenseNet-201`, and `DenseNet-169`, were used to extract the features of images. DenseNet169 indicated higher performance compared to other networks. Accuracy, Sensitivity, Specificity, Precision, and F1-score of the proposed `DenseNet-169` network were 0.81, 0.86, 0.75, 0.82, and 0.84, respectively. The deep learning-based method proposed in this study can non-invasively and consistently estimate FFR from angiographic images, offering the significant clinical potential for diagnosing and treating coronary artery disease by combining anatomical and physiological parameters.

## Model architecture
<h1 align="center">
 <a href="https://github.com/MehradAria/FFR-Estimation"><img src="https://github.com/MehradAria/ALL-Subtype-Classification/blob/main/Model.png?raw=true" alt="Non-Invasive Fractional Flow Reserve Estimation using Deep Learning on Intermediate Left Anterior Descending Coronary Artery Lesion Angiography Images"></a>
</h1>

## Inference
You may use [Classifier.ipynb](https://github.com/MehradAria/FFR-Estimation/blob/main/Classifier.ipynb), inference is as simple as:

```shell
# Example
classes = Classifier.predict([Test_img])
```

---
### Paper / Data / Pre-trained model availability:
- Due to the policies and guidelines of Shahid Beheshti University of Medical Science, data is not allowed for publication.

- The model is not publicly available at this moment due to Git LFS limitations.

---
### Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1) Please cite the following paper:
```
Arefinia, F, Aria, M, Rabiei, R, Hosseini, A, Ghaemian, A, Roshanpoor, A.
Non-Invasive Fractional Flow Reserve Estimation using Deep Learning on Intermediate Left Anterior Descending Coronary Artery Lesion Angiography Images.
J. 2023; 37: 5113- 5133. doi:X
```

2) Please do not distribute the database or source codes to others without author authorization.
Authors’ Email: `mehrad.aria[at]shirazu.ac.ir` (M. Aria).

