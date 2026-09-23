# VeriStream Authenticator 🛡️
> **Real-Time Deepfake Detection & Synthetic Content Firewall**
> *Built for Perspectra Ideathon 2026 | Lokmanya Tilak College of Engineering*

![Digital India Act Compliant](https://img.shields.io/badge/Compliance-Digital%20India%20Act-blue)
![DPDP Compliant](https://img.shields.io/badge/Privacy-100%25%20On--Device%20DPDP-emerald)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview
**VeriStream Authenticator** is a client-side edge firewall that detects synthetic media and deepfakes in real-time. By utilizing quantized Vision Transformers (`ViT`) via WebAssembly (`WASM`), remote photoplethysmography (`rPPG`) bio-pulse tracking, and `C2PA` cryptographic provenance seals, VeriStream offers instant protection with zero cloud server latency and complete user privacy.


## ✨ Key Features
- **Client-Side ViT Engine**: Sub-35ms frame latency running directly in browser memory via WASM/WebGL.
- **Explainable AI (Grad-CAM)**: Visual heatmap overlays highlighting manipulated facial regions for rapid triage.
- **Bio-Pulse (rPPG) Liveness**: Detects micro-dermal blood volume pulse signals to identify synthetic faces.
- **Audio-Visual Lip Sync Matching**: Detects frequency mismatches between vocal spectrographs and facial landmarks.
- **Cryptographic C2PA Provenance**: Stamps immutable metadata manifest seals onto verified media.
- **Automated DIA Safe-Harbor Takedown**: Triggers instant quarantine notices under Digital India Act mandates.


## 🛠️ Tech Stack
- **Frontend**: React 18, Tailwind CSS, Lucide Icons, WebGL
- **Machine Learning**: Hugging Face Vision Transformer (`ViT-Base-Patch16`), ONNX Runtime Web
- **Backend Microservices**: Python 3.11, FastAPI, `c2pa-python` SDK, OpenCV, Librosa


## 🚀 Quick Start (Local Setup)

No complex installations or Node.js required for the presentation demo:

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/veristream-authenticator.git](https://github.com/YOUR_USERNAME/veristream-authenticator.git)
   cd veristream-authenticator
