# house-price-prediction-streamlit
This is a simple and interactive web application built with **Streamlit** that predicts housing prices based on various features like area, bedrooms, bathrooms, and more. The machine learning model used is a **Linear Regression** model trained on the `Housing.csv` dataset.

---

## Features

- 🧠 Train and run a regression model on housing data
- 📥 User inputs to dynamically predict house prices
- 📊 Visual insights:
  - Price distribution plot
  - Correlation heatmap of all numeric variables
- 🔄 Live updates with each prediction

---

## 🗂Project Structure

├── housepriceapp.py          # Main Streamlit app
├── Housing.csv               # Dataset used for training
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation

---

## 🧰 Technologies Used

- Python 3.7
- Streamlit
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib

---

## ▶️ How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/streamlit-house-price-predictor.git
cd streamlit-house-price-predictor
```

### 2. (Recommended) Create a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On macOS/Linux
```

### 3. Install Required Libraries
```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App
```bash
streamlit run housepriceapp.py
```

Once it runs, it will open automatically in your default browser.

---

## 📊 Dataset Info

The dataset (`Housing.csv`) includes features like:
- Area (in sq. ft.)
- Number of bedrooms and bathrooms
- Stories
- Road access, guest room, basement availability
- Furnishing status
- Parking spaces
- And the target column: **Price**

---

