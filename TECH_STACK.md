# Tech Stack

Dokumentasi lengkap teknologi yang digunakan dalam repositori Final Project KCVanguard Workshop 2025.

## Overview

Repositori ini berisi beberapa project dengan berbagai tech stack, terutama fokus pada:
- **Machine Learning & Deep Learning**: Generative Adversarial Networks (GANs), Computer Vision
- **Backend Development**: FastAPI, Python
- **Frontend Development**: Next.js, React
- **Deployment**: Docker, Hugging Face, Vercel

---

## 🧠 Machine Learning & AI Frameworks

### Deep Learning
- **PyTorch** - Framework utama untuk training dan inference model GAN
  - `torch` - Core PyTorch library
  - `torchvision` - Computer vision utilities
  - `triton` - GPU programming
- **TensorFlow** - Framework ML untuk beberapa aplikasi
- **ONNX Runtime** - Optimized inference runtime untuk model ML

### GAN Architectures
Berbagai arsitektur Generative Adversarial Network yang diimplementasikan:
1. **Vanilla GAN** - Basic GAN implementation
2. **DCGAN** (Deep Convolutional GAN)
3. **ProGAN** (Progressive GAN)
4. **StyleGAN** - Style-based generator
5. **StyleGAN2-ADA** - Adaptive Discriminator Augmentation

### Scientific Computing
- **NumPy** - Numerical computing
- **SciPy** - Scientific computing dan advanced math
- **Pillow (PIL)** - Image processing

---

## 🖥️ Backend Technologies

### Web Frameworks
- **FastAPI** - Modern, fast web framework untuk building APIs
  - `uvicorn` - ASGI server
  - `starlette` - Web framework foundation
  - `pydantic` - Data validation
- **Python 3.9+** - Primary programming language

### Additional Backend Libraries
- `python-multipart` - Multipart form data parsing
- `huggingface_hub` - Integration dengan Hugging Face Hub
- `requests` - HTTP library
- `click` - Command-line interface creation

---

## 🎨 Frontend Technologies

### Framework & Libraries
- **Next.js 15.2.4** - React framework dengan server-side rendering
- **React 19.0.0** - UI library
- **TypeScript 5.x** - Type-safe JavaScript
- **Tailwind CSS 4.x** - Utility-first CSS framework

### Development Tools
- `@types/node` - TypeScript definitions untuk Node.js
- `@types/react` - TypeScript definitions untuk React
- `@types/react-dom` - TypeScript definitions untuk React DOM

---

## 🎯 UI/Demo Frameworks

### Interactive Demos
- **Streamlit** - Framework untuk membuat web apps dengan Python
- **Gradio** - Library untuk membuat ML demos dan interfaces

---

## 🐳 DevOps & Deployment

### Containerization
- **Docker** - Container platform
  - Base image: `python:3.9-slim`
  - Multi-stage builds untuk optimasi
  - Non-root user untuk security

### Deployment Platforms
- **Hugging Face Spaces** - Hosting untuk ML demos
  - Streamlit deployment
  - Gradio deployment
- **Vercel** - Deployment untuk Next.js frontend
- **GitHub Actions** - CI/CD untuk PR structure validation

---

## 📊 Development Tools

### Notebooks
- **Jupyter Notebook (.ipynb)** - Interactive development dan experimentation

### Version Control
- **Git** - Version control system
- **GitHub** - Repository hosting dan collaboration

---

## 🔧 CUDA & GPU Support

### NVIDIA CUDA Libraries
Untuk GPU-accelerated computing:
- `nvidia-cublas-cu12`
- `nvidia-cuda-cupti-cu12`
- `nvidia-cuda-nvrtc-cu12`
- `nvidia-cuda-runtime-cu12`
- `nvidia-cudnn-cu12`
- `nvidia-cufft-cu12`
- `nvidia-curand-cu12`
- `nvidia-cusolver-cu12`
- `nvidia-cusparse-cu12`
- `nvidia-nccl-cu12`

---

## 📦 Package Management

### Python
- **pip** - Python package installer
- **requirements.txt** - Dependency specification

### JavaScript/Node.js
- **npm** - Node package manager
- **package.json** - Dependency specification

---

## 🏗️ Project Structure

```
fp-kcvanguard-workshop-2025/
├── example-app/          # Example application (Playing Card Classification)
│   ├── app/             # FastAPI + TensorFlow application
│   └── notebook/        # Jupyter notebooks
├── gan-batik/           # BatikGAN project
│   ├── BatikGAN-FE-Next/        # Next.js frontend
│   ├── FastAPI-Batik-GAN/       # FastAPI backend
│   ├── batikgan-gradio/         # Gradio demo
│   ├── batikgan-streamlit-demo/ # Streamlit demo
│   └── notebook/                # Training notebooks
└── .github/
    └── workflows/       # GitHub Actions CI/CD
```

---

## 📚 Key Dependencies Summary

### Example App (Playing Card Classification)
- FastAPI + Uvicorn
- TensorFlow
- NumPy, Pillow
- Docker deployment

### GAN-Batik (BatikGAN)

#### Frontend
- Next.js 15.2.4 + React 19
- TypeScript
- Tailwind CSS 4

#### Backend (FastAPI)
- FastAPI + Uvicorn
- PyTorch + Torchvision
- ONNX Runtime
- Pillow

#### Demo Apps
- **Streamlit**: PyTorch, ONNX Runtime, NumPy, SciPy
- **Gradio**: PyTorch, ONNX Runtime, Gradio, NumPy, Pillow

#### Training/Research
- PyTorch
- Berbagai GAN implementations
- Jupyter Notebooks

---

## 🔗 Deployment URLs

### BatikGAN Deployments
- **Streamlit Demo**: [https://thisusernamealreadyexistsalreadyexists-batikgan-e7dd5c0.hf.space](https://thisusernamealreadyexistsalreadyexists-batikgan-e7dd5c0.hf.space)
- **Gradio Demo**: [https://cthleen-batik-test2.hf.space](https://cthleen-batik-test2.hf.space)
- **Next.js Frontend**: [https://batik-gan-fe.vercel.app](https://batik-gan-fe.vercel.app)

---

## 📝 Notes

- Semua aplikasi menggunakan **Python 3.9+** sebagai runtime utama
- GPU acceleration tersedia melalui CUDA 12.x
- Frontend menggunakan modern React ecosystem dengan Next.js 15
- Backend API services menggunakan FastAPI dengan async support
- Model ML di-deploy menggunakan ONNX Runtime untuk inference optimization
