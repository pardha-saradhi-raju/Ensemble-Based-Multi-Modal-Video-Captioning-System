# 🎥 Ensemble-Based Multi-Modal Video Captioning

An AI-powered system that generates rich, context-aware captions for videos by integrating **visual**, **audio**, and **textual** data using state-of-the-art models like **BLIP**, **CLIP**, **Google Speech Recognition**, **Google Gemini AI**, and **Google Translate**. The system enhances accessibility, searchability, and content understanding for applications in education, assistive technology, and video summarization.

---

## 📌 Problem Statement

Traditional video captioning systems rely heavily on visual features and often produce **incomplete or ambiguous descriptions**, ignoring the valuable context provided by **speech and audio**. This project addresses that limitation by building a **multi-modal architecture** that combines audio, visual, and linguistic data to generate fluent, accurate, and human-like captions.

---

## 🚀 Features

- 🎞️ **Scene Description** using **BLIP** (Bootstrapped Language Image Pretraining)
- 🕺 **Action Recognition** using **CLIP** (Contrastive Language–Image Pretraining)
- 🎙️ **Speech Transcription** with **Google Speech Recognition**
- 🧠 **Caption Refinement** & Grammar Correction using **Google Gemini AI**
- 🌐 **Multilingual Translation** using **Google Translate API**
- 📊 **Evaluation** using BLEU, METEOR, and ROUGE metrics

---

## 🛠️ Tech Stack

- Python  
- BLIP  
- CLIP  
- Google Speech Recognition API  
- Google Gemini AI  
- Google Translate API  
- OpenCV  
- Transformers, PyTorch, HuggingFace

---

## 🧩 System Architecture

```text
Input Video
   ├──▶ Keyframe Extraction
   │      ├──▶ Scene Captioning (BLIP)
   │      └──▶ Action Recognition (CLIP)
   ├──▶ Audio Extraction
   │      └──▶ Speech Transcription (Google Speech Recognition)
   └──▶ Caption Refinement (Gemini AI)
           └──▶ Multilingual Translation (Google Translate)
```

---

## ✅ Sample Output

### 📸 Input Frame:
![image](https://github.com/user-attachments/assets/ed2c182d-06bc-49f8-b3cd-19febe0bacc7)

---

## 📈 Results

| Metric     | Score   |
|------------|---------|
| BLEU-1     | 0.6792  |
| BLEU-2     | 0.4301  |
| BLEU-3     | 0.2546  |
| BLEU-4     | 0.1506  |
| METEOR     | 0.5136  |
| ROUGE-1    | 0.5146  |
| ROUGE-2    | 0.2637  |
| ROUGE-L    | 0.4651  |

> 🔍 The system performs well on unigram-level accuracy and shows good semantic relevance. Future work will focus on improving long-sequence fluency and real-time video input support.

---

## 📂 Dataset

**MSVD (Microsoft Video Description Dataset)**  
A standard benchmark dataset with ~2,000 short video clips and multiple human-written captions per clip. It offers diverse scenes, actions, and dialogues to test the generalization of video captioning systems.

---

## 🎯 Applications

- Assistive Technology for Visually Impaired  
- YouTube/Streaming Auto-Captioning  
- Educational Video Summarization  
- Video Content Indexing & Search  
- Social Media Reels/Shorts Captioning  
- Multilingual Access to Global Video Content  

---

## 🔮 Future Improvements

- ⏱️ Real-time captioning for live/streaming videos  
- 🧪 Domain-specific fine-tuning (e.g., healthcare, education)  
- 🌍 Multilingual speech transcription  
- 🖼️ UI for uploading and captioning user videos  
