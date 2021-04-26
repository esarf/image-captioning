# Neural Image Captioning

In this project, we propose a deep learning approach to generate automatically the caption of an image. Project done as part of the course Deep Learning; Models and Optimization taught by Marco Cuturi (Google Brain).

**Authors**: Ryan Boustany, Emma Sarfati

## Notebooks

This repo is splitted into two parts:
- `DLnotebook1`: our first approach, based on a CNN-RNN without visual attention weights and a GRU decoder. This notebook is not based on any original paper or code, and uses a simple RNN model as a convolved image as initial state.
- `DLnotebook2`: our second approach, based on the paper of Xu et al. : *Show, Attend and Tell: Neural Image Caption Generation with Visual Attention* (https://arxiv.org/abs/1502.03044). The idea is to add an attention mechanism on the encoded image. 

## Report

The theoretical bases and motivations are detailed in our report in the file `.pdf` 
