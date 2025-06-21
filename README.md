Thanks for the clarification! Since your app was deployed using **Vercel**, not Streamlit Cloud, here's the updated and corrected version of your `README.md`:

---

# ❤️ Heart Failure Prediction System

Welcome to the **Heart Failure Prediction System** – a machine learning-powered web application that predicts the likelihood of heart disease in patients using medical parameters.

🔗 **Live App**: [heart-disease-app.vercel.app](https://heart-disease-app.vercel.app/)

## 🚀 Project Overview

This project helps in predicting the risk of heart failure using patient data. It uses a trained machine learning model and provides an intuitive web interface for real-time predictions.

Key features:

* Built with **Python**, **Streamlit**, and deployed using **Vercel**
* Predicts heart disease based on various clinical features
* Logistic Regression used as the core predictive model
* Clean and responsive UI for easy interaction

## 🧠 Model & Dataset

* 📚 **Dataset Used**: [Heart Disease UCI dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
* 🧹 **Preprocessing**:

  * Handled missing/null values
  * Encoded categorical variables like chest pain type, slope, etc.
  * Scaled features for better model performance
* 🤖 **Model**: Logistic Regression

  * Accuracy: \~86%
  * Evaluated using confusion matrix, ROC-AUC score, and classification metrics

## 📊 Features

* Real-time heart disease prediction
* User-friendly input form
* Backend logic in Python
* Deployed seamlessly on Vercel for production use

## 📁 File Structure

```
├── Heart_Failure_Prediction.ipynb  # Jupyter Notebook with full model pipeline
├── requirements.txt                # Python dependencies
├── README.md                       # Project documentation
```

## 🛠️ Tech Stack

* Python
* Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* Streamlit (as the web interface framework)
* Vercel (for frontend hosting)

## 🌐 Deployment

This application was deployed using **Vercel**. The frontend is powered by **Streamlit**, and the entire app was exported and configured for Vercel deployment using a `vercel.json` config and proper structure to serve the Streamlit interface as a static app via Vercel’s serverless platform.

## 🖥️ Run Locally

To test or run the app locally:

```bash
git clone https://github.com/yourusername/heart-failure-prediction.git
cd heart-failure-prediction
pip install -r requirements.txt
streamlit run Heart_Failure_Prediction.ipynb
```

## 🙌 Acknowledgements

* [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
* [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets)

---

Let me know if you also want to include badges (like deploy status or Python version), screenshots of the UI, or instructions for deploying on Vercel.
