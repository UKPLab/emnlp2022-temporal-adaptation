
<h2 align="center">The challenges of temporal alignment on Twitter during crises</h2>

<p align="center">
  <a href="https://2022.emnlp.org/"><img src="https://img.shields.io/badge/Findings%20of%20EMNLP-2022-4b44ce"></a>
  <a href="https://arxiv.org/abs/2104.08535"><img src="http://img.shields.io/badge/Paper-PDF-red.svg"></a>
  <a href="https://github.com/UKPLab/emnlp2022-temporal-adaptation/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg">
  </a>
</p>


Baseline.py runs the experiments, using the following arguments:


-e : Experiment type ("base", "dcwe", "transh", "ta", "lm", "dated")

-d : Dataset ("sandy", "clex", "humaid")

-r : Run type ("controlled", "temporal", "progressive")

-o : Output directory

-l : Limit (int, will restrict instances in trianing/dev/test for testing)
