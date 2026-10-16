# Human Activity Recognition Using LSTM

## Project Overview
This project uses a Long Short-Term Memory (LSTM) neural network to classify human physical activities using smartphone sensor data.

The model is developed in Python using TensorFlow and Keras in Google Colab.

## Dataset
**Human Activity Recognition with Smartphones (HAR)**

Dataset link: https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones

The dataset contains smartphone sensor features associated with human activities.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Project Workflow
1. Dataset loading and exploration
2. Data cleaning and preprocessing
3. Activity label encoding
4. Feature scaling
5. Training and validation split
6. LSTM model development
7. Model training and evaluation
8. Accuracy and loss visualization
9. Classification report and confusion matrix
10. Activity prediction and model saving

## Model Architecture
The model uses LSTM layers, batch normalization, dropout, dense layers, and a softmax output layer for multi-class classification.

## Evaluation
The project evaluates the model using:
- Accuracy and loss
- Precision, recall, and F1-score
- Confusion matrix
- Actual versus predicted activity comparison

Final performance metrics should be reported from the executed notebook.

## Output Files
- `har_lstm_model.keras`
- `har_scaler.pkl`
- `har_label_encoder.pkl`
- `har_lstm_predictions.csv`

## How to Run
1. Open the project notebook in Google Colab.
2. Load the dataset.
3. Run the notebook cells in order.
4. Review the training graphs and evaluation results.
5. Save the model and prediction outputs.

## Author
**Shafaat Ullah**

## License
This project is intended for educational and learning purposes.
