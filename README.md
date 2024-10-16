## Mobile-UIDesign-Generator
Mobile UI Design Generator is an application that generates mobile user interface (UI) designs based on textual descriptions. Leveraging the Stable Diffusion model, it transforms user-provided prompts into high-quality images, making it an essential tool for developers and designers.

## Features
- Generate unique mobile UI designs from text prompts.
- User-friendly interface powered by **Gradio**.
- Utilizes the **Stable Diffusion** model for image generation.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mobile-ui-design-generator.git
   cd mobile-ui-design-generator

2. Install the necessary libraries
   pip install torch torchvision transformers diffusers gradio accelerate

## Usage
1. Run the application
   python app.py
2. Enter a description of the mobile UI design you want to generate and click "Submit." The generated image will be displayed.

## Dataset
The dataset used for training and generating mobile UI designs is available at Hugging Face Datasets.

## Evaluation
The performance of the application is evaluated based on:

Design Accuracy: The relevance of generated designs to the input descriptions.
Visual Quality: The aesthetic quality of the generated images.

## Acknowledgments
Stable Diffusion: for providing the model used for image generation.
Gradio: for the user-friendly interface

