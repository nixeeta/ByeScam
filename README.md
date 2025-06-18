# ByeScam - 🛡️ AI-Powered Scam Call & Message Detector

An AI-driven mobile/web solution that detects and flags scam calls and SMS messages using NLP techniques, user reports, and crowdsourced data. This project aims to protect users—especially in India’s Tier 2/3 cities—from rising cyber threats, job frauds, and phishing attempts.

## 🚨 Problem Statement
In India alone, millions of users receive scam messages daily—promising fake jobs, lottery wins, or fraudulent bank alerts. Traditional spam filters are ineffective against phishing scams in regional languages. This tool bridges that gap with machine learning and crowd intelligence.

## 💡 Key Features
- 🔍 **Real-Time Scam Classification** for SMS & call logs
- 🌐 **Crowdsourced Reporting** of scam numbers & patterns
- 🧠 **NLP-Powered Detection Engine** (supports Hinglish & regional languages)
- 📊 **Dashboard** to visualize scams detected and reported
- 🔐 **Privacy-First Design** — no third-party data selling

## 🧱 Tech Stack
- **Frontend**: React Native / React.js
- **Backend**: Node.js + Express
- **ML/NLP**: Python (scikit-learn, spaCy, Transformers)
- **Database**: Firebase / MongoDB
- **Deployment**: Vercel + Render

## 🧠 ML Pipeline
1. Text Preprocessing (Stopwords, tokenization, lang-detect)
2. Feature Extraction (TF-IDF / BERT Embeddings)
3. Classification (Random Forest / XGBoost / Fine-tuned BERT)
4. Continuous Learning via user feedback

## 📦 Project Structure
📁 client/ # React app
📁 server/ # Node.js backend
📁 ml-model/ # Python NLP scripts
📁 data/ # Sample SMS/call datasets
README.md

## 🔍 Example Use Case
> 🚫 Detected Scam Message:  
> _"Congratulations! You won ₹5,00,000 in the KBC Lottery. Send your bank details to claim."_

## 🌍 Social Impact
This tool can help prevent:
- Financial loss from fake job scams
- Identity theft
- Elderly exploitation via phone scams

## 🤝 Contributions
We welcome data contributions, regional language support, and mobile integration help. See the [`CONTRIBUTING.md`](./CONTRIBUTING.md) file.

## 📜 License
MIT License