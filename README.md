# Big-Data-Stockmarket
Stock Analysis and Prediction Using Big Data Analytics and Machine Learning

### Overview
This project explores the integration of **big data analytics** and **machine learning (ML)** techniques to predict daily stock returns, focusing specifically on US oil stocks. Utilizing Apache Spark's machine learning library, the system processes real-time financial data from Yahoo Finance, employing various algorithms such as **Autoregressive Integrated Moving Average (ARIMA)** and **Long Short-Term Memory (LSTM)** to analyze time-series data effectively.

### Key Features
- **Real-Time Data Processing**: Collects and analyzes stock data in real-time using Apache Spark.
- **Advanced Algorithms**: Implements ARIMA for linear relationships and LSTM for capturing complex, non-linear patterns in stock price movements.
- **Feature Engineering**: Utilizes the XGBoost algorithm to enhance prediction accuracy by selecting the most relevant features from the dataset.
- **Performance Evaluation**: Compares model performance using R-squared metrics, demonstrating that LSTM significantly outperforms ARIMA in prediction accuracy.

### Methodology
1. **Data Collection**: Real-time stock data is sourced from Yahoo Finance, divided into training and testing datasets.
2. **Data Normalization**: Ensures consistency across features through normalization techniques.
3. **Model Training**: Both ARIMA and LSTM models are trained on the processed dataset.
4. **Model Evaluation**: The models are evaluated using R-squared metrics to assess their predictive capabilities.

### Results
The study indicates that the LSTM model achieves an R-squared value of 0.91, showcasing its high accuracy in predicting stock prices compared to an R-squared value of 0.308 for the ARIMA model.

### Conclusion
This project highlights the transformative potential of big data analytics in financial forecasting, providing a scalable approach for real-time stock market analysis. Future work will focus on enhancing predictive capabilities by incorporating advanced machine learning techniques and automating analytical processes.

