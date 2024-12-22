# End to End Machine Learning Project

This project is an end-to-end machine learning pipeline designed to predict student exam performance based on various features such as gender, race/ethnicity, parental level of education, lunch type, and test preparation course. The project includes data ingestion, preprocessing, model training, evaluation, and deployment.

## Project Overview

The goal of this project is to build a machine learning model that can accurately predict student performance in exams. The project follows a structured approach to ensure reproducibility and scalability.

## Features

- **Data Ingestion**: Load and split the dataset into training and testing sets.
- **Data Preprocessing**: Handle missing values, encode categorical variables, and scale numerical features.
- **Model Training**: Train multiple machine learning models and select the best-performing model.
- **Model Evaluation**: Evaluate the performance of the trained models using various metrics.
- **Model Deployment**: Save the trained model and preprocessing objects for future predictions.

## Project Structure

### `src` Directory

The `src` directory contains the main source code for the project, including data ingestion, preprocessing, model training, and utility functions.

### Additional Directories

- **`artifacts`**: Stores generated artifacts such as models and preprocessed data.
- **`logs`**: Contains log files generated during the execution of the project.
- **`notebook`**: Contains Jupyter notebooks for exploratory data analysis and experimentation.
- **`templates`**: HTML templates for the web interface.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Running the Project

To run the project, execute the following command:

```sh
python app.py