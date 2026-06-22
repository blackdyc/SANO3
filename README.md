<div align="center">


# From Visual Primitives to Semantic Masks: Fine-Grained Visual-Linguistic Alignment for Open-Vocabulary Remote Sensing Image Segmentation


</div>

## Overview

Open-vocabulary semantic segmentation enables text-driven segmentation of novel classes, but fine-grained remote sensing scenarios remain challenging due to visual similarity, semantic ambiguity, and blurry object boundaries. **SANO3** is a training-free framework that enhances SAM 3 with refined textual and spatial guidance. It leverages the visual self-similarity priors of vision foundation models to extract discriminative visual primitives, aligns them with text queries through visual-conditioned relation-aware alignment, and injects hybrid visual prototypes for deeper visual-linguistic fusion. To further refine boundaries, SANO3 formulates spatial prompt generation as an iterative information-gain process that greedily selects informative point prompts via entropy reduction.

## Benchmark

We introduce **FG-OVSSRS**, a fine-grained open-vocabulary semantic segmentation benchmark for remote sensing images. The benchmark covers diverse remote-sensing scenarios and provides synonym-expanded category queries to evaluate model robustness under flexible real-world open-vocabulary usage.

The benchmark is publicly available on Hugging Face: 🤗 [FG-OVSSRS Bench](https://huggingface.co/datasets/blackdyc/FG-OVSSRS)


## TODO

- [x] Release the FG-OVSSRS benchmark.
- [ ] Release SANO3 code.
