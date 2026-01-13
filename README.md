# 📊 YouTube Sentiment Analysis – End-to-End MLOps Project 🚀

## 📌 Project Overview
This project is an **end-to-end YouTube Sentiment Analysis system** built using **Machine Learning and MLOps best practices**.  
It covers the complete ML lifecycle from **data preprocessing** to **automated cloud deployment** using **CI/CD pipelines**.

---

## 🔄 End-to-End Workflow
- 📥 Data preprocessing & cleaning  
- 📊 Exploratory Data Analysis (EDA)  
- 🤖 Model training using ML algorithms  
- 🧪 Experiment tracking with **MLflow**  
- 🗂️ Data & model versioning using **DVC**  
- 📈 Model evaluation  
- 🏷️ Model registry using **MLflow**  
- 📦 Docker containerization  
- 🔁 CI/CD using **GitHub Actions**  
- ☁️ Deployment using **AWS ECR & EC2**  

---

## 🧠 Machine Learning Pipeline

### 🧹 Data Preprocessing & Cleaning
- Text normalization  
- Removing stopwords, URLs, emojis, punctuation  
- Tokenization & vectorization  

### 📊 Exploratory Data Analysis (EDA)
- Sentiment distribution  
- Comment length analysis  
- Data visualization  

### 🤖 Model Training
- Machine Learning model for sentiment classification  
- Hyperparameter tuning  
- Experiments tracked with **MLflow**  

### 🧪 Experiment Tracking (MLflow)
- Log parameters, metrics, and artifacts  
- Compare multiple experiments  
- Select best performing model  

### 📈 Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-Score  

### 🏷️ Model Registry
- Register best model using **MLflow Model Registry**  
- Model versioning & reproducibility  

---

## 🛠️ Tools & Technologies

| 🔧 Tool | 📌 Purpose |
|------|-----------|
| 🐍 Python | Programming language |
| 🤖 Scikit-learn | ML model training |
| 🧪 MLflow | Experiment tracking & model registry |
| 🗂️ DVC | Data & model versioning |
| 🐳 Docker | Containerization |
| 🔁 GitHub Actions | CI/CD pipeline |
| ☁️ AWS ECR | Docker image registry |
| 🖥️ AWS EC2 | Cloud deployment |
| 🐧 Ubuntu | Server OS |
| 🧑‍💻 VS Code | Local development |

---

## 🔗 CI/CD Architecture (GitHub ➝ ECR ➝ EC2)

```text
🧑‍💻 Local VS Code
        |
        | git push
        v
🐙 GitHub Repository
        |
        | GitHub Actions (CI/CD)
        v
☁️ AWS ECR (Docker Image Registry)
        |
        | docker pull
        v
🖥️ AWS EC2 (Ubuntu Server)
        |
        | docker run
        v
🚀 Live ML Application

📈 Future Improvements

🤖 Transformer models (BERT)

🔴 Real-time YouTube API integration

📊 Monitoring & logging

☸️ Kubernetes deployment
