# Neural Network Quantization Demo

This repository contains practical examples of post-training quantization for neural networks, including manual implementation of symmetric and asymmetric quantization in PyTorch.

## Features

- Manual quantization/dequantization of tensors
- Implementation of post-training symmetric quantized linear layer (`PTQSymmetricQuantizedLinear`)
- Comparison of quantized and original float32 inference
- Easy-to-follow code, fully reproducible

## Files

- `quantization_example.ipynb`: Jupyter notebook demonstrating quantization, dequantization, error analysis, and how to use the quantized linear layer.
- `ptq_linear.py`: Source code for the quantized linear layer as a reusable PyTorch module.

## Usage

Clone the repo and run the notebook:

```bash
git clone https://github.com/your-username/neural-network-quantization.git
cd neural-network-quantization
pip install torch
jupyter notebook quantization_example.ipynb
