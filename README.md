# Image-generation-using-stable-diffusion-in-comfyUI
# 🔥 Image Generation with Stable Diffusion – ComfyUI Workflow  

This repository contains a **custom ComfyUI workflow** for **Stable Diffusion v1.5** to generate high-quality images. The workflow is stored in `project_v1.json`, which can be imported directly into **ComfyUI** for easy setup.  

---

## **📷 Features**
✅ **Stable Diffusion v1.5** – Generates high-quality AI images  
✅ **ComfyUI Support** – Uses **ComfyUI JSON workflow** for a **node-based interface**  
✅ **ControlNet Support (Optional)** – Enables structured image generation  
✅ **Real-ESRGAN Upscaling** – Upscales images for **4K+ resolution**  
✅ **LDetailer & Inpainting** – Enhances facial details and fixes image artifacts  
✅ **Custom Sampling Settings** – Optimized for **photo-realism and artistic styles**  

---

## **🚀 How to Use**
### **1️⃣ Install & Set Up ComfyUI**
If you haven't installed **ComfyUI**, follow these steps:  

# Clone ComfyUI
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI

# Install dependencies
pip install -r requirements.txt

---

## **Add Workflow to ComfyUI**
✅ **Download** **project_v1.json** from this repository.
✅ **Open ComfyUI** (by running run.bat on Windows or python main.py on Linux/Mac).
✅ **Drag & Drop** **project_v1.json** into the ComfyUI window.
✅ Click **"Load Workflow"** and select project_v1.json.
✅ Check the nodes in the workflow and ensure all dependencies **(ControlNet, Real-ESRGAN, etc.)** are installed.
✅ Click **"Queue Prompt"** to generate an image.
```bash
