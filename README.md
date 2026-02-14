# 🔹 Veritas AI – Fake News & Deepfake Detection Platform

**Veritas AI** is a multi-source truth verification platform built with Streamlit that combines:

* 🧠 NLP-based fake news detection
* 🌐 Cross-source verification (Govt + Fact-check + News)
* 📸 Image forensic analysis (ELA)
* 🎙️ Voice deepfake detection simulation
* 📊 Interactive credibility scoring dashboard

---

## 🚀 Features

### 🔎 1. Text Truth Scanner

* BERT-based fake news classifier
* Real-time credibility scoring (0–100)
* Multi-source verification:

  * Government websites
  * Fact-checking organizations
  * Trusted news outlets
* Visual trust gauge (Plotly)

---

### 📸 2. Image Deepfake Detection

* Error Level Analysis (ELA)
* Highlights potential image manipulation
* Visual forensic heatmap output

---

### 🎙️ 3. Voice Scan (Prototype)

* Audio upload (MP3/WAV)
* Simulated synthetic voice detection
* Spectral anomaly warning system

---

### 🎨 4. Modern UI

* Glassmorphism design system
* Animated alert ticker
* Interactive dashboards
* Clean professional layout

---

## 🧠 Tech Stack

* Python
* Streamlit
* HuggingFace Transformers
* DuckDuckGo Search API
* Plotly
* Pillow (PIL)
* NumPy

---

## 🏗 Architecture Overview

```
User Input
   ↓
AI Classification (BERT Fake News Model)
   ↓
Multi-Source Search Validation
   ↓
Score Adjustment
   ↓
Visual Credibility Dashboard
```

Additional pipelines:

* Image → Error Level Analysis
* Audio → Spectral Pattern Scan (Simulated)

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Crystal-Flower/Fake_news_detector.git
cd Fake_news_detector
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If you don’t have `requirements.txt`, install manually:

```bash
pip install streamlit google-generativeai duckduckgo-search transformers plotly pillow numpy
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

The app will open in your browser at:

```
http://localhost:8501
```

---

## 📊 How Scoring Works

1. AI classifier predicts:

   * `LABEL_1` → Verified
   * `LABEL_0` → Suspicious

2. Base score = model confidence

3. +10 score boost if:

   * Government source found
   * Fact-checker confirmation found

4. Final output:

   * ✅ Verified (>70)
   * 🚨 Suspicious (<70)

---

## 📸 Example Use Cases

* Checking viral WhatsApp forwards
* Detecting misinformation headlines
* Validating suspicious screenshots
* Identifying AI-generated voice clips
* Academic misinformation research
* Media literacy tools

---

## 🛠 Future Improvements

* Real deepfake detection model (CNN-based)
* Live social media monitoring
* Source reliability ranking system
* Blockchain verification layer
* User credibility history tracking
* API version for integration

---

## 📁 Project Structure

```
Fake_news_detector/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 🎯 Vision

Veritas AI aims to become a **real-time misinformation defense system** combining AI classification, forensic tools, and trusted source verification into one accessible platform.

---

## 👩‍💻 Author

Crystal Flower
GitHub: [https://github.com/Crystal-Flower](https://github.com/Crystal-Flower)

---

## ⭐ Support

If you found this useful:

* ⭐ Star the repository
* 🍴 Fork it
* 🤝 Contribute
* 💬 Share feedback

