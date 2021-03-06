# Some Techniques

## Lag

Introduce delay into the data by `n` steps. 
Usually to prepare the data set in such a way that the model learns to predict `n` steps in the future.

## Dif

With `Dif` (or `Diff`) we calculate the difference from the previous values of the `Lag` that we have introduced.

## Out-Of-Bag (OOB)

Samples that have not been used during model training.

## Out-Of-Bag-Error (OOBE)

Calculating the trained model's error by using samples that have not been used for its training.

## Sub-sampling with replacement (aka Bootstrapping)

Pick a sample each time from the whole population.

## Fixed Feature Extraction

Push an image through a pretrained neural network and then construct the resulting filtered image from the output of the last hidden layer of neurons.
Then use this filtered image as input to the model (e.g. neural network)