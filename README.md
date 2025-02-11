**# Student Sentimental Analysis - UiPath Project**

## Overview
The **Student Sentimental Analysis** project is a UiPath automation designed to analyze student sentiment from textual data. It extracts, processes, and classifies student feedback into positive, negative, or neutral sentiments using Natural Language Processing (NLP) techniques.

## Features
- Extracts student feedback from various sources (Excel, CSV, or web scraping)
- Preprocesses text data (removing stopwords, tokenization, etc.)
- Uses NLP or API-based sentiment analysis for classification
- Generates reports with sentiment insights

## Prerequisites
Before running the automation, ensure you have the following:
- UiPath Studio installed (latest version recommended)
- Python installed (if using external NLP models)
- Required dependencies installed (UiPath packages for data processing, Excel, and API calls)
- Sentiment Analysis API key (if using an external API like Google NLP, Azure Text Analytics, or AWS Comprehend)

## Installation & Setup
1. Clone or download the UiPath project to your local machine.
2. Open UiPath Studio and load the project.
3. Install necessary dependencies via UiPath Package Manager.
4. Configure API keys and paths in the **Config.xlsx** file.
5. Ensure the input data file (Excel or CSV) is placed in the designated folder.

## Workflow Explanation
1. **Data Extraction**
   - Reads student feedback from Excel, CSV, or web-based sources.
2. **Preprocessing**
   - Cleans and formats text data (removes punctuation, stopwords, etc.).
3. **Sentiment Analysis**
   - Uses a pre-trained NLP model or external API to classify sentiments.
4. **Report Generation**
   - Summarizes sentiment distribution and exports results to Excel or dashboard.

## Usage
1. Run the **Main.xaml** file in UiPath Studio.
2. Review the generated sentiment classification report.
3. Adjust configurations as needed for different data sources.

## Output
- **Processed Student Sentiment Report** in Excel or CSV format
- Optional: Dashboard integration for visualization

## Troubleshooting
- If the workflow fails to extract data, check input file paths.
- If sentiment analysis is incorrect, verify API connectivity or NLP model accuracy.
- Ensure UiPath dependencies are properly installed.

## Future Enhancements
- Integration with real-time feedback collection from Google Forms or chatbots.
- Advanced machine learning models for improved sentiment accuracy.
- Multi-language support for sentiment analysis.

## Author
- Developed by NithishKumarsd
- Contact: nithishkumar.2205105@srec.ac.in

