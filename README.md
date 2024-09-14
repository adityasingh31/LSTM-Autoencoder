# Efficient Data Stream Anomaly Detection

## Project Overview

This project implements a real-time anomaly detection system using an LSTM Autoencoder to analyze continuous data streams. The system is designed to detect unusual patterns, such as exceptional values or deviations from normal behavior, in data streams representing metrics like financial transactions or system performance.

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








