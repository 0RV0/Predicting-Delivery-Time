# Predicting-Delivery-Time
Developed a cognitive application for Logistics using Neural Network.

In this project, we built a cognitive application using neural networks to predict delivery time based on shipment parameters. 

Here's a quick breakdown of what we did:
1. Dataset and Preprocessing
Boston Housing dataset (from Keras) was used to simulate logistics-like data.
We scaled the data using StandardScaler to ensure smooth training of the neural network.
2. Neural Network Model (MLP)
We used Sequential Neural Network (MLP) with:
Two hidden layers (64 units each)
ReLU activation and Dropout for regularization
Adam optimizer and MSE loss for regression
The model was trained for 50 epochs with early stopping to avoid overfitting.
3. Visualizing Training Performance
We plotted training and validation loss to monitor model performance over epochs.
4. User Interface (UI) with Widgets
Built a UI in Colab using ipywidgets:
Sliders and dropdowns to input shipment details:
Weight (kg), Distance (km), Priority, and Transport Type
Predict Button to generate predictions in real-time.
Displayed predicted delivery time in hours based on user inputs.
5. Prediction Example
Input Parameters: Weight, Distance, Priority (Low/Medium/High), Transport (Air/Ground/Sea).
Output: Predicted delivery time in hours.
Outcome and Next Steps
This application demonstrates how neural networks can be used in logistics for delivery time predictions. With real-world logistics datasets, it can be further enhanced to predict shipping costs, delays, or optimal transport modes.
