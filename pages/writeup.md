---
layout: page
permalink: /writeup.html
title: A timeline of DL in NLP
description: my short summary on DL in NLP
header-img: 
last-updated: 2020-10-30 5:55 PM
---

<h1 class="mx-auto" style="font-family:Courgette;">{{ page.title }}</h1>

I've been working on the application of DL in NLP since 2018. From my very first class on this topic, and the very first paper I read in this area, I've been fascinated by the progress that's happened so far, and the possibilities of what we can do in the future. This short write-up is my take on the timeline of DL in NLP - specifically Seq2Seq models, and interpretability of models.
<br><br>

<!-- When we (researchers) first started implementing deep models to solve tasks, we were excited by the leaps and bounds by which performances improved. This led to a surge in the development of deep models and techniques; in the last couple of years this has culminated in the release of pretrained language models such as ELMO, BERT, XLNET etc., which took us to human level performances on many exsiting datasets.  -->


<!-- But now, with deep models achieving SOTA and human-level performances on many complex tasks, the focus has shifted to understanding the logic used by the models developed so far, and to develop new methods, datasets and models that inherently incorporate the idea of interpretability.  -->

Due to the unique nature of NLP mostly having *dynamic sequence* type inputs and outputs, it became necessary to modify and adapt the standard structure of the neural network. This led to the development of *Recurrent-Neural-Networks* (RNNs), which can process temporal relations in data and work for any dynamic length of the input and output sequences.

To improve on this further, researchers then developed the LSTM (Long-Short-Term-Memory) and the GRU