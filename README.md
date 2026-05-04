# An Empirical Study of Mamba
This code is for Mamba reimplementation of CSCI1470 (Deep Learning) final project. This project and reimplementation is created by Dequan Zhang, Runming Zeng, and Yesheng Guan.

# Main Idea
This project provides an empirical evaluation of the Mamba architecture (state space model) compared to a Transformer baseline.
Our goal is to better understand when and why Mamba works, beyond standard benchmarks.
We reproduce key claims from the original Mamba paper and extend them with additional experiments focusing on:

Long sequence efficiency

Zero-shot performance

Robustness to noisy inputs

Sensitivity to prompt structure

Ablation of selective mechanisms


# Datasets
We use the following datasets:

PubMedQA (pqa_artificial), Used for zero-shot evaluation

WikiText-2, Used for language modeling and robustness testing

You can find them in the "data" folder.



# References

Mamba Paper: https://arxiv.org/pdf/2312.00752

Mamba Repository: https://github.com/state-spaces/mamba
