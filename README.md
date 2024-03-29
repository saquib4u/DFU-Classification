# DFU-Classification

## Diabetic Foot Ulcer Classification using Deep Learning

<p>Experimented with five different CNN architectures (InceptionV3, ResNet50, DenseNet121,
MobileNet, and VGG16) to classify images of Diabetic Foot Ulcers. These models were trained using
transfer learning, starting with pre-trained weights from ImageNet and fine-tuning them on the target
dataset.
<br><br>
The dataset used in the study consisted of 1051 images, which underwent preprocessing and augmentation
before training the models. The models were trained, validated, and tested on separate sets of data. We have
used evaluation metrics such as accuracy, F1 score, and ROC-AUC score to compare the performance of
the models.
<br><br>
Among the architectures tested, the VGG16 model achieved the highest accuracy and F1 score. On the
testing dataset, the VGG16 model achieved an accuracy of 96.68% and an F1 score of 0.96.
<br><br></p>

### Flowchart: ###
<img src="https://github.com/saquib4u/DFU-Classification/blob/main/DFU%20Flowchart.png" alt="Flowchart for Implementation">
<br><br>

## Resources: ##
* **ResNet121, DenseNet50 and InceptionV3 Implementation on [Google Colab Notebook](https://colab.research.google.com/drive/10FIBxpGV-OBLUzJMhZZBW1BnG3W-mFg6?usp=sharing) and [Jupyter Notebook](https://github.com/saquib4u/DFU-Classification/blob/main/DenseNet_ResNet_InceptionV3.ipynb)**
* **MobileNet and VGG16 Implementation on [Google Colab Notebook](https://colab.research.google.com/drive/1k5uTwY34SWR67Jrz5b514NzmAUS7KWVw?usp=sharing) and [Jupyter Notebook](https://github.com/saquib4u/DFU-Classification/blob/main/MobileNet_VGG16.ipynb)**
* [All five architecture implemented in single Google Colab File](https://colab.research.google.com/drive/1nvpexeoeIWdpJuiPswsFbBeyxDKrpS4z?usp=sharing)
* **Read the associated Research Paper [here](https://doi.org/10.1007/978-981-99-1983-3_35) for further details.**
