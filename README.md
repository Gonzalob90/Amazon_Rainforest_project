# Image Classification of Satellite images of the Amazon Rainforest

we aim to explore and compare the performance of different Convolutional Neural Network (CNN) architectures. We draw our motivation 
from the multi-class labelling problem posed by the Amazon rainforest dataset on Kaggle. The architectures considered are: 4 and 5 layer CNN models, 
VGG models, and ensemble models. We also discuss in detail the issues faced when scaling from binary classification tasks to multilabel
classification tasks.

## Dataset

The full dataset consists of 40,478 satellite images. The images are 256x256 pixels with 4 channels (RGB and infrared) and each image covers 90 hectares of land.
There are 17 labels that each image can be classified by. These fall into 3 broad categories: Weather conditions, common cover/activity and
rare cover/land use. Weather conditions include: clear, partly cloudy, cloudy, and haze. The common cover/land use labels are: 
primary rainforest, Water (rivers and lakes), Habitation, agriculture, road, cultivation and bare ground. The rare cover/land use
labels include slash and burn agriculture, selective logging, blooming, conventional mining, and artisanal mining.

<br>
<p align="center">
<img src=misc/dataset.png>
</p>
<br>

The frequency of the 17 labels is also quite varied; with the primary label denoting forest forming 90% of images, whereas mining 
appears in less than 1% of images.

<br>
<p align="center">
<img src=misc/histogram.png>
</p>
<br>

## Model

<br>
<p align="center">
<img src=misc/CNN.png>
</p>
<br>


<br>
<p align="center">
<img src=misc/VGG.png>
</p>
<br>

## Results

<br>
<p align="center">
<img src=misc/training.png>
</p>
<br>


<br>
<p align="center">
<img src=misc/confusion_matrix.png>
</p>
<br>

<br>
<p align="center">
<img src=misc/table.png>
</p>
<br>

## Further ideas

<br>
<p align="center">
<img src=misc/ensemble.png>
</p>
<br>
