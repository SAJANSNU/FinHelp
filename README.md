# FinHelp
AI based solution featuring an interactive chat for financial guidance
# FinHelp - FinancialAssistant - GENAI

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

## Model Tuning
To fine-tune the Ollama model specifically for financial tasks, ensure you have the text file "financial_planner.txt" during the tuning process. This file provides crucial context and parameters for the model to operate effectively as a financial assistant.

## Requirements
- Python 3.x
- Required Python packages: panel, langchain_community, Pillow, pytesseract, pandas, pydantic
## Usage
1. Run the provided Python scripts for each module.
2. Follow the instructions within each script for a seamless and interactive financial assistant experience.

Feel free to customize the code according to your requirements or integrate it into your financial management projects! The Financial Assistant aims to provide a versatile, user-friendly, and intelligent solution for managing and analyzing financial information, with a specific focus on fine-tuning the Ollama model for financial tasks using the "financial_planner.txt" file.

## Installation
1. Install required packages:
2. Ensure Tesseract OCR is installed and set the path in the code:
```python
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'


