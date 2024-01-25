# Awesome - Most Cited and Impactful Papers on AI Video generation
A curated list of papers on video generation or editing using Generative Models such as Diffusion Models, Generative Adversarial Networks (GANs), etc.

Though the name of the repo is `text-to-video`, all sorts of modalities to video such as `text+image` to video are also included and contributions are welcome.

The papers are grouped based on the main model architecture of the generative model. 

## Why this Awesome list
This awesome list is created to help researchers and practisioners get up to speed with generative models for video generation and editing. Anyone getting started, say a new PhD student, should be able to make the most out of this repo.

## Contributing
If you have any suggestions (missing papers, new papers, key researchers or typos), please feel free to edit and send across a pull request.

## Contents
* [Latent Diffusion Models](#latent-diffusion-models)
* [Generative Adversarial Networks](#generative-adversarial-networks-gans)
* [Autoregressive Models](#autoregressive-models)

### Latent Diffusion Models
| Paper Title | Link | Blog | Who? | 
|---|---|---|---|
| Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets | [pdf](https://static1.squarespace.com/static/6213c340453c3f502425776e/t/655ce779b9d47d342a93c890/1700587395994/stable_video_diffusion.pdf) | [blog](https://stability.ai/news/stable-video-diffusion-open-ai-video-model) | Stability AI
| Emu Video: Factorizing Text-to-Video Generation by Explicit Image Conditioning | [pdf](https://arxiv.org/pdf/2311.10709.pdf) | [blog](https://ai.meta.com/blog/emu-text-to-video-generation-image-editing-research) | Meta AI
| LUMIERE: A Space-Time Diffusion Model for Realistic Video Generation | [pdf](https://arxiv.org/abs/2401.12945) | [blog](https://lumiere-video.github.io/) | Google Research


### Autoregressive Models

### Generative Adversarial Networks (GANs)


Google has just dropped "Lumiere" -- a text-to-video diffusion model designed for synthesizing videos that portray realistic, diverse and coherent motion. It claims to address a pivotal challenge in video synthesis. 

Below are the novelties:
👉a Space-Time U-Net architecture that generates the entire temporal duration of the video at once, through a single pass in the model.
👉By deploying both spatial and (importantly) temporal down- and up-sampling and leveraging a pre-trained text-to-image diffusion model, the Lumiere model learns to directly generate a full-frame-rate, low-resolution video by processing it in multiple space-time scales.


