# Student Assessment: Denoising Probabilistic Diffusion Models

**Course:** Applied Hands-on Computer Vision @HPI

## Overview

This repository contains the submission for **Assignment 3: Diffusion Models**.
The objective of this assignment is to generate images using a diffusion-based generative model, evaluate the quality of the generated images using standard metrics, and analyze internal model representations using modern visualization and experiment tracking tools.

The experiments focus on generating flower images from text prompts and analyzing the generated outputs both qualitatively and quantitatively across different guidance scales.

## Objectives

* **Generate images** from text prompts using a diffusion model conditioned on CLIP embeddings.
* **Extract intermediate embeddings** from the U-Net architecture (`down2` layer) during image generation.
* **Evaluate generated images** using **CLIP Score** (text-image alignment) and **Fréchet Inception Distance (FID)** (image quality/diversity).
* **Analyze generated images** using **FiftyOne** and **FiftyOne Brain** (computing Uniqueness and Representativeness scores).
* **Log experiments, metrics, and visualizations** using **Weights & Biases (wandb)**.

##WandB ID

https://wandb.ai/rishikeshbharti007-university-of-potsdam/diffusion_model_assessment_v2

## Author

**Rishikesh Bharti**
**Student ID:** 828464
