# Fine-Tuning different LLms with LoRA, PEFT, and QLoRA

This repository contains a Jupyter Notebook for fine-tuning the Gemma-7B model using various techniques including LoRA (Low-Rank Adaptation), PEFT (Parameter-Efficient Fine-Tuning), and QLoRA (Quantization-aware Low-Rank Adaptation). These methods are designed to optimize the model's performance and efficiency, making it suitable for deployment in resource-constrained environments.

## Notebooks

Each Notebook is named with the correspoding Model name

- **Mistral-7B-Instruct**
- **Gemma-7B**
- **Llama2-7B**



## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Methods](#methods)
  - [LoRA](#lora)
  - [PEFT](#peft)
  - [QLoRA](#qlora)


## Overview

Fine-tuning large language models like Gemma-7B can be computationally expensive and time-consuming. This repository demonstrates how to effectively fine-tune the Gemma-7B model using LoRA, PEFT, and QLoRA techniques to enhance efficiency and performance.

## Features

- **LoRA**: Apply low-rank adaptations to the model's weight matrices.
- **PEFT**: Utilize parameter-efficient fine-tuning methods to reduce the number of trainable parameters.
- **QLoRA**: Combine quantization and low-rank adaptation for efficient model deployment.

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/gemma7b-finetuning.git
cd gemma7b-finetuning
pip install -r requirements.txt
