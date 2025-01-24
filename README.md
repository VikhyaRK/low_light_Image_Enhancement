# low_light_Image_Enhancement

# Overview
GUI Design with CustomTkinter

Created an interactive interface using CustomTkinter with a user-friendly layout.
Added input fields for user prompts and a dedicated area to display generated images.
Integration of the Stable Diffusion Model

Configured and loaded the pre-trained Stable Diffusion model from Hugging Face using the Diffusers library.
Implemented multi-device compatibility (GPU and CPU) with automatic detection for optimized performance.
Optimized Model Execution

Enabled floating-point precision handling (fp16 for GPU and fp32 for CPU) for efficient memory usage.
Incorporated PyTorch's torch.no_grad() to ensure computation efficiency during inference.
Image Generation Pipeline

Processed user prompts to generate high-quality 512x512 images in under 10 seconds on GPU.
Implemented image saving and dynamic rendering in the GUI using PIL's ImageTk module.
Button and Event Handling

Added a "Generate" button linked to the image generation function, allowing users to trigger image creation seamlessly.
Error Handling and Feedback

Integrated exception handling for robust performance and clear feedback in case of model or input errors.
