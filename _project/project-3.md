---
title: "pneumonia_detector(Chest x_ray CNN)<br/><img src='/images/cnn_project.png'>"
excerpt: "This application uses artificial neural network as a filter to classify the image. The output of the neural network is scaled so as to get the proper sizes of the images that are classified and can be used by radiologists to predict the abnormality up to a great extent.    
"
collection: project
---
# x_ray
![alt text](image.png)
```sh
install comet-ml from pypi
mxnet,gluoncv.
```
Register at (https://www.comet.ml/site/?cache=62352245) here confusion matrix will be stored.
Important::Change your api key which you will get after registraion under quick start guide with workspace given as active workspace 
in this line of code.
<experiment = Experiment(api_key="uVlCssu6MSf2jDhTxV9guqoDI",project_name="model",workspace="yatharth-123")>

1.Libraries to be installed:
```sh
   pip install mxnet-cu101
   pip install gluoncv
```
tutoials:

<https://gluon-cv.mxnet.io/build/examples_classification/transfer_learning_minc.html>

kaggle-dataset:

<https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>

About Resnet Model used in the project:
<https://numpy.mxnet.io/api/gluon/_autogen/mxnet.gluon.model_zoo.vision.resnet50_v2.html>

<https://github.com/KaimingHe/resnet-1k-layers>

<https://arxiv.org/abs/1603.05027>
