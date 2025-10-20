# Alice Session Detection
This is my personal project which i've done while completing the [mlcourse.ai](https://mlcourse.ai/book/index.html) course.

It is inspired on [Catch Me If You Can ("Alice")](https://www.kaggle.com/competitions/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2/submissions) competition on Kaggle which had a baseline of **0.93 ROC-AUC** score which I've beat getting the **~0.95** score.

## Project Overview
The goal of this competition is to build a machine learning model that predicts whether a given web session belongs to a specific user (*Alice*) based on browsing behavior.
The project covers the ML principles - from feature engineering and time-based analysis to model training and evaluation.  
It was completed as part of my self-study on machine learning fundamentals using real-world data.

## Key Features
- Exploratory Data Analysis (EDA) and visualization of user behavior  
- Feature engineering: time-of-day, session duration, etc... 
- Handling sparse data with `csr_matrix` and `hstack`  
- Logistic Regression with `TimeSeriesSplit` cross-validation  
- Model evaluation using **ROC-AUC**  
- Model saving/loading with **pickle**

## 🏆 Results
- Final model achieved **ROC-AUC = 0.95** on the validation set  
- Outperformed the Kaggle competition baseline of 0.93  

## Future Improvements
- Experiment with Gradient Boosting models  
- Add deep learning baseline using PyTorch/Tensorflow 
- Optimize feature selection and hyperparameters  
- Deploy a simple web demo for predictions

### Environment setup
You can run this project using either **Anaconda** or **pip**.

**Option 1 – Conda**

```bash
conda env create -f environment.yml
conda activate alice-session
```

**Option 2 – pip**

```bash
pip install -r requirements.txt
```
