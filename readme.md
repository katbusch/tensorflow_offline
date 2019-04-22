This repo has a single version of tensorflow available for offline install and some supplementary datasets and tutorials.

# Setup
First, install tensorflow:

```
pip install --no-cache-dir ./wheels/tensorflow-1.13.1-cp37-cp37m-macosx_10_11_x86_64.whl --find-links ./wheels
```

Next, move the Keras dataset cache to the correct location:

```
cp keras_cache ~/.keras
```

# Tutorials

For an introduction to tensorflow and some basic machine learning concepts, read the Keras guide, downloaded from https://www.tensorflow.org/tutorials/keras found in tutorials/keras_guide.
