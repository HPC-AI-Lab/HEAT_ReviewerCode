## Environment

- Python: 3.10
- PyTorch: 2.5.1
- CUDA: 12.4
- GPU: NVIDIA (tested)

## Installation

pip install -r requirements.txt

# Install PyTorch with CUDA
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu124

# DATASET AVAILABILITY
Download the dataset from the below google drive link and extract it.
The folder structure is such that - 3 files for each phase of training.
Each phase has a sapling image folder, one hypocotyl mask folder and one distance measure folder.

[Google drive link](https://drive.google.com/file/d/1rcCAJLOU1kHRhPNkRlXK-6rKgVTlAJ13/view?usp=sharing)

# Trained weight
The trained weight of the model is also uploaded to google drive. Download it and put it in the InferencePipeline folder.

[Google drive link](https://drive.google.com/file/d/1IV57arzrbF82g2PBCYM2TlpuhcG4DCOv/view?usp=sharing)