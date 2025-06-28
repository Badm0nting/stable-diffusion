# 🧠 Stable Diffusion with KerasCV (Internship Project)

This Google Colab notebook demonstrates the generation of images from natural language prompts using **Stable Diffusion**, implemented through the `keras_cv` library. This task was completed as part of my internship, where I explored various Generative AI (GenAI) pipelines.

## 🔗 Open the Notebook

[View in Google Colab](https://colab.research.google.com/drive/1aij9JfccZU9G9y1QrljRJ1_S3J07lHa9#scrollTo=kbRwbwqSctxf)

## 🎯 Objective

This was one of five GenAI-focused tasks assigned during my internship. The goal was to:

- Work with pre-trained generative models (like Stable Diffusion)
- Understand the text-to-image pipeline
- Run and adapt the model in a cloud notebook environment (Google Colab)
- Customize prompts and visualize image outputs

## 🚀 Features

- Uses KerasCV’s Stable Diffusion model
- Generates high-resolution (512x512) images from text
- Allows prompt and batch size customization
- Built-in image visualization with `matplotlib`

## 🔧 Technologies Used

- Python 3
- TensorFlow / Keras
- KerasCV
- Google Colab
- Matplotlib

## 🧪 How to Use

1. Open the [notebook in Colab](https://colab.research.google.com/drive/1aij9JfccZU9G9y1QrljRJ1_S3J07lHa9#scrollTo=kbRwbwqSctxf).
2. Run all code cells in order:
   - Install dependencies
   - Load the Stable Diffusion model
   - Enter your custom prompt
   - Generate and visualize images
3. Modify `prompt` or `batch_size` to experiment.

### ✏️ Example Usage

```python
prompt = "A futuristic skyline during sunset"
images = model.text_to_image(prompt, batch_size=2)

## 🖼 Sample Output
The model generates realistic or artistic images based on the prompt. Results vary slightly with each run, even using the same prompt.

## 💼 Internship Context
Role: Intern
Domain: Generative AI
Project: Stable Diffusion with KerasCV
Task: Image generation from natural language prompts using pretrained models

## 🙌 Acknowledgements
KerasCV

Google Colab

TensorFlow & Keras Teams

## 📄 License
This project is for academic and educational purposes. All models and libraries are the property of their respective maintainers under open-source licenses.
