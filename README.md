# Deep Learning - Projects

**01. Stock Price Prediction with LSTM Neural Network**

- **Data Acquisition**: The project uses Yahoo Finance (yf) to download historical stock prices for Apple (AAPL) from a specified start date to today’s date.

- **Data Visualization**: It includes a Candlestick chart created with Plotly to visualize Apple’s stock price movements, highlighting the highs and lows.

- **Correlation Analysis**: A correlation matrix is computed to understand the relationship between different features and the ‘Close’ price of the stock.

- **LSTM Model**: The project constructs and trains a Long Short-Term Memory (LSTM) neural network to predict stock prices based on features like Open, High, Low, and Volume.

**02. Image Classification with Neural Networks**

- **Library Import**: It starts with importing necessary libraries like TensorFlow, Keras, NumPy, and Matplotlib.

- **Data Acquisition**: The project uses the Fashion MNIST dataset for fashion image.
  
- **Model Building**: A neural network model with two hidden layers is constructed for image classification.
  
- **Training**: The model is trained on the dataset, and the training process includes splitting the data into training and validation sets.

- **Prediction**: Finally, the model is used to predict the classes of new images, showcasing the output of the predictions.

**03. Credit Card Fraud Detection Model with Autoencoder Model**

- **Data Preparation**: The dataset is downloaded from Kaggle and preprocessed by removing null values, scaling the ‘Amount’ feature, and dropping the ‘Time’ feature due to lack of correlation.

- **Model Building**: An autoencoder model is built using Keras. The model consists of an input layer, two encoding layers, two decoding layers, and an output layer. The model is trained on non-fraudulent transactions to learn normal transaction patterns.

- **Training and Evaluation**: The autoencoder is trained for 10 epochs. The hidden representations from the autoencoder are used to train a Logistic Regression model for fraud detection. The model achieves an accuracy of 97.1%.

- **Results**: The classification report shows high precision and recall for both classes, indicating the model’s effectiveness in detecting fraudulent transactions.

**04. Data Augmentation for Image Processing**

- **Install Tensorflow**: The project starts with installing necessary packages like tensorflow_docs and tensorflow_datasets.

- **Image Augmentation**: Various augmentation techniques are applied to a single image, including flipping, grayscaling, saturation adjustment, brightness adjustment, rotation, and cropping.

- **Dataset Augmentation**: The MNIST dataset is augmented with techniques like random cropping and brightness adjustment.

- **Model Training**: Two models are trained—one with augmented data and one without. The augmented model shows better performance and less overfitting compared to the non-augmented model
