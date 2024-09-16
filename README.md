# SPARK - Superior Performance Assessment and Real-time Kinetics

SPARK is an advanced system performance analytics application that collects real-time system data, stores it in a MySQL database, and provides detailed visualizations of performance metrics. Additionally, it creates machine learning models to predict future CPU and GPU usage, helping to optimize system efficiency.

## Features

- **Real-time System Monitoring**:
  - Collects real-time data on system metrics such as CPU utilization, GPU usage, memory usage, and more.
  - Data is stored in a MySQL database for historical tracking.

- **Visualization of ML Program Stats**:
  - Displays key metrics of machine learning programs being executed, such as:
    - Epochs
    - Training and validation accuracy
    - F1 score
    - Other model performance statistics

- **Machine Learning Predictions**:
  - Uses historical data to create machine learning models with the ARIMA algorithm.
  - Predicts CPU and GPU usage, enabling proactive performance optimization.

- **Frontend**:
  - The user interface is built using **React**, offering a clean and intuitive dashboard.
  - Real-time and historical data are visualized using charts and graphs.

- **Backend**:
  - The backend is developed using **Flask**, handling data ingestion and providing APIs for the frontend.

## Tech Stack

- **Frontend**: React
- **Backend**: Flask
- **Database**: MySQL
- **Machine Learning**: ARIMA (for time-series predictions)
- **Visualizations**: Chart.js / D3.js (for graphing performance metrics)

## Installation

### Prerequisites

- Node.js (for React)
- Python 3.x (for Flask)
- MySQL (for data storage)
- Required Python packages: Flask, MySQL connector, ARIMA (statsmodels), etc.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/krishmehta21/S.P.A.R.K---System-Performance-Analytics-App.git
