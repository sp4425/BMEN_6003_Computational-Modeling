# AI in Medicine Notebooks — Ear (Ideal Binary Mask) & Eye (Module 3, 2025)

This repo contains two Jupyter notebooks from an AI-in-medicine coursework set. Each notebook is self-contained and can be run in Jupyter or Google Colab.

## Contents

### `IdealBinaryMaskFinal.ipynb` — Ear / Audio (Ideal Binary Mask)
A signal-processing notebook that demonstrates speech/audio enhancement using an **Ideal Binary Mask (IBM)**.  
**What it does**
- Loads/creates clean + noisy audio examples.
- Computes a time–frequency representation (e.g., STFT), builds an IBM to keep high-SNR bins, and reconstructs the enhanced waveform.
- Compares noisy vs. enhanced signals with basic quality metrics and plots (waveforms/spectrograms).

**Why it’s useful**
- Shows how a simple mask in the TF domain can significantly improve intelligibility in noisy conditions—foundational for hearing-assist and robust ASR scenarios.

---

### `Module3_Eye_2025.ipynb` — Eye / Computer Vision (DL pipeline)
A computer-vision notebook that walks through a **baseline deep learning pipeline** for eye-image analysis (e.g., classification).  
**What it does**
- Loads and preprocesses images (PIL/OpenCV), applies common augmentations.
- Uses a pretrained CNN (PyTorch/timm/torchvision) and fine-tunes on the provided dataset.
- Evaluates with standard metrics (accuracy, loss curves; optionally confusion matrix) and saves example predictions.

**Why it’s useful**
- Provides a concise template for medical-imaging tasks: clean data loading, transfer learning, training loop, and basic evaluation.

---
