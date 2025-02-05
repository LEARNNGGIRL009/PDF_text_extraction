# PDF_text_extraction
# PDF Text Extraction Tool

A tool for extracting different types of content from PDF files:
- Text extraction (both printed and handwritten)
- Image extraction
- Blue handwritten text extraction

## Features

- Extract printed and handwritten text using Tesseract OCR
- Extract embedded images from PDFs
- Detect and extract blue handwritten text with color-based detection
- Debug visualization outputs
- Output formats: CSV and Excel

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/pdf_text_extraction.git
cd pdf_text_extraction
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Make sure you have Tesseract OCR installed on your system:
- For Windows: Download and install from https://github.com/UB-Mannheim/tesseract/wiki
- For Linux: `sudo apt-get install tesseract-ocr`
- For Mac: `brew install tesseract`

## Usage

Open `PDF_Text_Extraction.ipynb` in Jupyter Notebook or JupyterLab to:
- Extract text and images from PDFs
- Process handwritten text
- View the extraction results

The notebook contains all necessary code and documentation for each step.

## Output Files

- `output/construction_text_database.csv`: Extracted text data
- `output/detected_regions.xlsx`: Information about detected text regions
- `output/extracted_images/`: Directory containing extracted images
- `output/debug_output/`: Debug visualizations of text detection

## Requirements

See `requirements.txt` for complete list of Python dependencies.
