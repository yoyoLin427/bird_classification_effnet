# Bird images classification
This repository is related to the [Selected Topics in Visual Recognition using Deep Learning Homework 1](https://www.google.com/url?q=https://competitions.codalab.org/competitions/35668?secret_key%3D09789b13-35ec-4928-ac0f-6c86631dda07&sa=D&source=editors&ust=1636039312184000&usg=AOvVaw3hIm2ASXDRpbGdAYGSR3XC).

## Getting started
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cHVv9qiuVlsUws5p6yR0nvBwGqPMEKK-?usp=sharing)



please use colab to open the file "inference.py"
just execute this file on colab,

it will automatically load the model and reproduce submission file



## Training 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1E-_HXc_I3Tcqord_T-3swV3JQyjtJdKA?usp=sharing)

be specified in `bird_v11_sgd.py`.

if you want to try this file, please change the file path in code

I found that use SGD as learning rate, larger the image input size and reduce the batch size can improve the model.


## Future work:

If there is time, I will try to adjust the learning rate and try to unfreeze only a portion of layers gradually while training.
