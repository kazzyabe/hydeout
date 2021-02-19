---
layout: post
title: "Knowledge Based Taxonomy Classifier"
categories:
  - Projects
tags:
  - Knowledge-based
  - Rule-based
---
[Click here for the code](https://github.com/kazzyabe/Knowledge_Based_Taxonomy).

This is an assignment from B552 "Knowledge Based AI." In this assignment, I implemented a rule based system to derive animal taxonomy from given information. The rules are in the form (name, left hand side (LHS), right hand side (RHS)), and the classifier performs depth first search to match the LHS of rules and apply substitution on the RHS to derive new knowledge. The classifier ends its execution when no more new knowledge is derived by the algorithm. 