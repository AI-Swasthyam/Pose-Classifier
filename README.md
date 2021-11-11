# Pose-Estimator
## Getting Started
Clone The Repository    :
```bash
   git clone https://github.com/AI-Swasthyam/Pose-Classifier
   cd Pose-Classifier
```
### Requirements
* Python 3.7 (numpy, skimage, scipy, opencv)  
* PyTorch >= 1.9.1
* mediapipe library [installation](https://google.github.io/mediapipe/getting_started/install.html)

### Training
``` bash
    python3 -m poseEst.modelLib.train
```
### Dataset
* Download [dataset](https://www.kaggle.com/nandwalritik/yoga-pose-videos-dataset) from here place it inside datasets folder and unzip it, for refrence please see the attached image for directory structure.

![Screenshot from 2021-11-11 18-41-29](https://user-images.githubusercontent.com/48522685/141304008-9d2e0635-e1f1-45f7-96eb-40a1a53c05c0.png)

### Visualization of what our model is trying to learn ?
<img src='./poseEst/demoImages/SamplePose.gif' width=500>

### Note
* Final Training weights to be updated !

