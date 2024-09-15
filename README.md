# Efficient Data Stream Anomaly Detection

## Project Overview

This project implements a real-time anomaly detection system using an LSTM Autoencoder to analyze continuous data streams. The system is designed to detect unusual patterns, such as exceptional values or deviations from normal behavior, in data streams representing metrics like financial transactions or system performance.

## WHY LSTM-Autoencoder?

<img width="850" alt="autoencoder-architecture" src="https://github.com/user-attachments/assets/c334f979-f86e-454f-84ae-6eb05cb8dd52">

Based on the data and the requiremnets of the project it is best to choose LSTM Autoencoder for high accuracy and noise tolerance here the reasons -

1. They can be trained on large amounts of data without requiring manual feature engineering, this makes them particularly useful for analyzing complex time series data with multiple variables or high dimensionality.
2. LSTM Autoencoders can adapt to changes in data distributions and concept drift, which is vital for real-time anomaly detection where the nature of the data may evolve over time.
3. LSTM networks can remember long-term dependencies, allowing them to learn and recognize complex patterns and sequences. This is crucial for detecting anomalies in data streams with varying patterns and long-term trends.
4. By combining LSTM's ability to handle temporal sequences with the autoencoder's reconstruction capabilities, this model can recognize and flag complex and subtle anomalies that simpler models might miss.

## Features

- **Data Stream Simulation**: Generates synthetic data from August 2024 to September 14, 2024, including regular patterns, seasonal variations, and random noise.
- **Preprocessing**: Normalizes data and prepares sequences for input into the LSTM Autoencoder model.
- **Anomaly Detection**: Uses LSTM Autoencoder to identify anomalies based on reconstruction errors, adapting to concept drift and varying data distributions.
- **Real-Time Visualization**: Provides interactive animation of the data stream and detected anomalies using Plotly.
- **Robustness**: Handles noisy data and effectively detects subtle deviations from normal patterns.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/anomaly-detection.git
   
2.  Install Dependencies
    pip install -r requirements.txt
   
## Usage
1. Generate Data and Train Model
   Run the main script to generate synthetic data, train the LSTM Autoencoder model, and perform anomaly detection:
   python main.py
2. View Results
   After running the script, the real-time visualization of the data stream and detected anomalies will be displayed using Plotly.

## Technical Details

Algorithm Selection: The LSTM Autoencoder was chosen for its high accuracy and robustness in detecting anomalies in sequential data. It is well-suited for handling noisy data and adapting to concept drift and seasonal variations.
Data Stream Simulation: Uses synthetic data generation to simulate real-time sequences with patterns and noise.
Preprocessing: Scales and prepares data sequences for the model input.
Anomaly Detection: Identifies anomalies based on reconstruction errors using the LSTM Autoencoder.
Visualization: Animated plots with Plotly to visualize data and anomalies over time.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

## Contact
For any questions or feedback, please contact adiwork01.singh@gmail.com








