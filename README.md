# SP500 Price Movement Prediction  
> A financial analysis project focused on predicting the price movement of the S&P 500 index.

> The project aims to predict whether the price of the S&P 500 index will move up or down based on historical data, utilizing a combination of machine learning and deep learning algorithms, including Long Short-Term Memory (LSTM) networks.

> Extensive feature engineering was employed, including the calculation of rolling averages and other financial indicators, to provide better context and improve model accuracy.

> The predictive models were further refined by implementing a custom learning rate schedule that decreases over time, helping to enhance the model’s performance during training.

> Model evaluation and optimization were key components, ensuring that the predictions were both accurate and reliable.

## Design Process and Methods  
> **Data Collection and Preprocessing:**  
> - Historical data for the S&P 500 index was collected, including daily prices, volumes, and other relevant financial metrics.  
> - Preprocessing involved cleaning the data, removing unwanted columns, and normalizing features to prepare them for model training.

> **Feature Engineering:**  
> - Rolling averages were calculated over various time windows to capture trends and provide additional context for the models.  
> - Additional financial indicators, such as moving averages, were also computed to enhance the predictive power of the models.  
> - Feature selection techniques were applied to identify the most relevant variables for predicting price movements.

> **Prediction Models:**  
> - **Machine Learning Algorithms:**  
>   - A variety of machine learning models, including Decision Trees, Random Forests, and Support Vector Machines (SVM), were implemented to predict the direction of price movement.  
> - **Deep Learning Algorithms:**  
>   - A deep neural network (DNN) and Long Short-Term Memory (LSTM) networks were constructed to capture more complex patterns in the data, particularly the temporal dependencies inherent in financial time series data.  
>   - The LSTM model was particularly useful in modeling sequential data, capturing long-term dependencies to improve prediction accuracy.  
>   - Both models were trained with a custom learning rate that decreased as training progressed, allowing for fine-tuning and better generalization.

> **Model Evaluation:**  
> - Model performance was evaluated using metrics such as accuracy, precision, recall, and the F1-score to ensure reliable predictions.  
> - Cross-validation was used to assess model robustness across different time periods, helping to avoid overfitting.  
> - Confusion matrices were generated to visually analyze the performance and fine-tune the models accordingly.

> **Results and Impact:**  
> - The models demonstrated significant accuracy in predicting the directional movement of the S&P 500 index, providing valuable insights for traders and financial analysts.  
> - The incorporation of rolling averages, other engineered features, and the use of LSTM networks, along with the custom learning rate schedule, significantly improved the model’s predictive performance.  
> - The project offers a practical approach for financial forecasting, combining traditional machine learning techniques with advanced deep learning methods.
