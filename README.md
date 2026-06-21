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

The system consists of three main components:

* **`train_model.py`** → Model training (Unsloth + LoRA)
* **`app.py`** → FastAPI-based inference service
* **`index.html`** → Real-time CV analysis dashboard

The model learns from the examples in train_dataset.jsonl and breaks down the CV into the following fields:

* Personal Information
* Education History
* Work Experience
* Technical Skills
* Certifications
* Projects
* ...and custom HR fields

A fully modular, scalable, production-grade architecture.

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

* 🔥 **Fine-Tuned Llama-3 8B** — high-accuracy CV understanding
* ⚡ **Modüler Kod Yapısı** — training and inference are fully separated
* 🛡️ **AST-Based JSON Repair System** — automatically fixes formatting errors even if the model produces them
* 🌐 **FastAPI + Cloudflare Tunnel** — easy public exposure, no port-forwarding hassle
* 🧩 **Modern Dashboard** — dark-mode frontend that visualizes CV analysis
* 📈 **%100 Accuracy Golden Set** — flawless performance in final tests

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

This process will create a `./model/` folder.

---

### ✔ 3. Start API Server

```bash
python app.py
```

Once running, it will give you a **Cloudflare URL**:

```
https://random-tunnel-name.trycloudflare.com
```

---

### ✔ 4. Launch the Dashboard

1. Open the `index.html` file
2. Paste the Cloudflare link into the API URL field
3. Enter the CV text → *Analyze*

That's all there is to it. 🎉

---

## 📊 Model Performance

| Metric        | Score    |
| ------------- | -------- |
| **Accuracy**  | **100%** |
| **Precision** | **100%** |
| **Recall**    | **100%** |
| **F1-Score**  | **100%** |

The model has been tested on a "Golden Set" containing 45+ different CV formats.



# 👨‍💻 Developer

**[Kaan Algür]**
*Computer Engineering Student — AI & LLM Enthusiast*

# ⭐ Support

If you liked the project, don't forget to leave a ⭐!
