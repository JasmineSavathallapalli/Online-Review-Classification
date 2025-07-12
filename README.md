# Online-Review-Classification

A machine learning project to classify online product reviews as **real** or **fake** using XGBoost, DNN, and a fine-tuned **BERT transformer model** — with progressively improving accuracy.


## 📌 Project Description

This project explores fake review detection using traditional ML and modern deep learning approaches. We start with XGBoost and a simple DNN model, and finally fine-tune BERT to achieve superior performance. 


## 🚀 Features

- XGBoost, DNN, and BERT comparison
- Cleaned and labeled review dataset
- Real-time prediction with confidence


## 🗃️ Dataset

- Custom-labeled dataset (`fake reviews dataset.csv`)
- Labels: `CG` (fake), `OR` (real)
- Binary mapped: `1 = Fake`, `0 = Real`


## 🧠 Model Comparisons

| Model   | Accuracy |
|---------|----------|
| ✅ XGBoost | 84.8%    |
| ✅ DNN     | 87.9%    |
| ✅ BERT    | **98.0%** ✅ |

- **XGBoost:** fast and interpretable  
- **DNN:** better generalization with embeddings  
- **BERT:** state-of-the-art NLP performance  


🙏 Acknowledgements
- Hugging Face Transformers for pre-trained BERT models

- Scikit-learn for ML utilities

- PyTorch for deep learning framework

- Google Colab for training on GPU

- All open-source contributors and Kaggle community for supporting datasets and tutorials
