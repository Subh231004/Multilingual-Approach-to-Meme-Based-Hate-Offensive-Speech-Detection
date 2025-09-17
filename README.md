# Multilingual-Approach-to-Meme-Based-Hate-Offensive-Speech-Detection
A multimodal deep learning project for detecting hate, offensive, sarcastic, vulgar, abusive, and targeted content in memes. The system combines OCR-based text extraction and image feature analysis using CNNs, then fuses both modalities for multi-label classification. Evaluated with accuracy, F1-score, and confusion matrix to ensure robustness.  
🌐 Meme-based Hate & Offensive Speech Detection

A multimodal deep learning project that combines OCR + NLP + Computer Vision to detect hate, offensive, sarcastic, and abusive content in memes.
This system processes both text (captions) and image features, fuses them, and classifies across multiple labels like Sentiment, Sarcasm, Vulgarity, Abuse, Target, and Usage.

📌 Why This Project Matters

Memes are one of the most viral forms of communication on social media. While fun and entertaining, they can also carry hidden hate speech, offensive jokes, and abusive targeting that traditional text-only systems often miss.

✅ Why important?

🌍 Helps build safer social media environments

🤖 Advances research in multimodal AI (text + image fusion)

🛡️ Detects hidden hate speech disguised in humor

📊 Provides datasets & models for future research

⚙️ Features

🖼️ OCR-based text extraction from meme images

🧾 Text preprocessing & embeddings (Word2Vec / GloVe)

🎨 Image feature extraction with CNNs

🔀 Feature fusion (text + image)

🏷️ Multi-label classification (sentiment, sarcasm, vulgarity, abuse, target, use)

📈 Evaluation using Accuracy, F1-score, Confusion Matrix

📂 Project Structure
├── notebooks/                # Jupyter notebooks (4 main workflows)
│   ├── Bodo_prediction.ipynb
│   ├── Gujrati_W2V.ipynb
│   ├── Bangla_meme_dataset.ipynb
│   ├── Enhanced_pipeline.ipynb
├── data/                     # Datasets (ignored in .gitignore)
├── models/                   # Saved models (ignored in .gitignore)
├── outputs/                  # Results, plots, logs
├── requirements.txt          # Dependencies
├── .gitignore                # Ignore unnecessary files
└── README.md                 # Project documentation

🚀 Setup & Installation

1️⃣ Clone the repository

git clone https://github.com/your-username/meme-hate-detection.git
cd meme-hate-detection


2️⃣ Install dependencies

pip install -r requirements.txt


3️⃣ Run Jupyter Notebook

jupyter notebook

🧠 Workflow Overview

📥 Input Meme (Image + Text)

🔎 OCR → Extract caption text

✍️ Text Preprocessing & Embeddings

🖼️ Image Feature Extraction (CNN)

🔀 Fusion of Features

🏷️ Classification into multi-labels

📊 Evaluation & Results

📊 Results (Sample)

Accuracy: ~85%

Macro F1-score: ~0.81

Confusion Matrix: Shows balanced predictions across labels

(Results may vary based on dataset & preprocessing)

🔮 Future Enhancements

🔍 Use transformers (BERT, CLIP, ViT) for better feature extraction

📦 Deploy as a web app / API

📊 Train on larger multilingual datasets

⚡ Real-time meme moderation for social platforms

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License.
