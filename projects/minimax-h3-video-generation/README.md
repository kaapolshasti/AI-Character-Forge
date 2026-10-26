# MiniMax H3 — Local AI Video Generation

An experimental local AI video-generation project using MiniMax H3, ComfyUI, and Apple Silicon.

This project explores cinematic image-to-video generation on a MacBook Pro with an M4 Max GPU, without relying on a paid cloud-generation API.

## Project Overview

The goal is to generate short cinematic video sequences locally and explore how they can be used in AI-assisted storytelling, character development, and independent animation production.

## Technology Stack

- **Model:** MiniMax H3
- **Interface:** ComfyUI
- **Hardware:** Apple MacBook Pro with M4 Max
- **Video generation:** Local image-to-video workflow
- **Model format:** INT8 diffusion model with quantised text encoder
- **Post-production:** DaVinci Resolve

## Initial Results

Successfully executed a five-second video-generation workflow locally.

| Parameter | Result |
|---|---|
| Video duration | 5 seconds |
| Aspect ratio | 9:16, vertical |
| Megapixel setting | 0.4 MP |
| Resolution alignment | Multiple of 32 |
| Sampling steps | 20 |
| Sampling time | Approximately 33 minutes 56 seconds |
| Total workflow execution time | Approximately 39 minutes 43 seconds |

Execution times are from one test and are not general performance benchmarks.

## Model Components

The local setup includes the following model components:

- MiniMax H3 INT8 diffusion model
- Qwen3-VL 32B quantised text encoder
- MiniMax H3 INT8 video VAE
- MiniMax H3 audio VAE

Model weights are stored locally and are not included in this repository.

## What I Am Exploring

- Cinematic image-to-video generation
- Vertical video production
- Camera movement and scene composition
- Local generative AI on Apple Silicon
- AI-assisted storytelling and animation
- Integration of generated clips into a larger video-production workflow

## Reproducibility

This repository documents the workflow, settings, experiments, and results.

Actual performance and compatibility may vary with model versions, ComfyUI versions, custom nodes, and the quantisation backend.

To reproduce the workflow, obtain the required models from their official sources and follow their applicable licences.

## Official Resources

- [MiniMax H3 on Hugging Face](https://huggingface.co/Comfy-Org/MiniMax-H3)
- [ComfyUI](https://github.com/Comfy-Org/ComfyUI)
- [ComfyUI Documentation](https://docs.comfy.org/)

## Author

Developed as part of my ongoing exploration of local generative AI, character creation, and AI-assisted cinematic storytelling.
