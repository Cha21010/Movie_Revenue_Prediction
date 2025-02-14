# 🎬 Movie Revenue Prediction

## 📌 Overview
This project aims to predict the revenue of movies based on various features such as budget, genre, cast, and more. Using machine learning techniques, the model analyzes historical movie data to forecast the revenue potential of new releases.
---
## 📂 Project Structure

```bash
├── data/                 # Dataset files
├── notebooks/            # Jupyter notebooks for data exploration & model building
├── models/               # Trained machine learning models
├── src/                  # Source code for data processing and training
│   ├── data_preprocessing.py     # Script for cleaning and preprocessing data
│   ├── feature_engineering.py    # Script for feature extraction and engineering
│   ├── model_training.py         # Script to train machine learning models
│   ├── model_evaluation.py       # Script to evaluate model performance
│   ├── predict.py                # Script to make predictions on new data
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── main.py               # Main script to run predictions
```
---
## 📊 Dataset
The dataset consists of movie-related features such as:
- 🎥 **Movie Title**
- 💰 **Budget**
- ⭐ **IMDb Rating**
- 🎭 **Genre**
- 🏆 **Awards**
- 👥 **Cast & Crew**
- 🏛 **Production Studio**
- ⏳ **Runtime**
- 📅 **Release Year**
- 💸 **Box Office Revenue (Target Variable)**
---
## 🛠 Installation
### 1. Clone the repository:
   ```r
   git clone https://github.com/Cha21010/Movie_Revenue_Prediction.git
   cd Movie_Revenue_Prediction
   ```
### 2. Install Required Dependencies
   ```r
   pip install -r requirements.txt
   ```
### 3. Data Preprocessing
  ```r
   python src/data_preprocessing.py
   ```
### 4. Train the Model
   ```r
   python src/data_preprocessing.py
   ```
### 5. Evaluate the Model
   ```r
   python src/model_evaluation.py
   ```
### 6. Predict Revenue
To predict movie revenue using a trained model:
  ```r
   python src/predict.py --input "new_movie_data.csv"
   ```
---
## 🧠 Machine Learning Models

The project tests multiple models to determine the best revenue predictor:

- 📈 **Linear Regression** – A simple model that establishes a relationship between the movie features and revenue.  
- 🌲 **Random Forest Regressor** – An ensemble model that uses multiple decision trees to improve predictive performance.  
- 🤖 **XGBoost** – A high-performance gradient boosting model for more accurate predictions.  
- 🔄 **Neural Networks (Optional Extension)** – Deep learning model to capture complex patterns in the data.  

---

## 📌 Results & Performance

- **Best Model:** [Specify Best Performing Model]  
- **Metrics Used:**  
  - 📉 **RMSE (Root Mean Squared Error)** – Measures prediction error magnitude.  
  - 📊 **MAE (Mean Absolute Error)** – Measures average prediction error.  
  - 📈 **R² Score (Coefficient of Determination)** – Assesses model goodness-of-fit.  
- **Insights:**  
  - Movies with higher budgets tend to generate more revenue.  
  - Star power and genre significantly influence box office performance.  

---

## 🏗 Future Improvements

- 🎞 **Improve Feature Engineering:** Enhance text-based features like cast names and movie descriptions.  
- 🎯 **Optimize Hyperparameters:** Utilize **GridSearchCV** and **RandomizedSearchCV** for better model tuning.  
- 📡 **Deploy Model:** Deploy as a **Flask** or **FastAPI** web service.  
- 📊 **Build a Web Dashboard:** Create an interactive dashboard using **Streamlit** to visualize predictions.  

---

## 🤝 Contributing

We welcome contributions from the community!  

To contribute:  
1. Fork the repository.  
2. Create a new branch for your feature/bugfix.  
3. Commit your changes with descriptive messages.  
4. Submit a pull request for review.  

Please ensure your code follows the project's style guidelines.  

---

## 📝 License

This project is licensed under the **MIT License**.  

See the [LICENSE](./LICENSE) file for more details.  

---

🎬 **Thank you for checking out our Movie Revenue Prediction project! 🚀**  
