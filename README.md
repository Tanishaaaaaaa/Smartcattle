
![Logo](https://github.com/naeemmrz/MasPA.py/blob/main/MasPA_logo.png?raw=true)

# MasPA: Mastitis Prediction Application

## Overview

MasPA (Mastitis Prediction Application) is a machine learning-based tool developed to predict the risk of mastitis in cattle using Automated Milking System (AMS) sensor data. This application leverages a Random Forest Classifier to analyze various udder parameters and provide actionable insights for cattle health management.

## Features

- **User-Friendly Interface**: Developed with Streamlit for a seamless user experience.
- **Machine Learning Model**: Utilizes a pre-trained Random Forest Classifier to predict mastitis risk.
- **Data Input**: Accepts CSV files containing udder parameter data.
- **Visual Outputs**: Displays predictions in a visually appealing format with an easy-to-use search function for individual Cow IDs.
- **Background Information**: Provides links to the corresponding research article and more details about the project.

## How It Works

1. **Upload Data**: Users upload a CSV file containing the udder parameters of their cattle.
2. **Model Prediction**: The application processes the data and uses the Random Forest model to predict the mastitis risk for each entry.
3. **Visual Display**: Results are displayed with a visually enhanced layout, allowing users to search for specific Cow IDs to get detailed predictions.

## Usage

1. **Upload CSV File**: Ensure your data file is in CSV format with the required columns: `Months_after_giving_birth`, `IUFL`, `EUFL`, `IUFR`, `EUFR`, `IURL`, `EURL`, `IURR`, `EURR`, `Temperature`, `ID`.
2. **View Predictions**: After uploading, the predictions will be displayed. Use the search bar to look up specific Cow IDs.
3. **Download Results**: You can download the prediction results as a CSV file for further analysis.


### Prerequisites

- Python 3.8 or higher
- Streamlit
- Scikit-learn
- Pandas
- PIL

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/Tanishaaaaaaa/MasPA.git
    cd MasPA
    ```

2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Application**:
    ```sh
    streamlit run MasPA.py
    ```



By using this application, farmers and researchers can better monitor the health of their cattle, potentially preventing severe cases of mastitis through early detection and intervention.   
# MasPA.py

MasPA.py is an ML-based Web App that can predict the **Risk of Mastitis** in cattle from simple easy-to-obtain cost-effective sensor data.

## CREATOR

Tanisha Saxena
###### [Click Here For The Corresponding Article](https://doi.org/10.3390/agriengineering3030037)

