# 🔐 Cybersecurity LLM Fine-Tuning

This project focuses on fine-tuning a small Large Language Model (LLM) (TinyLlama) on a cybersecurity dataset using QLoRA (Low-Rank Adaptation).

---

## 🚀 Features

* Fine-tuned on cybersecurity instruction dataset
* Covers topics like:

  * C2 (Command & Control) detection
  * TLS traffic analysis
  * MITRE ATT&CK techniques
* Uses efficient fine-tuning (QLoRA) for low-resource systems
* Trained and tested on Google Colab (GPU)

---

## 🛠 Tech Stack

* Python
* Hugging Face Transformers
* PEFT (LoRA)
* Datasets
* Google Colab

---

## 📊 Training Details

* **Base Model:** TinyLlama 1.1B
* **Dataset Size Used:** 15,000 samples
* **Epochs:** 1
* **Training Method:** QLoRA (4-bit quantization)

---

## 📂 Dataset

👉 https://drive.google.com/file/d/17dLlQimm7k-zJ3Hr5LvlXjQqsszc7crF/view?usp=sharing

---

## 📌 Results

* Model generates structured cybersecurity responses
* Understands domain-specific concepts like:

  * TLS-based C2 detection
  * Beaconing analysis
  * Certificate inspection
* Some hallucination observed due to small model size

---

## 👨‍💻 Author

**Himanshu Mourya**
