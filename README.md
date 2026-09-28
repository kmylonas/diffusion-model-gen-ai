# Generative AI Diffusion Homework

This repository contains homework completed for a Generative AI class. It implements denoising diffusion probabilistic models (DDPMs) for 2D point distributions and image generation.

## Contents

- `task1-2d-diffusion/`: a small DDPM for learning 2D distributions, with a Jupyter notebook.
- `task2-image-diffusion/`: a U-Net DDPM trained on the AFHQ image dataset, plus sampling and FID evaluation utilities.

## Setup

Python 3.10 and a CUDA-capable environment are recommended for image training.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Run Task 1 with `jupyter lab task1-2d-diffusion/ddpm_tutorial.ipynb`. Run Task 2 from its directory with `python train.py`; the AFHQ dataset is downloaded when needed.

The included FID checkpoint is about 83 MB, so Git LFS is recommended when publishing the repository.
