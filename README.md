# 🌟 Stock Price Prediction Using LSTM 🌟

Welcome to the **Stock Price Prediction Using LSTM** project! This project uses a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical data. The dataset employed in this project is for **TATA Global** stock prices.

---

## 🔬 Project Overview

The goal of this project is to build a predictive model that forecasts future stock prices by learning from historical data. This approach can assist in understanding trends and making informed decisions in the stock market.

---

## 🔍 Key Steps

### 1. ⚙️ Data Preprocessing:

- Load the dataset.
- Scale the features using `MinMaxScaler` for normalization.
- Create sequences of 60 time steps for training.

### 2. 🎨 Model Building:

- Construct an LSTM model with **four LSTM layers** and **dropout regularization** to prevent overfitting.
- Compile the model using the **'adam' optimizer** and **'mean\_squared\_error' loss function**.
- Train the model on the prepared training data.

### 3. 🔀 Prediction:

- Load the test dataset.
- Prepare the input data for predictions.
- Use the trained model to predict stock prices.
- Visualize the results by plotting **real vs. predicted stock prices**.

---

## 📂 Files

- **`NSE-TATAGLOBAL.csv`**: Historical stock prices for training the model.
- **`tatatest.csv`**: Stock prices used for testing and validating the model.
- **`Predictor.py`**: The main Python script for preprocessing data, training the model, and generating predictions.

---

## 📊 Dependencies

Ensure you have the following Python libraries installed:

- 🤼 **NumPy**
- 🎨 **Matplotlib**
- 📖 **Pandas**
- ⚛ **Scikit-learn**
- 🚀 **Keras**

---

## 🔧 How to Run

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your_username/Stock-Price-Prediction-LSTM.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Stock-Price-Prediction-LSTM
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the script to train and predict stock prices:

   ```bash
   python Predictor.py
   ```

---

## 🌍 Results Visualization

The results of the model’s predictions are visualized in a plot, showing the **real stock prices** vs. **predicted stock prices**, making it easy to evaluate the model's performance:

- 🔹 **Blue Line**: Actual stock prices.
- 🔹 **Orange Line**: Predicted stock prices.

---

## ✨ Contributing

We welcome contributions! If you have ideas for improving the model or code, feel free to:

1. Fork this repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your branch:
   ```bash
   git commit -m "Added a new feature"
   git push origin feature-name
   ```
4. Open a pull request.

---

## 📞 Contact

For any queries, feel free to reach out:

- Email: 2022eeb1217\@iitrpr.ac.in

---

🚀 **Happy Predicting!** 🌟

