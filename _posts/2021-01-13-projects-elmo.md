---
layout: post
title: "POS Tagger With Elmo Embeddings"
categories:
  - Projects
tags:
  - POS
  - part of speech
  - elmo
  - tagger
---

A part of speech tagger implemented in Python with TensorFlow using Universal Dependency corpus. Used pretrained Elmo Embeddings through TensorFlow Hub. The model includes Elmo Embeddings layer, Bidirectional LSTM layer, and a softmax dense layer. If an appropriate Elmo embedding is loaded, the tagger can be trained on any languages which have Universal Dependency corpus. Used Keras for incorporating some layers. Evaluated the model by F1 scores.

[Click here for the code](https://github.com/kazzyabe/POS_Elmo)