---
layout: post
title: "Jointly Trained Part-Of-Speech (POS) tagger and Graph-Based Parser"
categories:
  - Projects
tags:
  - POS
  - part of speech
  - elmo
  - tagger
---

[Click here for the code](https://github.com/kazzyabe/Joint_POS_PARSE).

This is a extension of [the graph-based dependency parser](/hydeout/projects/2021/01/13/projects-graph.html). Instead of training POS tagger and dependency parser separately, it trains them at the same time to avoid the error propagation. 

With the parser above, you have to run a POS tagger before running the parser because POS tags are a important feature that is used in the parser. Therefore, the error of the POS tagger is propagated to the parser. To avoid this propagation, a tagger and a parser is trained using the shared features.