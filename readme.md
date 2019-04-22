This repo has a single version of tensorflow available for offline install and some supplementary datasets and tutorials.

# Setup
First, install tensorflow:

```
pip install ./wheels/tensorflow-1.13.1-cp37-cp37m-macosx_10_11_x86_64.whl --find-links ./wheels
```

It may seem sad that it's offline but it should finish successfully if you're patient.

Next, move the Keras dataset cache to the correct location.  The directory contains a cached copy of the datasets used in the tutorials and a couple more that you can play around with.

```
cp keras_cache ~/.keras
```

# Tutorials

For an introduction to tensorflow and some basic machine learning concepts, read the Keras guide, downloaded from https://www.tensorflow.org/tutorials/keras found in tutorials/keras_guide.
