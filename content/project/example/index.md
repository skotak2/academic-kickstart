---
slides: example
url_pdf: ""
title: Image Captioning With Visual Attention
summary: An example of using the in-built project page.
url_video: ""
date: 2016-04-27T00:00:00Z
external_link: https://github.com/skotak2/Image-Captioning-With-Visual-Attention-Mechanism
url_slides: ""
subtitle: "CNN Encoder - RNN(LSTM & GRU) decoder model for captioning an image
  with visual attention mechanism. "
tags:
  - Deep Learning
links:
  - url: https://github.com/skotak2/Image-Captioning-With-Visual-Attention-Mechanism
    name: GitHub
image:
  caption: ""
  focal_point: Smart
  filename: ""
url_code: ""
---
## INTRODUCTION

The concept of image captioning is novel problem which deals with cognition of image processing, language modelling and recurrent neural networks. Ability to generate descriptions for image has a myriad number of applications across the industry. The social media platforms have enormous amount of need for these kinds of applications where there is huge surge of images which could help draw insights for business and decision-making purposes. The problem is framed with encoder – decoder flow line with recurrent nueral network layers. Further we also capture the image visual attentions and use it for descriptions. We use pretrained models for implementing CNN as the encoder, and further use RNNs (GRU & LSTM) to translate the objects in image to words to frame a natural sentence. Model takes an image I as input and is trained to maximize the likelihood p(W|I) of producing a target sequence of words W = {W1, W2, W3 . . .Wt} where each word Wt comes from a given vocabulary, while W would also have the start and stop tokens for the sentences. The image vectors are generated using CNN with help of pretrained models. Given the existence of context in the caption a BLEU score metric is used to gauge the performance of model.