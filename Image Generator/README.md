# Image Generator 

### Stable Diffusion 
A latent text-to-image diffusion model, by Stability AI supported from LAION. The model is a Latent Diffusion Model on 512x512 images from a subset of the LAION-5B database. With its 860M UNet and 123M text encoder, the model is relatively lightweight and runs on a GPU with at least 10GB VRAM.

Example: 
python scripts/txt2img.py --prompt "Year of Rabbit by Claude Monet, oil on canvas" --plms --ckpt sd-v1-4.ckpt --skip_grid --n_samples 1 --H 384 --W 384 --seed 119

![00005](https://user-images.githubusercontent.com/5380211/216806223-9888dd9d-c539-460c-bd10-2cba289537ed.png)
