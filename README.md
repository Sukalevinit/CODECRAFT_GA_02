# Task 02 – Image Generation with Pre- trained Models

## 📄 Project Description

This notebook demonstrates the use of Hugging Face's `diffusers` library to generate images using the **Stable Diffusion** model. The task involves installing required libraries, logging into the Hugging Face hub, loading a pre-trained model, and generating AI images based on text prompts.

---

## 📦 Technologies and Libraries Used

* Python (Jupyter Notebook)
* Hugging Face `diffusers` library
* Transformers
* Torch (PyTorch)
* Accelerate
* Safetensors
* Hugging Face Hub API

---

## 🛠️ Installation and Setup

Before running the notebook, make sure you have the following dependencies installed:

```bash
pip install diffusers transformers accelerate scipy safetensors
```

Additionally, login to Hugging Face to access the model:

```python
from huggingface_hub import notebook_login
notebook_login()
```

---

## 🚀 How to Use

1. **Install Required Libraries**
   Installs necessary Python packages using pip.

2. **Login to Hugging Face Hub**
   Authenticates your session to download and run models from the Hugging Face model hub.

3. **Load Stable Diffusion Pipeline**
   Loads `runwayml/stable-diffusion-v1-5` with appropriate hardware support (CUDA if available).

4. **Enter Text Prompt**
   You can customize the following prompt:

   ```python
   prompt = "ANY PROMPT"
   ```

5. **Generate and Display Image**
   Runs inference and displays the generated image in the notebook. The result is also saved locally as `output.png`.

---

## 📸 Output

The notebook generates an image based on the provided prompt using the Stable Diffusion model. For the current prompt **"space dog in moon"**, the output will be a creative AI-generated visual representation of the solar system saved as:

```bash
output.png
```
OUTPUT:

![image](https://github.com/user-attachments/assets/a25a4b8a-5f1d-4a3b-a38f-26021ad33773)

---

## 📁 File Structure

```
Task02_CODECRAFT.ipynb   # Jupyter Notebook containing the full pipeline
output.png               # Generated image from the given prompt
```

---

## 🧠 Learning Outcome

By completing this task, you will gain practical experience in:

* Using pretrained diffusion models
* Interfacing with Hugging Face's ecosystem
* Generating and manipulating AI-based media
* Handling GPU acceleration in model inference

---
