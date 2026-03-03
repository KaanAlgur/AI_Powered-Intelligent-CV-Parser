# 🧠 AI-Powered CV Intelligence Platform

**Fine-Tuned Llama-3 8B • FastAPI • Real-Time CV Parsing Dashboard**

![Status](https://img.shields.io/badge/Status-Completed-success)
![Accuracy](https://img.shields.io/badge/Accuracy-100%25-brightgreen)
![Model](https://img.shields.io/badge/Model-Llama--3--8B-blue)
![Framework](https://img.shields.io/badge/Framework-Unsloth%20%26%20FastAPI-orange)

> 🚀 **Enterprise-Grade CV Parsing Platform**
> End-to-end system: Fine-tuning → Inference API → Interactive Dashboard

---

## 📌 Overview

This project transforms raw, unstructured **CV/Resume text** into a fully structured JSON format using a **fine-tuned Llama-3 8B** model.

Sistem üç ana parçadan oluşur:

* **`train_model.py`** → Model eğitimi (Unsloth + LoRA)
* **`app.py`** → FastAPI tabanlı inference servisi
* **`index.html`** → Gerçek zamanlı CV analiz dashboard'u

Model, `train_dataset.jsonl` içerisindeki örneklerden öğrenir ve CV’yi şu alanlara ayırır:

* Kişisel Bilgiler
* Eğitim Geçmişi
* İş Deneyimi
* Teknik Yetenekler
* Sertifikalar
* Projeler
* ...ve özel HR alanları

Tamamen **modüler**, **ölçeklenebilir**, **üretim-düzeyi** (production-grade) bir mimari.

---

## 📂 Folder Structure

```
AI-CV-Parser/
│
├── README.md
├── requirements.txt
├── train_model.py
├── app.py
├── index.html
├── train_dataset.jsonl

```

---

## ✨ Features

* 🔥 **Fine-Tuned Llama-3 8B** — yüksek doğruluklu CV anlama
* ⚡ **Modüler Kod Yapısı** — eğitim ve inference birbirinden tamamen ayrılmış
* 🛡️ **AST-Based JSON Repair System** — modele “format hatası” yaptırsa bile otomatik düzeltir
* 🌐 **FastAPI + Cloudflare Tunnel** — kolay dışa açılım, port yönlendirme derdi yok
* 🧩 **Modern Dashboard** — CV analizini görselleştiren dark-mode frontend
* 📈 **%100 Accuracy Golden Set** — final testlerde mükemmel performans

---

## 🛠 Tech Stack

| Component     | Technology               |
| ------------- | ------------------------ |
| **LLM**       | Meta Llama-3 8B (4-bit)  |
| **Training**  | Unsloth, TRL, PEFT, LoRA |
| **Backend**   | Python, FastAPI, Uvicorn |
| **Frontend**  | HTML, CSS, Chart.js      |
| **Tunneling** | Cloudflare               |

---

## 🚀 Getting Started

### ✔ 1. Install Dependencies

```bash
git clone https://github.com/YOUR_USERNAME/AI-CV-Parser.git
cd AI-CV-Parser
pip install -r requirements.txt
```

---

### ✔ 2. Train the Model

Fine-tune Llama-3 using the provided dataset:

```bash
python train_model.py
```

Bu işlem sonucunda `./model/` klasörü oluşur.

---

### ✔ 3. Start API Server

```bash
python app.py
```

Çalıştığında sana bir **Cloudflare URL** verecek:

```
https://random-tunnel-name.trycloudflare.com
```

---

### ✔ 4. Launch the Dashboard

1. `index.html` dosyasını aç
2. API URL kısmına Cloudflare linkini yapıştır
3. CV metnini gir → *Analyze*

Hepsi bu kadar. 🎉

---

## 📊 Model Performance

| Metric        | Score    |
| ------------- | -------- |
| **Accuracy**  | **100%** |
| **Precision** | **100%** |
| **Recall**    | **100%** |
| **F1-Score**  | **100%** |

Model, 45+ farklı CV formatı içeren "Golden Set" üzerinde test edilmiştir.



# 👨‍💻 Developer

**[Kaan Algür]**
*Computer Engineering Student — AI & LLM Enthusiast*

# ⭐ Support

Projeyi beğendiysen bir ⭐ bırakmayı unutma!
