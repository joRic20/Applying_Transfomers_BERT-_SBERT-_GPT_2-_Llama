<!-- PROJECT LOGO -->
<p align="center">
  <a href="https://github.com/YourUsername/NLP_4_Exercise_Transformers">
    <img src="docs/logo.png" alt="Project Logo" width="120" height="120">
  </a> 

  <h3 align="center">Advanced Transformer Representations in NLP</h3>

  <p align="center">
    Hands-on exploration of BERT, SBERT, GPT-2 and LLaMA for text embeddings and performance benchmarking.
    <br />
    <a href="https://github.com/YourUsername/NLP_4_Exercise_Transformers"><strong>📓 View Notebook »</strong></a>
    ·
    <a href="https://linkedin.com/in/YourLinkedInProfile">🔗 LinkedIn Profile</a>
    ·
    <a href="#contact">✉️ Contact</a>
  </p>
</p>

---

## 📖 About The Project

This exercise notebook demonstrates how to:

- **Tokenize** text using BERT’s WordPiece and GPT-2’s Byte Pair Encoding.
- **Extract embeddings** from:
  - BERT (base-uncased)
  - Sentence-BERT (SBERT)
  - GPT-2
  - Meta’s LLaMA
- **Compare performance**: CPU vs. GPU inference times on sample datasets.
- **Visualize** and interpret differences in embedding dimensions and structures.

---

## 🛠️ Features

- **Modular code**: Clear sections for each transformer model.
- **Reusable functions** for tokenization, embedding extraction, and timing.
- **Pandas DataFrame** pipeline to handle input text and store embeddings.
- **Performance benchmarks** with `time` module.
- **Extensible**: Plug in your own dataset or additional transformer models.

---

## 🚀 Built With

- [Python 3.9+](https://www.python.org/)
- [PyTorch](https://pytorch.org/)
- [Transformers (Hugging Face)](https://github.com/huggingface/transformers)
- [pandas](https://pandas.pydata.org/)
- [Sentence-Transformers](https://www.sbert.net/)

---

## 📂 Repository Structure


---

## 💻 Installation


python -m venv .venv
source .venv/bin/activate        # Linux/macOS
.\.venv\Scripts\activate         # Windows


pip install -r requirements.txt

jupyter notebook notebooks/NLP_4_Exercise_Transformers.ipynb
