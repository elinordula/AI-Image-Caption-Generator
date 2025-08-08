# AI-Image-Caption-Generator

Description
This project is an AI-powered image captioning app that automatically generates a natural language description of any image you upload. It uses the pre-trained BLIP (Bootstrapping Language-Image Pretraining) model from Hugging Face, which combines vision and language understanding to generate accurate and context-aware captions.

The app is built and deployed using Google Colab and includes a simple and interactive Gradio UI for testing and sharing.

Features
Upload any image and receive a descriptive caption.

Uses Salesforce's BLIP model from Hugging Face Transformers.

Built in Google Colab (no local installation needed).

Interactive interface using Gradio.

Option to share the app via a public link.

Tech Stack
Model: BLIP (Salesforce/blip-image-captioning-base)

Framework: PyTorch, Hugging Face Transformers

UI: Gradio

Platform: Google Colab

How to Use
Open the Colab notebook.

Upload an image (JPG, PNG, etc.).

The model generates and displays a caption.

Optionally, use share=True to generate a public link for others to try it.

Example Output
Input:
Image of a man on the beach watching the sunset

Output:

“A man standing on a beach watching the sunset.”
