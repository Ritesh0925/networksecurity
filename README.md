# 🛡️ Network Security Project — Phishing Detection System

An end-to-end **Machine Learning based Phishing Detection System** built for network security.
This project detects malicious phishing websites using URL and network-based features, helping users and organizations stay protected against cyber threats.

---

## 🚀 Features

* 🔍 Detect phishing websites using ML models
* 📊 Data preprocessing and feature engineering
* 🤖 Model training, evaluation & prediction pipeline
* 🐳 Dockerized deployment
* ☁️ AWS deployment using EC2 + ECR
* 🔄 CI/CD with GitHub Actions

---

## 🏗️ Project Architecture

```bash
Data Ingestion → Data Validation → Data Transformation → Model Training → Prediction → Deployment
```

---

## 📂 Project Structure

```bash
NetworkSecurity/
│
├── artifacts/
├── networksecurity/
│   ├── components/
│   ├── pipeline/
│   ├── utils/
│   ├── entity/
│   └── exception/
│
├── notebook/
├── app.py
├── main.py
├── requirements.txt
├── Dockerfile
└── README.md
```

---

## ⚙️ Tech Stack

* Python
* Machine Learning
* Pandas / NumPy / Scikit-learn
* MongoDB
* Docker
* AWS EC2
* AWS ECR
* GitHub Actions

---

# 🔐 GitHub Secrets Setup

Configure the following GitHub Secrets:

```bash
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION=us-east-1

AWS_ECR_LOGIN_URI=788614365622.dkr.ecr.us-east-1.amazonaws.com/networkssecurity

ECR_REPOSITORY_NAME=networkssecurity
```

---

# 🐳 Docker Setup on EC2

## Optional Updates

```bash
sudo apt-get update -y
sudo apt-get upgrade -y
```

## Required Setup

```bash
curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
```

---

# ▶️ Installation

Clone repository:

```bash
git clone https://github.com/yourusername/NetworkSecurity.git
cd NetworkSecurity
```

Create virtual environment:

```bash
python -m venv venv
```

Activate environment:

### Windows

```bash
venv\Scripts\activate
```

### Linux/Mac

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run application:

```bash
python app.py
```

---

# 🧠 ML Workflow

* Data Collection
* Data Cleaning
* Feature Extraction
* Model Training
* Evaluation
* Deployment

---

# 📈 Future Improvements

* Deep Learning based phishing detection
* Real-time browser extension
* Live threat intelligence integration
* Dashboard for monitoring attacks

---

# 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit pull requests.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Ritesh Kumar Gupta**
B.Tech Data Science | AI & ML Enthusiast | Cybersecurity Explorer
