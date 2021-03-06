## Pawpularity Contest
This repository contains the EDA, training and submission code for kaggle Pawpularity contest competition
The goal of the competition is to predict how cute the pet photo is so as to choose the best photo to be put up in the adoption website to increase the rate of adoption
### Kaggle link
https://www.kaggle.com/c/petfinder-pawpularity-score

### Technologies used in these notebooks
1. swinTransformer
2. EfficientNet
3. Training if mixed precision
4. integration and weights and biases
5. GradCam for interpretability of computer vision classification task
6. Crossvalidation and ensembling

## Weights and Biases report link
https://wandb.ai/zuozhe/Pawpularity/reports/Pawpularity-training-charts--VmlldzoxMjYwNjc2?accessToken=ut2ikla3qvdbwgzx1k5j1qhbnp3za6817pl74k7ifl2kf8c33jor6824za13i8ol

<p align="center">
<img src="assets/weights_and_bias.JPG" height="370px" width="550px">
</p>

## GradCAM efficientNet
In this section, we are investigating where the model is "looking at" so we can identify if the model is focusing on the "right" area of the image and not overfit to the background
Please click on picture to see a better resolution picture
<p align="center">
<img src="assets/efficientNetb3_gradcam.png" height="2500px" width="800px">
</p>

## GradCAM swinTransformer
We could see that we are not getting good results with swinTransformers. Further investigation have to be done. This issue could be due to poor model training on my part or like NLP transformers, intepretibility is heavily impacted by the deep self attention layers.
Please click on picture to see a better resolution picture
<p align="center" style="margin: 5px">
<img src="assets/swinTransformer_gradcam.png" height="2500px" width="800px" >
</p>

