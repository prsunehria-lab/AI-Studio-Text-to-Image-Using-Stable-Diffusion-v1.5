# AI-Studio-Text-to-Image-Using-Stable-Diffusion-v1.5
A lightweight, fully offline Stable Diffusion v1.5 Web UI optimized for low-VRAM NVIDIA GPUs. Built with Python, Flask, Diffusers, and Tailwind CSS. Features Txt2Img, Img2Img, interactive Inpainting Canvas, ControlNet (OpenPose &amp; Recolor), and an automated MTCNN face-refining pipeline.

# AI Studio Generator (Vision X Engine)

An ultra-optimized, local AI image generation studio powered by NVIDIA CUDA, Python, and Flask. This project provides a streamlined, single-file web interface designed to run advanced diffusion workflows entirely offline, with aggressive VRAM management tailored for mid-range hardware <=6GB VRAM (like the NVIDIA RTX 4050 (Recommended)).

## ✨ Key Features

*   **Multi-Mode Rendering Engine:** Seamlessly switch between Text-to-Image (Txt2Img), Image-to-Image (Img2Img), and ControlNet architectures.
*   **Interactive Inpainting Canvas:** A custom HTML5 drawing viewport that maps binary alpha masks directly into the Diffusers pipeline for seamless object insertion and localized generation fixes.
*   **Dual ControlNet Pipelines:** Integrated support for **OpenPose** skeleton extraction and **ioclab Recolor** for advanced colorization mechanics.
*   **Automated Face Refiner (ADetailer Alternative):** Uses a local `MTCNN` face scanner to dynamically detect, crop, upsample, and re-blend facial features during the final generation stage to completely eradicate anatomical artifacts.
*   **100% Air-Gapped / Offline Native:** Local model caching logic (`local_files_only=True`) and hard-saved client scripts ensure the studio remains completely operational without an internet connection.
*   **VRAM Protection Layer:** Integrated UNet channel optimization, sliced/tiled VAE decoding, and shared pipeline memory configurations to eliminate Out-Of-Memory (OOM) errors.

##Warning 
Python Version 3.12 (Recommended)

I am Not responsible for What content you Generate or Modify. But i give you full Access and Permission to Do what ever you want and modify this project
