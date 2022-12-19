# Temporal Adaptation

<h1 align="center">
  CompGCN
</h1>

<h4 align="center">Composition-Based Multi-Relational Graph Convolutional Networks</h4>

<p align="center">
  <a href="https://iclr.cc/"><img src="http://img.shields.io/badge/ICLR-2020-4b44ce.svg"></a>
  <a href="https://arxiv.org/abs/1911.03082"><img src="http://img.shields.io/badge/Paper-PDF-red.svg"></a>
  <a href="https://iclr.cc/virtual/poster_BylA_C4tPr.html"><img src="http://img.shields.io/badge/Video-ICLR-green.svg"></a>
  <a href="https://medium.com/@mgalkin/knowledge-graphs-iclr-2020-f555c8ef10e3"><img src="http://img.shields.io/badge/Blog-Medium-B31B1B.svg"></a>
  <a href="https://github.com/malllabiisc/CompGCN/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg">
  </a>
</p>


Baseline.py runs the experiments, using the following arguments:


-e : Experiment type ("base", "dcwe", "transh", "ta", "lm", "dated")

-d : Dataset ("sandy", "clex", "humaid")

-r : Run type ("controlled", "temporal", "progressive")

-o : Output directory

-l : Limit (int, will restrict instances in trianing/dev/test for testing)
