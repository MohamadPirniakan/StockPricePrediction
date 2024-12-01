# Stock Price Prediction  

A time series forecasting project for stock prices using machine learning models including **RNN**, **LSTM**, and **GRU**. The project is implemented in Python and leverages TensorFlow for model building, training, and evaluation.  

---

## 📋 Table of Contents  
- [Overview](#overview)  
- [Features](#features)  
- [Technologies](#technologies)  
- [Dataset](#dataset)  
- [Setup and Installation](#setup-and-installation)  
- [Usage](#usage)   
- [Contributing](#contributing)  
- [License](#license)  

---

## 📖 Overview  
This project aims to predict stock prices based on historical data. By using sequential models such as RNN, LSTM, and GRU, the system generates predictions for future stock values. This project is designed to help explore the power of deep learning in time series forecasting.  

---

## 🌟 Features  
- Data fetching from Yahoo Finance using `yfinance`.  
- Scalable preprocessing pipeline with `MinMaxScaler`.  
- Sequence generation for time series modeling.  
- Implementation of **RNN**, **LSTM**, and **GRU** models with TensorFlow.  
- Model checkpointing and early stopping for optimal performance.  
- Visualizations for actual vs. predicted stock prices.  

---

## 🛠 Technologies  
- **Programming Language**: Python  
- **Libraries**:  
  - [NumPy](https://numpy.org/)  
  - [Pandas](https://pandas.pydata.org/)  
  - [Matplotlib](https://matplotlib.org/)  
  - [Scikit-learn](https://scikit-learn.org/)  
  - [TensorFlow](https://www.tensorflow.org/)  
  - [yfinance](https://pypi.org/project/yfinance/)  

---

## 📊 Dataset  
The dataset is dynamically fetched from Yahoo Finance. The default symbol used is **GOOGL (Google)**, and the data spans from April 1, 2020, to April 1, 2023.  

---

## ⚙️ Setup and Installation  
1. **Clone the repository**:  
   ```bash
   https://github.com/MohamadPirniakan/Stock_price_prediction.git
   cd StockPricePrediction
   ```  

2. **Install dependencies**:  
   Ensure you have Python 3.8 or above installed, then run:  
   ```bash
   pip install -r requirements.txt
   ```  

3. **Run the script**:  
   Execute the main script to start training models and generating predictions:  
   ```bash
   StockPricePrediction.ipynb
   ```  

---

## 🚀 Usage  
- Modify the `stock_symbol`, `start_date`, and `end_date` in the script to work with different stocks or timeframes.  
- Check the `models/` folder for saved models after training.  
- View the generated logs in the `logs/training.log` file.  


---

## 🤝 Contributing  
Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch for your feature/bugfix.  
3. Submit a pull request.  

---

## 📜 License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.  

---

## 🔗 Links  
- [TensorFlow Documentation](https://www.tensorflow.org/)  
- [Yahoo Finance API](https://pypi.org/project/yfinance/)  
- [Project Repository](https://github.com/your-username/StockPricePrediction)  
```  
