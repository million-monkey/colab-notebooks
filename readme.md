Just a couple of Google Colab notebooks for playing around with image generation models using Colab's free T4 GPU access. If you don't have a decent GPU then you might find these useful or at least fun for a bit. If you have a google/gmail account then you already have access to Google Colab: https://colab.research.google.com/

* These notebooks do not use the full ComfyUI Node Based UI. They use a lightweight headless technique that uses less memory and runs faster.
* The workflows are hard-coded via the Python API. You can examine the source for more details.
* I cobbled these together from various other sources on the githubs. Unfortunately I cannot recall the original authors but any kudos go to them.
* I will not be maintaining these or adding any features.
## comfy-tti-unet [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/million-monkey/colab-notebooks/blob/main/comfy-tti-unet.ipynb)

A hard-coded text to image UNET workflow with preconfigured support for:
* Z-Image-Turbo FP8
* Z-Image-Base FP8
* Anima Preview 2 FP8
* Flux.2 9B Klein FP8 (takes a while to load, crashes after 4-5 images)
* Qwen Image GGUF (very slow and crashes often)

## comfy-tti-checkpoint [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/million-monkey/colab-notebooks/blob/main/comfy-tti-checkpoint.ipynb)

A hard-coded text to image CHECKPOINT workflow with preconfigured support for:
* Illustrious
* Pony
* SDXL
* SD1.5

