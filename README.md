# Table-Question-Answering

A Python application that performs question answering on tabular data using the TAPAS (TAble PArSing) model.

# Description

The Table Question Answering application is a Python program that allows you to upload a CSV or Excel file containing tabular data and ask questions about the data. It utilizes the TAPAS model from the Hugging Face Transformers library to perform question answering on the table.

# Features

> **Table Question Answering:** The application performs question answering on tabular data by utilizing the TAPAS model. It allows you to upload a CSV or Excel file, ask questions about the table, and obtain answers based on the data.

> **TAPAS Model:** The TableQuestionAnswering class uses the "google/tapas-large-finetuned-wtq" model from the Hugging Face Transformers library. This model is specifically trained for table question answering tasks.

> **Support for CSV and Excel:** The application supports uploading both CSV and Excel files for table input. It automatically converts Excel files to CSV format for processing

# Installation

**Clone the repository:**
https://github.com/AdopleAIOrg/Table-Question-Answering.git

**Install the required dependencies:**
pip install -r requirements.txt

# Usage

1. Run the application:

    !streamlit run app.py & npx localtunnel --port 8501

2. Access the application by opening the provided URL in your web browser.

3. Click on the "Upload a CSV file" button to select a CSV or Excel file containing tabular data.

4. Enter a question in the text input box.

5. The application will process the uploaded file and generate an answer based on the question and the table data.

6. The answer will be displayed below the question input.

# Contact

If you have any questions or feedback, feel free to contact me at ceo@adople.com.
