# 3Dgen
This repository contains my project to generate 3D models from text and image inputs.

# 🧠 3D Object Generation with Shap-E

This project uses [OpenAI’s Shap-E](https://github.com/openai/shap-e) model to generate 3D mesh models from either text prompts or images. It supports both types of inputs and outputs `.obj` and `.ply` files.

---

## 🔗 If Working in Google Colab 
Colab gives free access to GPUs and lets you run the project entirely in the cloud without local installation.

---

## 🚀 Features

- Generate 3D models from **text** (e.g., "a red toy car")
- Generate 3D models from **images** (background is removed first)
- Outputs 3D files in `.obj` and `.ply` format
- Uses OpenAI's `shap-e` diffusion-based model

---

## 📁 How to Clone the Repository

```bash
git clone https://github.com/TAMANNA230904/3Dgen.git
cd 3Dgen
```

## Create virtual environment if Working Locally

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
## Install dependencies
```bash
pip install -r requirements.txt
```
## Clone and Install shap-e
```
git clone https://github.com/openai/shap-e.git
cd shap-e
pip install -e .
```

