---
language: en
tags:
- ConvMixer
- keras-io
license: apache-2.0
datasets:
- cifar10
---

#ConvMixer model
The ConvMixer model is trained on Cifar10 dataset and is based on [the paper](https://arxiv.org/abs/2201.09792v1), [github](https://github.com/locuslab/convmixer). 

Disclaimer : This is a demo model for Sayak Paul's keras [example](https://keras.io/examples/vision/convmixer/). Please refrain from using this model for any other purpose.

##Description

The paper uses 'patches' (square group of pixels) extracted from the image, which has been done in other Vision Transformers like [ViT](https://arxiv.org/abs/2010.11929v2). One notable dawback of such architectures is the quadratic runtime of self-attention layers which takes a lot of time and resources to train for usable output. The ConvMixer model, instead uses Convolutions along with the MLP-mixer to obtain similar results to that of transformers at a fraction of cost.

###Intended Use
This model is intended to be used as a demo model for keras-io.
