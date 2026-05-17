# Neural Networks: Zero to Hero — Makemore Reimplementation

This repository contains my personal learning reimplementation of Andrej Karpathy’s `makemore` project from the *Neural Networks: Zero to Hero* series.

Link to YouTube series: https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ

The project explores character-level language modeling by building neural networks that learn to generate name-like text from a dataset of names. The notebooks were created as I followed along with the video series, reimplemented the core ideas, and added my own notes, experiments, and organization.

## Project Purpose

I created this repository while preparing for my master’s program and building foundational knowledge in artificial intelligence, machine learning, and neural networks.

The goal of this project was to strengthen my understanding of:

- character-level language modeling
- embeddings
- multilayer perceptrons
- PyTorch model implementation
- manual backpropagation
- gradient checking
- neural network training loops
- batch normalization
- WaveNet-style architectures
- model evaluation and text generation

This is best understood as a guided learning project rather than an original research project.

## Repository Structure

```text
.
├── data/
│   ├── names.txt
│   └── README.md
├── notebooks/
│   ├── makemorePT3_pytorch.ipynb
│   ├── makemorePT3_mac.ipynb
│   ├── makemorePT4_BackwardPass.ipynb
│   └── makemorePT5_WaveNet.ipynb
├── requirements.txt
├── LICENSE
└── README.md

'''

## Attribution

This project is a personal learning reimplementation of concepts from Andrej Karpathy’s
*Neural Networks: Zero to Hero* series and the accompanying `makemore` project.

Original project: https://github.com/karpathy/makemore

The notebooks in this repository reflect my own follow-along implementations, experiments,
notes, and organization while studying the series.
