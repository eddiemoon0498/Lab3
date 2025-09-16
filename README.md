# My Project Plan

> **Note**: This document is written merely as an illustrative example, and does not provide any working guide to an actual project.

### Proposal

I am planning to make a computer vision software that detects objects in images.

In order to build it, I will use OpenCV, deep learning libraries such as TensorFlow or PyTorch, and other open-source softwares.

For example, the objects in the following images were detected using MMDetection:

<p align="center">
  <img src="assets/example1.jpg" alt="Detection example 1" width="520">
  <br />
  <em>Figure 1. Sample detection results.</em>
</p>

### Dependencies

- python  
- opencv-python  
- tensorflow  
- openmmlab  
- package manager

### Installation

> In a bash terminal, run the following commands (**Do NOT actually run these commands on your computer**):

```bash
sudo apt update
conda create -n cv_detection
conda activate cv_detection
python --version
python example.py
