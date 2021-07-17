# cat_prediction
Introduction
This guide covers training, evaluation, and prediction (inference) models when using built-in APIs for training & validation (such as Model.fit(), Model.evaluate() and Model.predict()).

If you are interested in leveraging fit() while specifying your own training step function, see the Customizing what happens in fit() guide.

If you are interested in writing your own training & evaluation loops from scratch, see the guide "writing a training loop from scratch".

In general, whether you are using built-in loops or writing your own, model training & evaluation works strictly in the same way across every kind of Keras model -- Sequential models, models built with the Functional API, and models written from scratch via model subclassing.

This guide doesn't cover distributed training, which is covered in our guide to multi-GPU & distributed training.
