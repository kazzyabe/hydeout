---
layout: post
title: "Bert-based Explanation for Citeomatic"
categories:
  - Projects
tags:
  - CBR
  - case-based-reasoning
  - BERT
---
[Click here for the code](https://github.com/kazzyabe/Bert-based_Explanation).

An explanation classifier which classifies input-output pairs of Citeomatic (neural based citation recommendation system) into a relevant citation or not. Used BERT for embedding the abstracts of input and output papers. This model added explanations to “blackbox” decision process in neural models, and outperformed the original CBR (case-based reasoning) model both in terms of accuracy and macro F1 score.