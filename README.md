# D2NN — Diffractive Deep Neural Network

Numerical simulation of a diffractive neural network with trainable phase masks.
The notebook includes MNIST classification, Gerchberg–Saxton initialization,
and experiments on sensitivity to wavelength changes and phase noise.

Authors: Rodion Akinzhala, Kseniia Ibragimova.

**[Main presentation (English, PDF)](docs/d2nn_presentation_eng.pdf)**

## Contents

- [Notebook](code/D2NN.ipynb) — simulation, training and experiments.
- [Project article (Russian, PDF)](docs/D2NN_VPV_article.pdf).
- [Earlier presentation (Russian, PDF)](docs/D2NN_slides.pdf).

## Using the notebook

Open `code/D2NN.ipynb` in Jupyter or a compatible notebook environment.
It uses TensorFlow/Keras and includes installation cells for `cvnn` and `tf-keras`.
MNIST is downloaded through `tensorflow-datasets`. Some optional logo examples
require external images from Kaggle.
