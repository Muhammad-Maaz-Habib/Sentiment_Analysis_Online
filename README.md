# Sentiment Analysis on PDFs

## Description
This project performs sentiment analysis on text extracted from PDF files. The script downloads a PDF from a provided URL, extracts text from the PDF, analyzes the sentiment of each sentence using VADER, and then saves the sentiment scores to an Excel file.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Contact Information](#contact-information)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Muhammad-Maaz-Habib/Sentiment_Analysis_Online.git
    ```
2. Navigate to the project directory:
   
3. Install the required dependencies:
    ```bash
    pip install nltk fitz pandas openpyxl vaderSentiment requests
    ```

## Usage
1. Ensure you have the required Python packages installed (see [Installation](#installation)).

2. Run the script:

3. Enter the URL of the PDF file when prompted.

4. The script will process the PDF, perform sentiment analysis, and save the results to an Excel file named `Pdf_reader_python.xlsx` on your Desktop.

## Configuration
- **File Path**: The results are saved to `C:\Users\admin\Desktop\AiTEC\Pdf_reader_python.xlsx`. Modify the `file_path` variable in the script to change the location or filename.
- **Sentiment Analysis**: The script uses VADER (Valence Aware Dictionary and sentiment Reasoner) for sentiment analysis. Ensure you have the `vaderSentiment` library installed.

## Contributing
Feel free to open issues or submit pull requests for improvements. Please ensure your contributions adhere to the project's coding standards and provide clear documentation for any changes.


## Acknowledgements
- The sentiment analysis is performed using VADER from the `vaderSentiment` library.
- PDF text extraction is handled using `fitz` (PyMuPDF).

## Contact Information
For questions or feedback, please contact me at maazhabib2k4@gmail.com.
