# Wine-Type-Prediction-Neural-Network

This project implements a deep learning model to predict the type of wine (red or white) using the Wine Quality Dataset. It serves as a guided project for understanding deep learning concepts while showcasing my programming skills.

## Introduction

This project utilizes deep learning techniques to classify wines based on chemical properties. The model is designed to demonstrate the application of neural networks in binary classification tasks.

## Dataset

The **Wine Quality Dataset** can be found at the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/). It contains features like acidity, sugar, and alcohol content.

## Implementation Steps

1. **Libraries**: Imported libraries such as NumPy, Pandas, Matplotlib, and Keras.
2. **Data Preprocessing**: Loaded and combined red and white wine datasets, assigning labels.
3. **Visualization**: Created visualizations of alcohol distribution for each wine type.
4. **Data Splitting**: Divided the dataset into training and testing sets.
5. **Model Creation**: Constructed a neural network with three layers using Keras.
6. **Training**: Trained the model and made predictions on the test data.

```python
# Example code to train the model
model.fit(X_train, y_train, epochs=3, batch_size=1, verbose=1)
```

## Results

The model demonstrated an accuracy improvement from **89.04%** to **94.71%** over three epochs, showcasing effective learning.

## Acknowledgements

This project was inspired by a tutorial on GeeksforGeeks. While I followed the process outlined, I implemented and optimized the code independently to enhance my understanding.

## License

This project is licensed under the MIT License.
