📰 AG News Text Classification & Sentiment Analysis RAG Based Agent
🤖 Built with BERT | 📊 Dual Classification | 🚀 Fast & Scalable NLP Pipeline

📌 Overview
This project presents a fine-tuned BERT-based NLP agent that can:

🗞️ Classify news articles into one of four categories: World, Sports, Business, and Science/Technology.

😊 Predict sentiment of the text: Positive, Negative, or Neutral.

Built for robust, real-world text analysis tasks — content moderation, journalism filtering, and social analytics.

🔧 What This Project Does
✔️ Fine-tunes a pre-trained BERT model on the AG News dataset
✔️ Implements dual-task learning: Topic Classification + Sentiment Analysis
✔️ Supports dynamic data sampling (10%–100%) for fast experimentation
✔️ Provides sample predictions on custom input text
✔️ Visualizes output and performance metrics post-inference

🧠 How It Works
📁 Dataset:

AG News corpus (4 categories)

Sampled 10–50% of data for speed & memory flexibility

⚙️ Training Pipeline:

• Tokenization → Padding + Truncation using bert-base-uncased  
• Fine-tuning → 3 epochs, batch sizes (8 train / 16 eval), weight decay 0.01  
• Evaluation → Loss, runtime, throughput (samples/sec, steps/sec)
🧪 Sample Output:
Input: "The stock market is seeing record gains in 2024."  
Category: Business  
Sentiment: Neutral
📊 Performance Metrics
Metric	Value
Evaluation Loss	0.3967
Evaluation Runtime	~22.89 sec
Samples/Sec	33.206
Steps/Sec	2.097

🛠️ Tech Stack
🤗 Transformers (Hugging Face)

BERT (bert-base-uncased)

Python, PyTorch

Google Colab / Jupyter Notebooks

AG News Dataset

🏁 How to Run
⬇️ Clone the repository

⚙️ Open the .ipynb notebook

✅ Install required libraries (transformers, datasets, torch)

🎯 Run cells for:

Sampling dataset (adjust from 10–100%)

Training

Evaluation

Input testing

💡 Use TPU/GPU for faster training. Modify sample size in Step-2 to fit available memory.

🎯 Future Enhancements
🧠 Extend sentiment to emotions like joy, anger, etc.

🏎️ Train on full dataset for improved generalization

🌐 Deploy as an API or Streamlit app

⚡ Leverage multi-GPU support for speed

👨‍💻 Author
Krishianjan Lanka
📍 Binghamton University
