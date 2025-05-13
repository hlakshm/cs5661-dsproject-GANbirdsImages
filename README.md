# 📊 GAN Bird Images


## Project Description 

By leveraging advanced image generation techniques such as DCGANs or cGANS, we aim to create synthetic bird images for various applications such as to support wildlife conservation efforts, enrich creative projects, and making species identification more accessible and enhancing the quality of synthetic data.



---

## 📂 Repository Structure
- `data/`: Empty, data will be generated locally when you run the final notebook
- `notebooks/`: Jupyter Notebooks for data validation and analysis
- `src/`: Final models and analysis
- `data_card.md`: Dataset documentation ([Google Data Card](https://github.com/PAIR-code/datacardsplaybook/blob/main/templates/DataCardsExtendedTemplate.md))
- `README.md`: This file

---
## Elevator Pitch

The Problem (Why does this matter?)

Generative Adversarial Networks have emerged as a powerful tool to generate synthetic data, such as images. In this project, we will explore the capabilities of GANs and its extensions to generate realistic and diverse images of birds. Bird imagery has a range of applications, such as wildlife conservation, ecological research, or even just content creation and education.

The Data (What are you working with?)

We will be working with a preprocessed dataset of Caltech-UCSD Birds from 2000-2011. The dataset. The dataset contains high and low dimensional pictures of birds, along with pre-trained text embeddings for training text-to-image synthesis. The dataset is publicly available at https://www.kaggle.com/datasets/vishalkundar/gandata20/dataLinks to an external site..

The Approach (How are you exploring this?)

Our approach involves implementing and tuning DCGANs and cGANs. We will start by training a DCGAN from scratch to generate images, then extend it to a cGAN to control the generated output by using conditional inputs, such as textual descriptions. To ensure the quality of our images, we will use metrics such as Frechet Inception Distance, and Inception score. These metrics will compare the statistical similarity between the real and generated images, as well as measure the diversity and realism in the generated images. This will be implemented using Python and PyTorch/Tensorflow. This approach keeps it simple and practical, ensuring feasibility within our timeline.

The Impact (What is the expected outcome?)

The expected outcome of this project is a model that can generate high quality and diverse synthetic images of birds. By generating synthetic bird images, we can contribute to enhancing datasets for species identification, create realistic visuals for media, etc. A potential challenge is the instability of GAN training and the computational resources required, which may need us to look into a pre-trained model.

## 🚀 Installation Guide

### 🔧 Requirements
- Python 3.7 or higher  
- Pytorch

### 📦 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>


## Usage

## Contributors

We want to thank the following individuals who have contributed to this project:

| Name | GitHub Username |
|---|---|
| Anthony Lee | [anthonylee9](https://github.com/anthonylee9) |
