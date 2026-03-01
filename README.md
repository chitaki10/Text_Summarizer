# TextSummarizer
An end-to-end NLP pipeline that leverages Hugging Face Transformer models to automatically generate concise summaries from long-form text, built with a modular architecture for training, evaluation, and deployment.
# Clone & install
git clone https://github.com/yourusername/textsummarizer.git
cd textsummarizer
pip install -r requirements.txt

# Tech Stack 
transformers 4.45.2 — PEGASUS model + Trainer API

datasets — SAMSum dataset loading and mapping

evaluate — ROUGE metric computation

accelerate 1.0.1 — GPU-accelerated training

torch 2.4.1+cu121 — CUDA 12.2 on NVIDIA L4 GPU

nltk — Sentence tokenization for evaluation batching