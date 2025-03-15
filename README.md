# LD-BFR

Our code is primarily developed based on [latent-diffusion](https://github.com/CompVis/latent-diffusion). If there are any environment configuration issues, you can refer to related issues of LDM.  
The code has not been systematically organized yet and is quite messy, so it is for reference only. You can refer to the training and reference code of LDM and VQGAN to train our LD-BFR.  
Or you can wait for the next code update.  
The diffusion model can be found in the `./ldm/models/diffusion/ddpm_2.py` and the VQ-VAE can be found in the `./taming/models/vqgan_v2.py`.  
Their related configs are `ffhq-ldm-cvq-4.yaml`.
