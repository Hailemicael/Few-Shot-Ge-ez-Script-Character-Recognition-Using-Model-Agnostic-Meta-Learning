# Few-Shot Ge'ez Script Character Recognition Using Model-Agnostic Meta-Learning

## Overview
This repository contains the implementation of a few-shot learning approach for Ge'ez script character recognition using Model-Agnostic Meta-Learning (MAML). The system leverages a CNN-based architecture with MAML's nested optimization framework to learn an initialization that can quickly adapt to new character classes with minimal examples.

## Features
- Implementation of MAML for Ge'ez script character recognition
- Comparative analysis with traditional approaches:
 - Conventional CNN models
 - CapsNet implementation
 - Vision Transformer (ViT) adaptation
 - Traditional ML techniques

## Repository Structure
- `MAML Geez Character.ipynb`: Implementation of Model-Agnostic Meta-Learning for Ge'ez script
- `Geez Chara_CNN.ipynb`: Standard CNN approach for character recognition
- `CapsNet.ipynb`: Capsule Network implementation for comparison
- `VIT.ipynb`: Vision Transformer approach for Ge'ez characters
- `Traditional_ML.ipynb`: Classical machine learning techniques

## Methodology
Our approach uses MAML's meta-learning framework to optimize a model initialization that can be fine-tuned to recognize new Ge'ez characters with just a few examples. This addresses the challenge of limited labeled data for less-resourced scripts like Ge'ez.

The key innovations include:
- Two-level optimization process (meta-learning and adaptation)
- Fast adaptation to new character classes
- Robust feature extraction for the unique characteristics of Ge'ez script

## Experimental Results
The MAML-based approach significantly outperforms traditional methods in few-shot learning scenarios, demonstrating:
- Higher accuracy with limited examples (1-5 shots)
- Better generalization to unseen character variations
- Faster convergence during adaptation

## Requirements
- Python 3.7+
- PyTorch
- TensorFlow
- NumPy
- Matplotlib
- Scikit-learn

## Citation
If you use this code for your research, please cite our work:
