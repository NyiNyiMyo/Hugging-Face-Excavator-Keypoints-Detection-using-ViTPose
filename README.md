# Hugging Face Excavator Keypoints Detection using ViTPose

[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
[![Hugging Face](https://img.shields.io/badge/-Hugging_Face-3B4252?style=flat&logo=huggingface&logoColor=)](https://huggingface.co/)
![Static Badge](https://img.shields.io/badge/Keypoints-Detection-cyan)
![Static Badge](https://img.shields.io/badge/ViTPose-8A2BE2)

This repository contains keypoints detection project focused on **Robotic like Machine, Excavator** with **6 keypoints** using **ViTPose**.

---

## 🧭 Dataset Overview

Total train images: 642 / Total val images: 54

✅ keypoint_names = [ 'bucket', 'hinge1', 'hinge2', 'driver_seat', 'rear', 'b_hinge' ]  
✅ skeleton = [ (1,6), (2,3), (3,4), (4,5), (6,2) ] 

---

## 🏗️ Model Architecture

- 🦾 Model: **ViTPose**
- 🦾 Type: **Top-down**
- 🦾 Weight: **"vitpose-base"**
- 🦾 Framework: **PyTorch + Hugging Face**
- 🦾 Input Size: **256, 192**
- 🦾 Trained Epochs: **20**

---
