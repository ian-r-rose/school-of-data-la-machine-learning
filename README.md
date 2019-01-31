<div style="display: flex; width: 100%">
    <img style="height: 200px" src=./images/pink-donut-logo.png />
    <img style="height: 200px" src=./images/schoolofdata-logo.png />
</div>

<small><i>This tutorial is modeled after a series of tutorials by [Jake Vanderplas](http://www.vanderplas.com). Text, code, and licenses to those may be found [here](https://github.com/jakevdp)</i></small>

# Introduction to Machine Learning
#### Ian Rose (Project Jupyter) February 2, 2019

## What is a model?

We are often faced with a pile of data, and no notion of what to do with it.
We know that the data reflects some information about the real world, but not necessarily what that is, and how to get at it.

A model is a representation of a real-world process that we want to understand.
They can be qualitative or quantitative, complex or simple.
Broadly speaking, models are useful in two ways:

1. They provide understanding. Models are simpler than the real world, and the specific "physics" of a model can often be interpreted in terms of plain language. Frequently the interpretability of a model is among the most attractive of its attributes.

2. They have predictive power. You can use a good model of the real world to predict the behavior of hypothetical data or data you have not seen before. You can use these predictions to provide guidance for future data collection, policy, and model refinements.

## What is machine learning?

Machine learning is the process of building statistical models using computers.
You typically ingest existing data to fit a model, and then use that model to predict values from data that the model has not seen before.

There are many different classes of model, and many different methods of fitting and predicting, but they all follow this general pattern.

## This tutorial

This tutorial consists of several exercises that introduce the user to simple machine learning.
They use the de facto standard Python scientific software stack,
principally numpy, scipy, matplotlib, pandas, and (crucially) scikit-learn.