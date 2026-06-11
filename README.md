# NLP Document Analyzer

## Overview

NLP Document Analyzer is a Streamlit-based application that generates concise summaries from PDF, DOCX, and TXT documents using Natural Language Processing (NLP) techniques. The application extracts text, analyzes content, and produces meaningful summaries along with document statistics.

## Features

- Upload PDF, DOCX, and TXT files
- Automatic text extraction
- Extractive text summarization
- Adjustable summary length
- Document statistics and evaluation metrics
- Compression ratio calculation
- Download generated summaries

## Technologies Used

- Python
- Streamlit
- NLTK
- PyPDF
- Python-Docx

## Installation

```bash
git clone https://github.com/SAPASHK-KS/NLP-DocumentAnalyzer.git

cd NLP-DocumentAnalyzer

pip install -r requirements.txt

streamlit run app.py
```

## Project Structure

```text
NLP-DocumentAnalyzer/
│
├── app.py
├── requirements.txt
├── doc_summarizer.ipynb
├── README.md
└── sample_documents/
```

## Future Enhancements

- Transformer-based summarization
- Multi-language support
- Keyword extraction
