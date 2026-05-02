# 🎨 Painting Price Prediction using Deep Learning

## 📌 Overview
This project focuses on predicting artwork prices using deep learning techniques. It is a model-based implementation where visual features from paintings are used to estimate their price. The system is built using a hybrid approach combining CNN and LSTM architectures.

---

## 🎯 Objectives
- Predict artwork prices using image-based features  
- Apply deep learning techniques to a real-world regression problem  
- Explore hybrid architectures for improved prediction accuracy  

---

## 🧠 Key Features
- 🖼️ Image feature extraction using CNN  
- 🔗 Similarity learning using Siamese Network  
- 🔄 Context modeling using LSTM  
- ⚡ Hybrid CNN + LSTM model  
- 📊 Regression-based output (price prediction)  
- 📉 Evaluation using MSE and RMSE  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** PyTorch, Torchvision, NumPy, Pandas  
- **Environment:** Jupyter Notebook / Google Colab  

---

## ⚙️ Methodology
1. Data Preprocessing  
   - Image resizing and normalization  
   - Train, validation, test split  

2. Model Design  
   - CNN for feature extraction  
   - Siamese Network for similarity learning  
   - LSTM for sequential/contextual patterns  

3. Training  
   - Model trained on artwork dataset  
   - Optimization using loss functions  

4. Evaluation  
   - Metrics used: Mean Squared Error (MSE), Root Mean Squared Error (RMSE)  

---

## 📊 Results
- High similarity accuracy achieved using Siamese CNN  
- Low RMSE indicating good regression performance  
- Hybrid approach performed better than individual models  

---

## 🚧 Challenges Faced
- Handling large image datasets  
- Dataset imbalance across artists  
- Tensor shape mismatches during model fusion  
- Training stability and tuning  

---

## 🔮 Future Work
- Integrate with a web application for real-time predictions  
- Use advanced models like Vision Transformers (ViT)  
- Add metadata features (artist, year, style)  
- Improve dataset with real auction price data  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/Vaachi405/A-CNN-and-LSTM-based-Painting-price-prediction-system
