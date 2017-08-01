# Hotdog or not hotdog
![](https://media.giphy.com/media/3ohzdSmUdpinK1sX3G/giphy.gif)

A simple hotdog/not hotdog classifier built through transfer learning on InceptionV3. In order to learn about fine-tuning a well known architecture, I decided to begin with the simplest framework, Tensorflow for Poets.

All of the training images were taken from Imagenet (Princeton University and Stanford University).

## Accuracy
98-99% accuracy after being trained on 1400 images (1200 hotdog, 200 not hotdog).
## How to run
In the directory, run `python label_image.py hotdog.jpg` (or any other image you would like to test).
