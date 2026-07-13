---
title: "Global-batch load balance almost free lunch to improve your MoE LLM training"
url: "https://qwenlm.github.io/blog/global-load-balance/"
date: "2025-01-21"
author: ""
feed_url: "https://qwenlm.github.io/blog/index.xml"
---
GITHUB HUGGING FACE MODELSCOPE DISCORD Background The Mixture-of-Experts (MoEs) architecture has become a popular model-parameter-scale-up technique. Typically, one MoE layer consists of a router (often parameterized as one single Linear layer) and a group of experts (for transformer-based models, each expert is one feedforward layer). Given an input, only a subset of experts will be activated,...
