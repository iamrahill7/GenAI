# GenAI

---

## Image Generation Using Stable Diffusion

This repository provides a tool for generating high-quality images from text descriptions using the Stable Diffusion model.

### Key Features

1. **Model and Performance**: Utilizes the Stable Diffusion model from the `diffusers` library, configured for optimal performance with GPU acceleration.

2. **Customizable Parameters**: The code allows setting parameters such as:
   - **Seed**: Ensures reproducibility of generated images.
   - **Inference Steps**: Controls the number of steps in the image generation process.
   - **Image Size**: Defines the dimensions of the generated images.
   - **Guidance Scale**: Adjusts the strength of adherence to the text prompt.

3. **Image Generation**: The `generate_image` function processes a text prompt with the configured model to produce and resize images according to the specified settings.

---

