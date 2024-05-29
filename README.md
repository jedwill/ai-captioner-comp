# Image Captioning Comparison: BLIP vs ViT-GPT2

This repository contains a Python project that compares the image captioning capabilities of two models: Salesforce's BLIP (Bootstrapped Language Image Pre-training) and nlpconnect's ViT-GPT2. The project uses the Hugging Face Transformers library to implement and evaluate these models on a variety of images.

## Project Overview

The purpose of this project is to evaluate and compare the performance and output of two advanced image captioning models. 

## Models

- **BLIP**: Developed by Salesforce, it is designed for generating rich, detailed captions for images. It is based on a bootstrapped pre-training approach that enhances the relevance and accuracy of the captions.
- **ViT-GPT2**: This model combines the Vision Transformer (ViT) with the GPT-2 text generation model, fine-tuned for the task of image captioning.

## Installation

Before running the project, you need to install the required Python packages:

```bash
pip install torch torchvision transformers pillow pandas
