# IoT Traffic Scalograms & Spectrograms Dataset

Welcome!

My name is **Ignacio**, and I am a **PhD student** researching the application of Artificial Intelligence (AI) for cybersecurity, with a particular focus on the analysis of IoT network traffic.

This repository has been created to share the image datasets used during my doctoral research. My hope is that these resources will be useful to students, researchers, and anyone interested in experimenting with machine learning techniques for cybersecurity.

---

# About the Dataset

The original network traffic used to generate these images comes from the **CICIoT2023 Dataset**, developed by the **Canadian Institute for Cybersecurity (CIC)**.

All credit for the original network traffic belongs to the authors of the CICIoT2023 dataset. This repository contains **image representations generated from that traffic**, rather than the original packet captures.

---

# Repository Structure

## Benign_Final

CSV flow files representing normal (non-malicious) IoT network traffic.

## DoS-HTTP_Flood

CSV flow files corresponding to HTTP Denial-of-Service (DoS) attacks.

## DoS-TCP_Flood

CSV flow files corresponding to TCP Flood attacks.

## DoS-UDP_Flood

CSV flow files corresponding to UDP Flood attacks.

## DoS-SYN_Flood

CSV flow files corresponding to TCP SYN Flood attacks.

## *_spectrograms

These folders contain spectrogram images generated from the corresponding CSV files using the **Short-Time Fourier Transform (STFT)**.

Spectrograms provide a visual representation of the frequency content of network traffic over time.

## *_scalograms

These folders contain scalogram images generated from the same CSV files using the **Continuous Wavelet Transform (CWT)**.

Scalograms provide an alternative time-frequency representation that highlights transient events and short-lived traffic patterns.

---

# Purpose

This repository is intended to serve as a reference dataset for reproducible research.

Researchers are welcome to use these images to compare machine learning models, evaluate new approaches, or reproduce experiments related to IoT traffic classification.

At the current stage of my research, only the generated datasets are publicly available. The Python source code used to generate the images and train the neural network models will be released after the associated scientific article has completed the peer-review and publication process.

---

# Citation

If you use this repository in your research, please consider citing:

- The original **CICIoT2023 Dataset**.
- The associated scientific publication (link will be added after publication).

---

# Repository Status

🚧 **Work in Progress**

This repository is actively maintained as part of my PhD research. Additional datasets, documentation, and source code will be published as the research progresses.

---

# Contact

Thank you for visiting this repository.

I sincerely hope these datasets are useful for your own research and contribute to future advances in AI-based cybersecurity.

**Ignacio**

*PhD Student*
