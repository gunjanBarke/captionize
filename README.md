# captionize

Project Overview
Captionize is an AI-powered image captioning system that uses the BLIP (Bootstrapped Language Image Pretraining) transformer model to generate real-time, contextually accurate image captions.
The system supports both the Flickr8k and Flickr30k datasets and includes:
Image enhancement tools
Real-time caption generation
Hashtag extraction
Evaluation using BLEU-4, METEOR, and ROUGE-L
A Gradio-based interactive UI

Features
🔁 Dataset Switch: Choose between Flickr8k and Flickr30k
🎨 Image Enhancements: Contrast, brightness, sharpness, saturation, blur, edge enhancement, cropping
✍️ BLIP Captioning: High-quality captions using Salesforce's blip-image-captioning-large via Hugging Face
📌 Hashtag Generator: Extracts keywords from the caption as hashtags
📊 Evaluation Metrics: BLEU-4, METEOR, and ROUGE-L scores
🖼️ Batch or Single Image Evaluation
💻 Gradio UI: Easy-to-use web interface for uploading, previewing, and captioning images


Requirements
Install dependencies:
pip install transformers
pip install gradio
pip install pillow
pip install nltk
pip install rouge-score
pip install matplotlib

How to Run
Open the notebook: captionize_combined.ipynb in Jupyter or Colab
Run all cells in order
Launch the Gradio UI and start uploading images
Select enhancement options and dataset
Get caption, hashtags, and evaluation scores

