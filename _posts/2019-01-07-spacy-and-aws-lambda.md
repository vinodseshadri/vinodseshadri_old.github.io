---
layout: default
title: Spacy on Lambda
published: true
---
Hosting machine learning models on Amazon Web Services Lambda, is one of the cheapest ways to deploy ML models. AWS Lambda calculate costs on Lambda purely on the basis of calls and compute time, hence giving the flexibility in controlling the cost of hosting the models

But on the flip side, lambda comes with lot of limitations with reference to the size of the package and the computing abilities of these serverless services.

Though there are many ways to come around these, in my blog today, I will be presenting my experiences over the weekend, on getting a spacy(a obviously huge python library) based NLP code onto AWS lambda.  It wasn't a smooth experience but in the end I prevailed :)