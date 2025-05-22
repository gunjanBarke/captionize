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


How to Run
Clone this project or open captionize_combined.ipynb in Jupyter or Google Colab.
Install dependencies using: pip install -r requirements.txt
Run all cells in the notebook.
Use the Gradio interface to:
Upload an image or choose a dataset (Flickr8k/Flickr30k)
Apply enhancements (contrast, brightness, sharpness, etc.)
Generate captions and hashtags
Evaluate captions using BLEU, METEOR, and ROUGE-L

