# FinHelp - FinancialAssistant - GENAI

## Project Description
FinHelp is an AI-based solution designed to provide interactive financial guidance through a comprehensive suite of modules. Developed using GENAI, this project aims to streamline financial tasks, enhance user interactions, and offer valuable insights into financial data. By integrating cutting-edge technologies such as natural language processing (NLP), optical character recognition (OCR), and machine learning, FinHelp empowers users to manage and analyze their financial information effectively.

## Overview
The Financial Assistant integrates three essential modules: the Ollama Language Model (LLM) Chatbot, an Optical Character Recognition (OCR) tool, and a Transaction Categorization component. This comprehensive solution streamlines financial tasks, enhances user interactions, and provides valuable insights into financial data.

## Ollama Language Model (LLM) Chatbot

### Description
The Ollama Language Model Chatbot is an intelligent interface for natural language interactions related to financial queries. Leveraging the capabilities of the Ollama language model, this chatbot understands user prompts and responds with detailed insights and information.

### Features
- **Conversational Interface:** Users can input prompts in natural language to inquire about various financial aspects.
- **Dynamic Responses:** The Ollama Chatbot generates dynamic and context-aware responses based on user queries.
- **Interactive Controls:** Users can seamlessly continue or exit conversations, providing a user-friendly experience.
- **Pre-Tuned for Finance:** The Ollama model is pre-tuned specifically for financial purposes, ensuring accurate and relevant responses in the financial domain.

### Usage
- Enter prompts in the provided text input.
- Click the "Invoke Model" button to receive responses.
- Utilize the "Continue" and "Exit" buttons to manage ongoing interactions.

## OCR Module

### Description
The OCR module enables users to extract text information from images containing financial transaction details. Using the Tesseract OCR engine, this module digitizes data from receipts, invoices, or any financial documents. The OCR tool is seamlessly integrated with the Ollama language model for a comprehensive understanding of extracted information.

### Features
- **Image Upload:** Users can upload images in formats such as .png, .jpg, or .jpeg.
- **OCR Processing:** The assistant performs OCR on the uploaded image to extract relevant text information.
- **Ollama Integration:** Extracted information is sent to the Ollama model for detailed analysis and insights.
- **Pre-Tuned for Finance:** The Ollama model, integrated with the OCR module, is specifically designed for financial purposes, ensuring accurate interpretation of financial transaction details.

### Usage
- Upload an image containing financial transaction details.
- Click the "Perform OCR & Invoke Model" button.
- View the extracted information and relevant insights.

## Transaction Categorization

### Description
The Transaction Categorization module processes a CSV file containing financial transactions and categorizes them based on user prompts. Utilizing the Ollama language model, this module seeks user input for categorization, enhancing the organization and analysis of financial data.

### Features
- **CSV Processing:** Transactions are read from a CSV file named "transactions_2022_2023.csv."
- **Interactive Categorization:** Users are prompted to categorize transactions interactively based on Ollama's guidance.
- **Category Definitions:** Predefined categories include Food and Drinks, Clothing, Services, Health and Wellness, Sport and Fitness, and Travel.
- **Pre-Tuned for Finance:** The Ollama model, integrated with the categorization module, is tailored for financial categorization, ensuring accurate and relevant guidance.

### Usage
- Ensure you have a CSV file named "transactions_2022_2023.csv" with a column named "Name / Description" containing transaction details.
- Follow prompts to categorize transactions interactively.
- View the categorized transactions, enhancing organization and analysis.

## Target Audience
- **Individual Users:** Everyday consumers seeking personalized financial guidance and assistance in managing their finances effectively.
- **Small Businesses:** Entrepreneurs and small business owners looking for tools to streamline financial tasks, categorize transactions, and gain insights into their financial data.
- **Financial Analysts:** Professionals in the finance industry who require intelligent tools for analyzing financial data, categorizing transactions, and providing financial recommendations.

## Model Tuning
To fine-tune the Ollama model specifically for financial tasks, ensure you have the text file "financial_planner.txt" during the tuning process. This file provides crucial context and parameters for the model to operate effectively as a financial assistant.

## Requirements
- Python 3.x
- Required Python packages: panel, langchain_community, Pillow, pytesseract, pandas, pydantic

## Installation
1. Install required packages:
    ```
    pip install panel langchain_community Pillow pytesseract pandas pydantic
    ```
2. Ensure Tesseract OCR is installed and set the path in the code:
    ```python
    pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'''
    ```

## Usage
1. Run the provided Python scripts for each module.
2. Follow the instructions within each script for a seamless and interactive financial assistant experience.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).




