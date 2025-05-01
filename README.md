# FouRA

## 🔎 FouRA: Fourier-Based Adapter for Efficient Fine-Tuning of ViTs
In this notebook, we implement and explore FouRA, a plug-and-play adapter that efficiently fine-tunes Vision Transformers (ViTs) using low-rank projections and frequency transforms.

## Why FouRA?
✅ Efficient fine-tuning of ViTs
✅ Works in the frequency domain (DFT/DCT)
✅ Modular and easy to inject into pretrained models
✅ Achieves great performance with minimal additional parameters

We'll apply FouRA to a pretrained ViT-B/16 model and fine-tune it on the CIFAR-100 dataset.
