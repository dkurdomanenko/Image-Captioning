# Image Captioning Experiments

This repository contains a collection of Jupyter notebooks for experimenting with different deep learning models for image captioning. The project is structured into main comparison experiments and other variations.

## Main Experiments: Core Model Comparisons

These four notebooks represent the core of the project, performing end-to-end fine-tuning to compare every combination of the selected vision encoders (**SWIN-V2**, **ViT**) and language decoders (**BERT**, **GPT-2**).

* `Image Captioning Fine-Tune SWIN-V2 BERT.ipynb`: Fine-tuning **SWIN-V2** with **BERT**.
* `Image Captioning Fine-Tune SWIN-V2 GPT-2.ipynb`: Fine-tuning **SWIN-V2** with **GPT-2**.
* `Image Captioning Fine-Tune ViT BERT.ipynb`: Fine-tuning **Vision Transformer (ViT)** with **BERT**.
* `Image Captioning Fine-Tune ViT GPT-2.ipynb`: Fine-tuning **Vision Transformer (ViT)** with **GPT-2**.

## Supplementary Experiments & Variations

These notebooks explore alternative training strategies and model variations based on the SWIN-V2 + BERT architecture.

* `Image Captioning Fine-Tune BERT Freeze-SWIN-V2.ipynb`: Fine-tuning the decoder only, with a frozen SWIN-V2 encoder.
* `Image Captioning Fine-Tune BERT-large Freeze-SWIN-V2.ipynb`: A variation using the larger `BERT-large` model as the decoder.
* `Image Captioning SWIN-V2 BERT OotB.ipynb`: Tests the model combination out-of-the-box (OotB) without any fine-tuning.