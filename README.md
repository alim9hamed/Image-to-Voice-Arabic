# Image to Voice Arabic Pipeline

The **Image to Voice Arabic Pipeline** project aims to convert images into Arabic speech in three steps. Using advanced machine learning models, the pipeline first generates captions for images, translates these captions into Arabic, and finally converts the text into speech.

## Project Overview

This pipeline consists of three main stages:

1. **Image Captioning**: Generates detailed captions from images using Microsoft's [Phi-3.5 Vision](https://huggingface.co/microsoft/Phi-3.5-vision-instruct) model, which excels at providing detailed and accurate descriptions.
  
2. **Arabic Translation**: Translates the captions into formal Arabic using the [Llama-3](https://huggingface.co/Groq/Llama-3-Groq-8B-Tool-Use) model, providing accurate translations in a formal register.
  
3. **Text-to-Speech (TTS)**: Synthesizes the Arabic text into high-quality, natural-sounding Arabic speech with the [XTTS-v2](https://huggingface.co/coqui/XTTS-v2) model.

This pipeline ensures a smooth, end-to-end transformation from image to Arabic speech, making it accessible for Arabic-speaking users who can understand and enjoy the visual content without needing written text.



## Running the Pipeline

### 1. Image Captioning

The image captioning step is powered by the Phi 3.5 Vision model by Microsoft. Use this to generate an English description of the provided image.

### 2. Arabic Translation

The Llama-3 Groq model is used here to translate the generated captions into formal Arabic.

### 3. Text-to-Speech (TTS)

Arabic-TTS synthesizes the Arabic captions into speech with high clarity.

## Using the Gradio Interface

This project includes an inference script using Gradio, which provides an interactive interface for uploading images and receiving Arabic speech output.

## How to Use

1. Run the code above in your Python environment.
2. Open the Gradio link generated in your terminal.
3. Upload an image to the interface, and the model will output an Arabic audio description.

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Yr3bmW8vzYLbxAwT67OgM7jhG6cx1KvN?usp=sharing)
## Models Used

- **Image Captioning**: [Phi 3.5 Vision](https://huggingface.co/microsoft/Phi-3.5-vision-instruct) – Generates high-quality captions for images.
- **Arabic Translation**: [Llama-3 Groq](https://huggingface.co/Groq/Llama-3-Groq-8B-Tool-Use) – Translates captions into formal Arabic.
- **Text-to-Speech**: [Arabic-TTS](https://huggingface.co/coqui/XTTS-v2) – Converts Arabic text into speech.

## Future Work

- Expand language support beyond Arabic.
- Enhance real-time processing capabilities.
- Improve captioning accuracy for more complex images.

## Need Help?

If you have any questions or need assistance, please don't hesitate to reach out to me anytime!
