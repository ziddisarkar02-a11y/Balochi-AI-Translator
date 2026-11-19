# 🌐 Balochi AI Translator

> **Break language barriers with the first-ever AI-powered trilingual translator for Balochi, English, and Urdu.**

![Balochi AI Translator](https://img.shields.io/badge/AI-Gemini%20Pro-blue) ![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Web-green) ![License](https://img.shields.io/badge/License-MIT-orange)

## 📌 Overview

**Balochi AI Translator** is an advanced translation application engineered to bridge the digital gap for the Balochi language. Powered by **Google Gemini AI**, the application provides real-time, context-aware translations between **Balochi, English, and Urdu**. 

It features dual-script rendering for Balochi (Arabic script & Latin transliteration), speech synthesis, real-time two-way live conversation interpretation, and secure cloud sync.

---

## ✨ Key Features

### 1. 🔀 Trilingual & Multi-Directional Translation
- Seamless two-way translation across **Balochi ↔ English ↔ Urdu**.
- High context accuracy using Google’s advanced Gemini LLM models.

### 2. ✍️ Dual Balochi Script Support
- **Arabic-based Balochi Script (عربی)**: Standard written Balochi script.
- **Latin Transliteration**: Enables non-native speakers or modern users to read Balochi using Latin characters.
- **Dual Display Mode**: View both scripts side-by-side for learning and clarity.

### 3. 🎙️ Voice & Real-Time Live Interpreter
- **Balochi AI Audio Engine**: One-tap voice-to-text translation with natural speech output.
- **Two-Way Live Interpreter**: Interactive conversation mode where Gemini AI listens, translates, and speaks back sequentially between Person A and Person B.
- **Voice Customization**: Adjust playback speed ($0.5\times$ to $2.0\times$) and volume levels.

### 4. 🔑 Custom Gemini API Integration
- Bring Your Own Key (BYOK): Users can securely plug in their custom **Google AI Studio Gemini API Key**.
- Fallback support via Firebase AI services.

### 5. 📜 Searchable Translation History & Encryption
- Every translation is privately encrypted and synced per account using **Cloud Firestore**.
- Filter history by translation type: **Text**, **Voice**, or **Live**.

### 6. 🎨 Personalization & UI Modes
- Multi-theme support: **Midnight Dark**, **Daylight**, and **System Default**.
- Integrated **Google Sign-In** for seamless user authentication.

---

## 🛠️ Tech Stack & Architecture

- **AI Model & Engine**: Google Gemini API (Google AI Studio)
- **Backend & Auth**: Firebase Authentication & Cloud Firestore
- **State Management & Encryption**: Local Encrypted Storage / Secure Keychain
- **UI & Audio**: Native Audio Engine & Responsive Interface Design

---

## 🚀 Getting Started

### Prerequisites
- A valid **Google AI Studio API Key** (Get it from [aistudio.google.com](https://aistudio.google.com/)).

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ziddisarkar02-a11y/Balochi-AI-Translator.git](https://github.com/ziddisarkar02-a11y/Balochi-AI-Translator.git)
   cd Balochi-AI-Translator
