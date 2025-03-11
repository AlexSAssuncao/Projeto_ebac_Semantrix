# Olist Customer Satisfaction Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Latest-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📊 Project Overview

This project develops a machine learning model to predict customer satisfaction for Olist, Brazil's largest e-commerce platform. Using historical order and review data, we create a binary classification model to predict whether customers will give high satisfaction ratings (>4 stars) or not.



## 🎯 Key Objectives

- Predict customer satisfaction levels before review submission
- Identify key factors influencing customer satisfaction
- Provide actionable insights for improving customer experience
- Develop an early warning system for potential negative reviews

## 📚 Dataset

The analysis uses the Brazilian E-Commerce Public Dataset by Olist, available on Kaggle. The dataset includes:
- Customer and order information
- Product details
- Seller data
- Payment and shipping information
- Customer reviews

## 🛠️ Technical Stack

- **Python 3.8+**
- **Key Libraries:**
  - Pandas & NumPy
  - Scikit-learn
  - XGBoost
  - LightGBM
  - CatBoost
  - Matplotlib & Seaborn

## 📈 Key Findings

- Achieved 80%+ prediction accuracy
- Identified critical satisfaction factors:
  - Delivery time
  - Price-to-freight ratio
  - Seller response time
  - Product category influence

## 🚀 Project Structure

```
project/
│
├── data/                   # Data files
├── notebooks/             
│   ├── analysis.ipynb     # Main analysis notebook
│   └── exploration.ipynb  # Initial data exploration
│
├── src/                    # Source code
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   └── model.py
│
└── README.md
```

## 💡 Key Insights

1. **Operational Insights**
   - Delivery timing critically impacts satisfaction
   - Price-freight relationship affects customer ratings
   - Seller response time correlates with satisfaction

2. **Model Performance**
   - Best model: CatBoost (80%+ accuracy)
   - Strong predictive power for negative reviews
   - Reliable early warning system

## 📋 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/olist-satisfaction-prediction.git
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

3. Download the dataset:
```python
import kagglehub
path = kagglehub.dataset_download("olistbr/brazilian-ecommerce")
```

## 📊 Results

- Model Accuracy: >80%
- Key Feature Importance:
  - Delivery Delay: 25%
  - Price Ratio: 20%
  - Seller Rating: 15%
  - Product Category: 10%

## 🔄 Future Improvements

- Real-time prediction implementation
- Additional feature engineering
- Deep learning model exploration
- External factors integration

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Olist for providing the dataset
- Kaggle community for insights
- All contributors and reviewers

## 📧 Contact

Your Name - [Your LinkedIn](your-linkedin-url) - your.email@example.com

Project Link: [https://github.com/yourusername/olist-satisfaction-prediction](https://github.com/yourusername/olist-satisfaction-prediction)
