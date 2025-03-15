# LD-BFR: Vector-Quantization-Based Face Restoration Model with Latent Diffusion Enhancement

Our code is primarily developed based on [latent-diffusion](https://github.com/CompVis/latent-diffusion). If there are any environment configuration issues, you can refer to related issues of LDM.  

A suitable conda environment named ldm can be created and activated with:
```
conda env create -f environment.yaml
conda activate ldm
```

The diffusion model can be found in the `./ldm/models/diffusion/ddpm_2.py`

The VQ-VAE can be found in the `./taming/models/vqgan_v2.py`.  

Their related configs are `ffhq-ldm-cvq-4.yaml`.

## Citation

If you use this code in your research, please cite the following paper:

```
@inproceedings{du2024ld,
title={LD-BFR: Vector-Quantization-Based Face Restoration Model with Latent Diffusion Enhancement},
author={Du, Yuzhen and Hu, Teng and Yi, Ran and Ma, Lizhuang},
booktitle={Proceedings of the 32nd ACM International Conference on Multimedia},
pages={2852--2860},
year={2024}
}
```
