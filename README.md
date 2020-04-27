# Basic image augmenter
Basic image augmentation for CNN's. Aiming to add regularisation to your model at the input layer.

Can be used in a pytorch pipeline 


## Setup

Clone repository

`git clone 'https://github.com/lewis-morris/image_augment'`
  
Open directory

`cd image_augment`



## Basic Usage.

Cutout - bocking out random segments of the image - details on this technique can be found here. https://arxiv.org/pdf/1708.04552.pdf

Noise - randomly adds noise to image 

Mirroring - randomly flips image on vertical and horizontal axis.


# For more info check the example jupyter notebook