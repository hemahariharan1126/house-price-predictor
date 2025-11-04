# 🧪 ML Experiments Lab

A collection of hands-on mini-projects, built for actual learning (not hype!)

---

## 📚 Experiments Gallery

Here's what I've been tinkering with:

### 🏠 House Price Predictor
**What I tried:** Trained regression models (Linear, Random Forest, XGBoost) to predict house prices from real estate data.

**Lessons Learned:**
- Feature engineering matters more than model complexity for tabular data
- Outliers can skew predictions—robust preprocessing is essential
- Visual explainability (feature importance, SHAP) builds trust in model outputs

---

### 📊 Customer Churn Classifier
**What I tried:** Binary classification to predict which customers are likely to leave a service.

**Lessons Learned:**
- Class imbalance requires careful handling (SMOTE, class weights)
- Precision vs. Recall trade-offs depend on business costs
- Simple models often outperform complex ones when data is limited

---

### 🖼️ Image Style Transfer
**What I tried:** Applied neural style transfer to blend content and artistic styles using pre-trained CNNs.

**Lessons Learned:**
- Transfer learning saves massive compute time
- Hyperparameter tuning (content/style weight ratios) is more art than science
- GPU access changes everything for image models

---

### 🤖 Sentiment Analysis Bot
**What I tried:** Fine-tuned a transformer model (BERT) to classify movie reviews as positive/negative.

**Lessons Learned:**
- Pre-trained language models capture nuance that traditional ML misses
- Fine-tuning requires surprisingly little data when starting from a good base
- Context matters—sarcasm and domain-specific language can trip up models

---

### 🔍 Recommendation Engine
**What I tried:** Built collaborative filtering and content-based recommenders for movie suggestions.

**Lessons Learned:**
- Cold start problem is real—new users/items need hybrid approaches
- Matrix factorization techniques are elegant and effective
- Real-world recommenders balance relevance with diversity and serendipity

---

## 🎓 Try Your Own!

This repo is all about **learning by doing**. Here's how you can join the fun:

1. **Fork this repo** and add your own experiments
2. **Pick a dataset** that excites you (Kaggle, UCI ML Repository, or your own data)
3. **Start small** – even a simple baseline model teaches you something
4. **Document your learnings** – write down what worked, what didn't, and why
5. **Share your experiments** – open a PR or tag me with your findings!

💡 **Ideas to explore:**
- Time series forecasting (stock prices, weather, energy usage)
- NLP projects (text summarization, topic modeling, chatbots)
- Computer vision (object detection, face recognition, OCR)
- Reinforcement learning (game AI, optimization problems)
- Anomaly detection (fraud, network intrusion, quality control)

---

## 📝 How to Use This Repo

Each experiment folder contains:
- **Jupyter notebooks** with step-by-step code and explanations
- **Datasets** (or links to download them)
- **Trained models** (where size permits)
- **Requirements.txt** for easy setup

To run any experiment:
```bash
cd experiment-name
pip install -r requirements.txt
jupyter notebook
```

---

## 🌟 Why This Exists

Machine learning is best learned through **experimentation**, not just theory. This lab is my personal sandbox for:
- Testing ideas without the pressure of perfection
- Learning from failures as much as successes
- Building intuition about what works in practice
- Documenting the messy, iterative process of real ML work

---

## 📬 Feedback & Collaboration

Found a bug? Have suggestions? Want to collaborate on an experiment?
- Open an issue
- Submit a pull request
- Reach out on [Twitter/LinkedIn/Email]

---

**Real learning happens when you run your own experiments.**
