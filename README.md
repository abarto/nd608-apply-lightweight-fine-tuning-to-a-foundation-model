## nd608 - Apply Lightweight Fine-Tuning to a Foundation Model

### Introduction

This is repo contains my implementation for Udacity's Generative AI Nanodregree "Apply Lightweight Fine-Tuning to a Foundation Model" project. For this project, I've chosen the following configuration:

* PEFT technique: [`QLoRA`](https://huggingface.co/docs/peft/conceptual_guides/adapter#low-rank-adaptation-lora)
* Model: [`gpt2`](https://huggingface.co/openai-community/gpt2)
* Evaluation approach: Hugging Face's [`Trainer.evaluate`](https://huggingface.co/docs/transformers/main_classes/trainer#transformers.Trainer.evaluate)
* Fine-tuning dataset: [`imdb`](https://huggingface.co/datasets/imdb)

The model was trained on my own infrastructure:

* Ryzen 7 5800X
* 64Gb DDR4
* NVIDIA RTX 4070 TI
* Ubuntu 23.10

### Contents

| File/Folder | Description |
|-------------|-------------|
| [`LightweightFineTuning-template.ipynb`](LightweightFineTuning-template.ipynb) | Jupyter Notebook template, provided by Udacity. |
| [`LightweightFineTuning.ipynb`](LightweightFineTuning.ipynb) | Jupyter Notebook with the project submission. |
| [`LightweightFineTuning.html`](LightweightFineTuning.html) | HTML export of the Jupyter Notebook with the project submission. |
| [`nd608/gpt2-lora`](nd608/gpt2-lora) | Folder containing the exported fine-tuned model weights. |