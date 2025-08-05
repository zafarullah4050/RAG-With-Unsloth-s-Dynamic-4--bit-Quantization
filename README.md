# RAG-With-Unsloth-s-Dynamic-4--bit-Quantization
# 🔍 Retrieval-Augmented Generation (RAG) using Unsloth 4-bit Quantized Models

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using **Unsloth’s dynamic 4-bit quantized models**, ideal for running on low VRAM environments like Google Colab.

📄 The pipeline loads a custom PDF, splits it into chunks, embeds and indexes them with FAISS, and answers user questions based on **retrieved relevant context**.

---

## 🚀 Features

- 🔗 **Unsloth LLaMA 3 4-bit** model for low-memory inference.
- 📄 **PDF document ingestion** and chunking.
- 🧠 **HuggingFace sentence embeddings** for semantic search.
- 📚 **FAISS vectorstore** for fast similarity retrieval.
- 🔁 **LangChain RAG pipeline** with custom prompts.
- ⚡️ Optimized for **Colab or low-VRAM GPUs** using 4-bit dynamic quantization.

---

## 📁 Project Structure

