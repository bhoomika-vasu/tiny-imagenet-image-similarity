# Tiny ImageNet Image Similarity Classification
This project focuses on image similarity classification using the Tiny ImageNet
dataset. The objective is to compare pairs of images and determine whether they
belong to the same class or different classes.
## Project Overview
The project explores two deep learning-based approaches for image similarity
classification:
1. \\\\\\\*\\\\\\\*ResNet18 Similarity Model\\\\\\\*\\\\\\\*

Uses ResNet18 for feature extraction.
Generates image embeddings.
Compares image pairs using similarity-based methods.
Evaluates model performance using classification metrics.
2. \\\\\\\*\\\\\\\*MobileNet Pairwise Similarity Model\\\\\\\*\\\\\\\*

Uses a MobileNet-based pairwise learning approach.
Trains a model to compare two images directly.
Predicts whether the image pair belongs to the same class or different classes.
## Dataset
The project uses the Tiny ImageNet dataset. The dataset is loaded inside the
notebooks using Hugging Face/Datasets utilities.
## Tools and Technologies
- Python
- PyTorch
- Torchvision
- Hugging Face Datasets
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow
- Jupyter Notebook
## Repository Structure
notebooks/
├── tiny\\\\\\\_imagenet\\\\\\\_resnet18\\\\\\\_similarity.ipynb
└── tiny\\\\\\\_imagenet\\\\\\\_mobilenet\\\\\\\_pairwise\\\\\\\_similarity.ipynb
1. ResNet18 Similarity Model
File:

notebooks/tiny\\\\\\\_imagenet\\\\\\\_resnet18\\\\\\\_similarity.ipynb
This notebook uses ResNet18-based feature extraction to generate image embeddings and compare image pairs using similarity methods.

2. MobileNet Pairwise Similarity Model
File:

notebooks/tiny\\\\\\\_imagenet\\\\\\\_mobilenet\\\\\\\_pairwise\\\\\\\_similarity.ipynb
This notebook uses a MobileNet-based pairwise model to classify whether two images belong to the same class or different classes.

How to Run the Project

## `1. Clone the repository:` 

git clone https://github.com/bhoomika-vasu/tiny-imagenet-image-similarity.git

## `2. Move into the project folder:` 

cd tiny-imagenet-image-similarity

## `3. Install the required libraries:` 

pip install -r requirements.txt

## `4. Open Jupyter Notebook:` 

jupyter notebook

## `5. Open and run the notebooks from the `notebooks/` folder.` 

Large datasets, model checkpoints, and temporary output files are not included in this repository.
If a Hugging Face token is required, replace the placeholder token only in your local environment.
The notebooks can be run independently depending on the selected modeling approach.

## `## Project Files` 

- ``tiny\\\\\\\_imagenet\\\\\\\_resnet18\\\\\\\_similarity.ipynb`` 

- ``tiny\\\\\\\_imagenet\\\\\\\_mobilenet\\\\\\\_pairwise\\\\\\\_similarity.ipynb`` 

- ``requirements.txt`` 

- ``.gitignore`` 
