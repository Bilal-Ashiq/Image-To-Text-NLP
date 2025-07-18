🖼️ Image Captioning using ViT-GPT2

This project uses a pretrained transformer model to automatically generate captions for images. It combines the Vision Transformer (ViT) as the encoder and GPT2 as the decoder using Hugging Face’s `nlpconnect/vit-gpt2-image-captioning` model.

📌 Project Overview

* Generates human-readable captions for uploaded images.
* Utilizes a pretrained deep learning model from Hugging Face.
* Implemented in Python using the Transformers and Torch libraries.
* Designed to be run easily on **Google Colab**.

🛠️ How to Use

1. Open the project notebook in Google Colab.
2. Install the required libraries (transformers, torch, pillow).
3. Upload your image to the Colab environment.
4. Run the final prediction cell by providing the image path (e.g., `/content/image.jpg`).
5. The model will return a descriptive caption for the image.

✅ Example Output

If you upload an image of a dog sitting in a park, the model might return:

"a dog is sitting on the grass in a park"

🧠 Model Details

* Model Used: `nlpconnect/vit-gpt2-image-captioning`
* Framework: Hugging Face Transformers
* Components: ViT encoder + GPT2 decoder

This model is trained to understand the contents of an image and convert that understanding into a relevant textual description.

📦 Requirements

* Python 3.7+
* Google Colab (recommended)
* Libraries: transformers, torch, pillow

💡 Use Case

This project is ideal for:

* Automating image captioning
* Learning how vision and language models work together
* Exploring transformer-based multimodal models

🔗 Credits

* Pretrained model from [Hugging Face](https://huggingface.co/)
* Model card: [`nlpconnect/vit-gpt2-image-captioning`](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning)
