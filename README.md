# 🚗 Car Price Prediction using Machine Learning

This project predicts the price of a car based on user-input features such as brand, fuel type, company, kilometers driven, and more. It uses a trained machine learning model (Linear Regression) and a Flask backend to deploy the prediction API.

## 🔧 Tech Stack

- Python 🐍
- Pandas, NumPy
- Scikit-learn (ML model training)
- Flask (web framework)
- Flask-CORS (cross-origin support)
- HTML/CSS (for the front-end, if applicable)
- VS Code / PyCharm
- Git & GitHub

## 📁 Project Structure

```
car-price-prediction/
│
├── application.py         # Flask backend app
├── model.pkl              # Trained machine learning model
├── templates/             # HTML frontend (optional)
│   └── index.html
├── static/                # CSS, JS, images
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── .gitignore             # Files to exclude from Git
```

## 🚀 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/car-price-prediction.git

# 2. Navigate to the project directory
cd car-price-prediction

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python application.py
```

Then open your browser and go to: `http://127.0.0.1:5000/`

## 📊 Model Details

- Model: Linear Regression
- Preprocessing: OneHotEncoding, ColumnTransformer
- Trained on cleaned car data with features like year, company, name, fuel type, kms driven

## 🧠 Prediction Example

You enter:

- Brand: Maruti
- Fuel Type: Petrol
- Year: 2015
- Kms Driven: 50000

- for output here is the screenshot
- <img width="1291" height="827" alt="image" src="https://github.com/user-attachments/assets/6fa8b93e-1eaf-4d12-8edc-99ef334b8301" />




## 💡 Future Improvements

- Add frontend using Streamlit or React
- Use XGBoost or RandomForest for better accuracy
- Save prediction history
- Dockerize the app
