# SentimentScope: Transformer-Based Sentiment Analysis on IMDB Dataset 🚀

**SentimentScope** is a transformer-based sentiment analysis model tailored for the IMDB dataset. Developed from scratch using **PyTorch**, this project demonstrates building a custom transformer architecture for binary sentiment classification, moving beyond pre-trained APIs. 💻✨

---

## Project Overview 📝

As an **Future AWS AI Scientist**, the goal was to design a custom transformer model capable of classifying movie reviews as positive or negative with high accuracy. The project involved end-to-end data preprocessing, model design, training, and evaluation.

Key features:
- 🛠️ Custom GPT-style transformer architecture for classification.
- 📦 Robust dataset handling with tokenization, padding, and truncation.
- ⚙️ Full training pipeline including optimizer, loss, and validation monitoring.

---

## Results 📊

- Processed **50,000 IMDB reviews** into tokenized tensors.
- Built a **DemoGPT Transformer** modified for binary classification.
- Achieved **76.92% Test Set Accuracy** after 3 epochs, surpassing the >75% target. ✅
- Demonstrated effective sentiment classification for real-world text data.

---

## Key Takeaways 🎓

- Implemented a **custom `IMDBDataset` class** for batch-ready data.
- Developed core **Transformer components**: Self-Attention, Multi-Head Attention, FeedForward Networks, Residual Blocks.
- Completed a **training pipeline** with `CrossEntropyLoss` and `AdamW`.
- Adapted a GPT-style model for classification by replacing the language head with **Mean Pooling + Linear Classification**.

---

## Requirements ⚡

- Python 3.9+
- PyTorch
- NumPy, Pandas, Matplotlib
- Hugging Face Transformers
- tqdm

---

## Contact 📫

I am always open to feedback, discussions, or collaborations!  

- ✉️ Email: **dani.ai.practitioner@gmail.com**  
- 🔗 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/danyal-ai)  

---

# Acknowledgements 🙏

Thanks to the Udacity and AWS team and the PyTorch community for their support and inspiration in building this project.

---
