# Data Analysis Web App

This Data Analysis Web App is built using **Streamlit** and **Python**. It provides an interactive platform for analyzing datasets. Users can upload a CSV file, and the app allows them to explore the dataset with several useful functionalities such as previewing data, checking data types, identifying missing values, removing duplicates, and summarizing statistics.

## Features:
1. **Upload a CSV Dataset**: Allows users to upload a CSV file for analysis.
2. **Preview Data**: Users can preview the first few rows (head) or last few rows (tail) of the dataset.
3. **Check Data Types**: Displays the data types of each column in the dataset.
4. **Dataset Dimensions**: Displays the number of rows or columns in the dataset based on the user's choice.
5. **Null Values Detection**: Highlights any missing values in the dataset using a heatmap.
6. **Duplicate Detection**: Allows users to check for duplicate values and offers an option to remove them.
7. **Dataset Summary**: Provides summary statistics of the dataset, including count, mean, std, min, max, etc.
8. **Interactive Features**: Provides checkboxes, buttons, and dropdowns for user interaction.

## Aim of the App:

The main aim of this app is to provide a simple and interactive interface for performing basic data analysis on any CSV dataset. The app helps in the following:

- Quickly inspecting data (preview, head, and tail).
- Understanding the structure of the data (data types and shape).
- Identifying and visualizing missing values.
- Detecting and removing duplicate rows.
- Summarizing the dataset with key statistics.

The app is designed to be user-friendly and requires no coding knowledge. Users can simply upload a dataset and interact with the app to gain insights into the data.

## How to Run the App:

1. **Install Required Libraries**:
   - Make sure you have **Python 3.x** installed.
   - Install the required libraries by running the following command:
     ```bash
     pip install streamlit pandas seaborn
     ```

2. **Run the Streamlit App**:
   - Save the Python code in a file (e.g., `data_analysis_app.py`).
   - In your terminal, navigate to the directory containing the file.
   - Run the following command to start the app:
     ```bash
     streamlit run data_analysis_app.py
     ```

3. **Interact with the App**:
   - Open your browser and go to `http://localhost:8501`.
   - Upload a CSV file and use the app's features for analysis.

## About:
- Built with **Streamlit** for quick and interactive data analysis.
- Designed to make data exploration easy for beginners and professionals alike.

## Credits:
- **Data Thinkers** (YouTube Channel for Tutorials).

link to use the app:
https://edaprojectwithappio-hserty66hkpaxzzemlaomm.streamlit.app/
