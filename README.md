# ESRGAN-Keras

## References  

Recurring the ESRGAN(https://arxiv.org/abs/1809.00219) with Keras  

It is a fork of the project https://github.com/fenghansen/ESRGAN-Keras, that was programed based on https://github.com/MathiasGruber/SRGAN-Keras, and refered from https://github.com/SavaStevanovic/ESRGAN and from https://github.com/xinntao/BasicSR.

## What is new in this project? 

* We implemented the content loss and L1 loss in the separated file.
* We adapted the relativistic discriminator (build_ra_discriminator) and the GAN function (build_esrgan).
* We adapted the loader in train generator (train_generator) to use several workers on CPU for preparing batches.
* New callbacks functions, for example, EarlyStopping, ReduceLROnPlateau, and LearningRateScheduler.
* We adapted the train_esrgan function and in the train.py was introduced news parameters.

#### Environment: Python 3.6 + Keras 2.2.4 + Tensorflow 1.12 

