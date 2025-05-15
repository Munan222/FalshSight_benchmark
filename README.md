# 🔥 FlashSight Benchmark

This repository provides testing code for **eight state-of-the-art (SOTA)** video prediction and spatiotemporal modeling methods on the **FlashSight** wildfire dataset.

## 📦 Included Models

The following models are supported and evaluated in this benchmark:

- [x] Earthformer  
- [x] PreRNN  
- [x] S2R-FireTr  
- [x] MCVD  
- [x] STDiff  
- [x] VDT  
- [x] DynamicCrafter  
- [x] Simulator  

Each method is implemented and tested on the FlashSight dataset with consistent preprocessing and evaluation settings.

## 🌍 Dataset

The dataset used in this benchmark is the **FlashSight** multi-modal drone-captured wildfire dataset.

- 📥 **Download Dataset**:  
  Available on Hugging Face:  
  👉 [FlashSight on Hugging Face](https://huggingface.co/datasets/Nancy111/FlashSight/tree/main)

The dataset includes:
- Infrared & RGB video (.mp4)
- Frame-wise image sequences (.jpg)
- Auto-labeled & manually annotated segmentation masks
- Environmental meteorological data (.csv)
- Land use maps (.png)

## 📁 Structure

Each model has its own folder containing:
- Preprocessing scripts  
- Training/testing routines  
- Evaluation metrics

## 🛠️ Setup & Usage

To run experiments, navigate to the corresponding model directory and follow its specific instructions in the `README.md` or script comments.

## 📌 Note

This benchmark aims to provide a unified evaluation setting for fair comparison of predictive models on drone-captured wildfire sequences.

---

Feel free to open issues or submit pull requests for improvements or additional models!
