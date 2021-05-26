---
layout: post
title: "Graph-Based Dependency Parser"
categories:
  - Projects
tags:
  - POS
  - part of speech
  - elmo
  - tagger
---


This parser extended [a perceptron part-of-speech tagger](https://github.com/ftyers/conllu-perceptron-tagger.git) into dependency parser. It works on any of universal dependency corpus in a conllu format. 

The parser first scores each possible edge using perceptron, and figure out a maximum spanning tree. 

[Click here for the code](https://github.com/kazzyabe/graph-parser).