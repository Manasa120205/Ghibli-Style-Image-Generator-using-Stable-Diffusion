# Ghibli-Style-Image-Generator-using-Stable-Diffusion
Transform any image into a beautiful Ghibli-style anime portrait using Stable Diffusion's image-to-image generation. This project leverages the Ghibli-Diffusion model with GPU acceleration for faster inference and allows easy uploads, real-time customization, and instant download of AI-generated artwork directly in Google Colab.


# Ghibli Style Image Generator using Stable Diffusion

Transform your photos into stunning Ghibli-style anime art using the power of AI! This Google Colab project uses the StableDiffusionImg2ImgPipeline from Hugging Face's Diffusers library, specifically the nitrosocke/Ghibli-Diffusion model, to generate soft, pastel-toned anime portraits.

## Features

- Upload any image and convert it to Ghibli-style art
- Adjustable stylization strength (0.3 to 0.8)
- GPU-accelerated processing (if available)
- Instant download of the generated image
- Visual preview of original and generated images

## Setup Instructions

1. Run the notebook in Google Colab
2. Upload your desired image when prompted
3. Enter the stylization strength (recommended: 0.6)
4. View and download the Ghibli-style image

## Libraries Used

- diffusers
- torch
- PIL
- matplotlib
- google.colab

## Model Used

- *Model*: [nitrosocke/Ghibli-Diffusion](https://huggingface.co/nitrosocke/Ghibli-Diffusion)
- *Type*: Image-to-Image Stable Diffusion
- *Framework*: PyTorch + Hugging Face Diffusers


## License

This project is for educational and personal use only. All model rights belong to their respective authors.
