# Data

This folder contains the dataset used for the character-level language modeling notebooks.

## Included Dataset

### `names.txt`

This file contains a list of names used to train character-level language models. Each line contains one name.

The models use this file to learn character sequence patterns and generate new name-like text.

## Source and Attribution

This dataset is included with Andrej Karpathy’s original `makemore` project, which accompanies the *Neural Networks: Zero to Hero* series.

Original project: https://github.com/karpathy/makemore

Please refer to the original repository for additional context about the dataset source and intended educational use.

## Expected Format

The notebooks expect `names.txt` to be a plain text file formatted as:

```text
emma
olivia
ava
isabella
...
