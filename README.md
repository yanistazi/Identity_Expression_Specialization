# Code accompanying: *Emergence of Interpretable Functional Specialization in Neural Networks Trained on Facial Expression and Identity Recognition*

[Paper Link](https://icml-compbio.github.io/2023/papers/WCBICML2023_paper40.pdf)
 
## 📂 I. Repository Structure

This directory contains the notebooks and the figures to reproduce the results of the study.

```
The repository is structured the following way:

├Analysis_Reproduction                        <- The 2 notebooks to reproduce the results
│   ├── Main_figures_Reproducibility.ipynb    <- Main results notebook
│   ├── Supplementary_Figures.ipynb           <- Supplementary results notebook
│
├Results                                      <- Helper files to reproduce the results
│   ├── .pickle helper files                  <- .pickle to reproduce the results
│   ├── .pdf helper files                     <- .pdf to reproduce the results
│
└── README.md

```
## 🚀 II. Getting started with this repository

### ✏️ The code was written in Python 3.7.

### 1. Fork or clone this repository.

### 2. 🔨 Create a dedicated environment as follow with the needed dependencies.

**STEP 1:`conda create --name YOUR_ENV_NAME python=3.8 -y`**

**STEP 2:`conda activate YOUR_ENV_NAME`**

## 💻 III. Tutorial:

### 1. Analysis Reproduction
To reproduce the analysis results, simply run the 2 notebooks: **`Main_figures_Reproducibility.ipynb`** and **`Supplementary_Figures.ipynb`**

## 📗 IV. Conclusion:
Our research has shed light on the capacity of a single convolutional neural network, trained simultaneously on both facial expression and identity recognition, to exhibit functional specialization, thereby segregating distinct features specific to each task.

The interpretability methods provided meaningful insight into the decision-making process of the model. CAM and preferred stimulus visualization showed that the joint model focuses on different facial attributes for each task, and that task specific features only emerge in the deeper layers. These methods could be widely applicable to other studies aiming to understand the internal mechanisms of biological visual systems. Our study also identified task-specific facial biomarkers that could assist in training individuals with facial recognition impairments. Notably, by examining the images that maximally activate each unit in the model, we can potentially identify and tune disrupted neurons in the visual system to respond better to task-optimized images.
## 💾 V. Data availability
The raw data is not included but was obtained from open databases: [KDEF](https://kdef.se/), [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/), and [FER2013](https://www.kaggle.com/datasets/msambare/fer2013).
## 📌 VI. Citations:
Any use of the code or the data should cite both the associated [paper](https://icml-compbio.github.io/2023/papers/WCBICML2023_paper40.pdf) and this github repository DOI.
