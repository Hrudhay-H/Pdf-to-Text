# Pdf2Text:

Pdf2Text is an end-to-end Python tool that extracts text from any PDF, whether it’s digital or scanned, and automatically summarizes it using a transformer-based language model (`facebook/bart-large-cnn`).  
It is ideal for research papers, reports, invoices, or any text-heavy documents.

---

## Features

- Handles both text-based and scanned PDFs (via OCR)
- Tesseract OCR fallback for images and scanned pages
- Automatic summarization using Hugging Face transformers
- Exports both full text and summarized text as `.txt` files
- Progress bars for real-time extraction feedback
- Preprocessing support for better OCR accuracy

---

## Tech Stack

- pdfplumber — Text extraction from PDFs  
- pytesseract — Optical Character Recognition  
- pdf2image — PDF to Image conversion  
- transformers — Text summarization (BART model)  
- Pillow — Image processing  
- tqdm — Progress visualization  
- poppler-utils and tesseract-ocr — System-level dependencies  

---

## Installation

### Clone or open in Google Colab
