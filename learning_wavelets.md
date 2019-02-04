---
title: Learning Wavelets
theme: blotter.css
revealOptions:
    transition: 'fade'
    incremental: false
---

# Learning Wavelets

### Austen Lamacraft, Cavendish Lab


# Learning Representations

### Word Vectors

<p align="center">
<img src="assets/wordvec.png" alt="tensors" width="600"/>
</p>

---

### Autoencoder

<p align="center">
<img src="assets/autoencoder.png" alt="tensors" width="600"/>
</p>

<p align="center">
Latent space ($z$-variables) encodes inputs
</p>


# Challenge of Audio

<p align="center">
<img src="assets/dilate.gif" alt="tensors" width="600"/>
</p>


<p align="center">
Audio CD sampling rate 44.1 kHz
</p>

# Multiscale Methods

### Example: Fast Fourier Transform

<p align="center">
<img src="assets/DIT-FFT-butterfly.png" alt="tensors" width="600"/>
</p>

---

### Dilated Convolutions in DeepMind's WaveNet

<p align="center">
<img src="assets/wavenet.gif" alt="tensors" width="600"/>
</p>

# Wavelets

<p align="center">
<img src="assets/Wavelets_DWT.png" alt="tensors" width="600"/>
</p>
<p align="center">
<img src="assets/Wavelets_Filter_Bank.png" alt="tensors" width="600"/>
</p>
<p align="center">
<img src="assets/Wavelets_DWT_freq.png" alt="tensors" width="600"/>
</p>

---

<p align="center">
<img src="assets/Daubechies4-functions.png" alt="tensors" width="600"/>
</p>

---

<p align="center">
<img src="assets/Daubechies4-spectrum.png" alt="tensors" width="600"/>
</p>

---

# A Different Approach?

<p align="center">
<img src="assets/learn.jpeg" alt="tensors" width="600"/>
</p>

# Some Recent Work

<p align="center">
<img src="assets/recon.png" alt="tensors" width="600"/>
</p>

<p align="center">
Recoskie & Mann arXiv:1802.02961 [no exact reconstruction]
</p>


# Project structure

- A simple dataset e.g. [Google's NSynth](https://magenta.tensorflow.org/datasets/nsynth)
- A deep learning framework (TensorFlow, PyTorch)
- An objective function (sparseness, perceptual similarity)
- Use of GPU cluster
