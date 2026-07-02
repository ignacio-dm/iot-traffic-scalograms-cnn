IoT Traffic Scalograms & Spectrograms Dataset

Hello!

My name is Ignacio, and I am a PhD student working on research related to the application of Artificial Intelligence to cybersecurity, specifically the analysis of IoT network traffic.

I created this repository to share the image datasets used during my research so that other students, researchers, and anyone interested in this field can use them as a reference or as a starting point for their own experiments.

The original network traffic used to generate these images comes from the CICIoT2023 Dataset, developed by the Canadian Institute for Cybersecurity (CIC). All credit for the original traffic data belongs to its authors. This repository only contains image representations generated from that dataset.

Repository Structure

Each folder contains a different type of data generated from the original network traffic.

Benign_Final

Contains CSV files representing normal (non-malicious) IoT network traffic.

DoS-HTTP_Flood

Contains CSV files corresponding to HTTP Denial-of-Service (DoS) attacks.

DoS-TCP_Flood

Contains CSV files corresponding to TCP flooding attacks.

DoS-UDP_Flood

Contains CSV files corresponding to UDP flooding attacks.

DoS-SYN_Flood

Contains CSV files corresponding to TCP SYN flooding attacks.

*_spectrograms

These folders contain spectrogram images generated from the corresponding CSV files. Spectrograms provide a visual representation of the network traffic in the time-frequency domain using the Short-Time Fourier Transform (STFT).

*_scalograms

These folders contain scalogram images generated from the same traffic using the Continuous Wavelet Transform (CWT). Scalograms provide an alternative time-frequency representation that captures transient patterns in network traffic.

Purpose

The goal of publishing this repository is to make it easier for other researchers to reproduce experiments, compare different machine learning models, and explore new approaches for IoT traffic classification.

At this stage, only the generated datasets are published. The source code used to generate these images and train the models will be made publicly available after the associated scientific article has completed the publication process.

If you find this repository useful for your own research, I would be happy if you cited both the original CICIoT2023 dataset and the corresponding scientific publication once it becomes available.

Thank you for your interest, and I hope this repository is helpful for your research.

Best regards,

Ignacio
PhD Student
