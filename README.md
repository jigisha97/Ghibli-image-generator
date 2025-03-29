# 🎨 Ghibli Image Generator with BLIP + Stable Diffusion

Turn any image into a Studio Ghibli-style artwork using AI!

This project combines the power of **BLIP (Image Captioning)** and **Stable Diffusion Img2Img** using the `nitrosocke/ghibli-diffusion` model to automatically generate stylized Ghibli-inspired images.

---

## ✨ Features

- 🔍 Automatically describe any image using `Salesforce/blip-image-captioning-base`
- 🎨 Stylize the image using `nitrosocke/ghibli-diffusion`
- ⚙️ Simple pipeline to go from real image ➝ Ghibli magic
- 🖼️ Before-After image creation (optional)

---

## 🧰 Tech Stack

- Python 🐍
- HuggingFace Transformers 🤗
- diffusers
- Torch / PIL

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/ghibli-image-generator.git
cd ghibli-image-generator
