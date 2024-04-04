# Building-Transformers
## Introduction

This tutorial is designed to guide you through the intricacies of the attention mechanism, enabling you to construct a self-attention layer and develop your own transformer model from scratch. We aim to demystify the process, making it more accessible by breaking down complex concepts and providing a hands-on approach to learning.

## Preparing Your Environment

### GPU Training in Colab

- **Activating GPU Runtime**: Ensure you're using the GPU runtime to avoid errors and speed up training.
  1. Navigate to "Runtime" > "Change runtime type".
  2. Select "GPU" as your hardware accelerator.
  3. Save the changes.


### Setting Up

First, install necessary libraries and set a fixed seed for reproducibility:

```python
pip install torch
pip install numpy
pip install matplotlib


