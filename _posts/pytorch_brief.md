---
layout: default
title: Pytorch
categories: ML
published: true
---
Pytorch is widely getting used in most research papers, hence finally decided on using pytorch for my ML endeavours

## Basic Pytorch
Main functionality of pytorch is creating a class subclassed from nn.Module
Used torch.nn for all losses and optimization
Build a training loop of epochs with the  model
perform gradient optimization within the loop

## Computer Vision
For computer vision transfer learning, first download the model, and set a neural network with the weights of the pretrained model.
then set require_grad=False. This will inshort disable all the previous layers except for the final layer

Then train the data and then predict

## NLP
For NLP transfer learning, use huggingface transformers

Basically encode the input with hugging face transformers. This can be done by first tokenizing, padding and then feeding into transformers for loading the text to vectors

Now use favorite neural network to perform the specific tasks

