## 📘 Abstractive Summarization

This repository contains implementations of **Abstractive Text Summarization** using various transformer-based models such as BART, PEGASUS, T5, Longformer, ProphetNet, RAG, and Long-T5. These models generate concise and coherent summaries by learning to paraphrase and rephrase the input content.

---

### 🚀 Models Covered

| Notebook                                      | Model                      | Dataset             |
| --------------------------------------------- | -------------------------- | ------------------- |
| `01_bart_cnn_dailymail.ipynb`                 | BART                       | CNN/DailyMail       |
| `02_pegasus_cnn_dailymail.ipynb`              | PEGASUS                    | CNN/DailyMail       |
| `03_pegasus_xsum.ipynb`                       | PEGASUS                    | XSum                |
| `04_t5_zero_shot.ipynb`                       | T5                         | Zero-shot           |
| `05_longformer_multi_news.ipynb`              | Longformer Encoder-Decoder | Multi-News          |
| `06_xlnet_prophetnet_rag_summarization.ipynb` | XLNet, ProphetNet, RAG     | Multi-source        |
| `07_zero_shot_summarization_long_t5.ipynb`    | Long-T5                    | Long-form Zero-shot |

---

### 🧠 What is Abstractive Summarization?

Abstractive summarization involves **generating novel sentences** that may not appear in the source text but convey the intended meaning. It requires deep semantic understanding and natural language generation capabilities, unlike extractive summarization which selects and ranks existing sentences.

---

### 📂 Folder Structure

```
abstractive-summarization/
├── Notebooks/
│   ├── 01_bart_cnn_dailymail.ipynb
│   ├── 02_pegasus_cnn_dailymail.ipynb
│   ├── 03_pegasus_xsum.ipynb
│   ├── 04_t5_zero_shot.ipynb
│   ├── 05_longformer_multi_news.ipynb
│   ├── 06_xlnet_prophetnet_rag_summarization.ipynb
│   └── 07_zero_shot_summarization_long_t5.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```

---

## 💻 Run Locally

```bash
git clone https://github.com/Koushim/abstractive-text-summarization-transformers.git
cd abstractive-text-summarization-transformers
pip install -r requirements.txt
````

---

### 📈 Future Work

* [ ] Integrate model evaluation (ROUGE, BLEU)
* [ ] Add Streamlit app for interactive summarization
* [ ] Include few-shot fine-tuning examples
* [ ] Add batch summarization pipeline

---

## ✍️ Author

**Koushik Reddy**
🔗 [Hugging Face](https://huggingface.co/Koushim) | [LinkedIn](https://www.linkedin.com/in/koushik-reddy-k-790938257)

---

## 📌 License

This project is open source and available under the [Apache License](LICENSE).

