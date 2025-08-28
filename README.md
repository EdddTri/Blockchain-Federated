# 🔗 Blockchain + Federated Learning  

## 📌 Project Overview  
This project integrates **Blockchain technology** and **Federated Learning (FL)** to enable **secure, privacy-preserving, and decentralized predictive modeling** in pervasive environments (e.g., IoT).  

- **Federated Learning** ensures that data remains local, while only model weights are shared.  
- **Blockchain** provides a tamper-proof, transparent log of training updates and secures model integrity.  
- Tested successfully on **3+ federated nodes (clients)**, demonstrating scalability in a distributed environment.  
- Implemented on both the **California Housing dataset** (regression) and **MNIST dataset** (image classification).  

---

## 🚀 Key Features  
- **Federated Learning (FL)**  
  - Local training on multiple nodes.  
  - Aggregation of model weights using **FedAvg** strategy.  

- **Blockchain Integration**  
  - SHA-256 hashing of model weights.  
  - Immutable training logs for transparency.  
  - Proof-of-Work validation.  

- **Smart Contract with Solidity**  
  - Dataset hash registration for integrity verification.  
  - Immutable logging of model training events.  
  - Pay-per-prediction system with on-chain payments.  

- **Frameworks Implemented**:  
  - ⚡ **FastAPI**: Server-client FL with blockchain logging.  
  - 🌸 **Flower (FLWR)**: Custom BlockchainFedAvg strategy with AES encryption.  

---

## 🧠 Datasets  
- **California Housing Dataset** – Regression task on housing prices.  
- **MNIST Dataset** – Image classification task with CNNs.  

---

## 📊 Results  

| Dataset              | Model Type  | Metric        | Result     |
|----------------------|-------------|---------------|------------|
| California Housing   | SimpleNN    | Loss (MSE)    | **0.4387** |
| MNIST (CNN)          | SimpleCNN   | Accuracy      | **95.65%** |
| MNIST (CNN)          | SimpleCNN   | Avg. Loss     | **0.1557** |

✅ Blockchain maintained **tamper-proof model updates**, and FL preserved **data privacy** while achieving strong performance.  

---

## ⚙️ Tools & Technologies  
- **Languages**: Python, Solidity  
- **Frameworks/Libraries**: FastAPI, Flower (FLWR), PyTorch, TensorFlow/Keras  
- **Blockchain Tools**: SHA-256, Proof-of-Work, AES Encryption  
- **Techniques**: Federated Learning, FedAvg Aggregation, Smart Contracts  

---

## 📂 Repository Structure  

├── blockchain_federated_fast_api # FL + Blockchain with FastAPI
├── blockchain_federated_flwr # FL + Blockchain with Flower
├── Project_Report.pdf # Detailed report
└── README.md # Project documentation
