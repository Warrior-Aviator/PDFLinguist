# PDFLinguist: A Translation Solution to PDF Documents
PDFLinguist is a powerful and user-friendly tool designed to address the complexities of multilingual document management. It extracts text and images from both scanned and digital PDFs, translates the content into the desired language, and reassembles it into a new, well-formatted PDF. This project simplifies and enhances the translation process, ensuring document integrity and contextual accuracy across languages.

# Features
-> Supports Multiple Languages: Translate PDFs into English, Hindi, Kannada, or Russian.
-> Scanned and Digital PDFs: Process both scanned PDFs using OCR and digital PDFs for direct text extraction.
-> Header/Footer Removal: Customize header and footer removal for improved translation accuracy.
-> High-Quality Output: Retain the original formatting, layout, and structure in the translated PDF.
-> User-Friendly Interface: A simple, interactive web-based interface built with Streamlit.

# Libraries and Tools

Frontend:
Streamlit: Web-based user interface.

Backend:
PyMuPDF: Text and image extraction from PDFs.
PyTesseract: OCR for scanned PDFs.
Googletrans: Language translation.
Pillow: Image processing.
PDF2Image: PDF-to-image conversion.
FPDF: PDF generation for output files.

APIs:
LightPDF API: Accurate file conversions.
ConvertAPI: Advanced PDF manipulations.

# Usage

Upload PDF: Start by uploading a scanned or digital PDF.

Customize:
-> Crop headers/footers for scanned PDFs.
-> Select the desired output language.

Translate: The system extracts, translates, and formats the content.

Download: Get the translated PDF with preserved formatting.

# System Requirements

Operating System: Windows 10+, macOS, or Linux.
Python Version: 3.12+

# Methodology

Input and Preprocessing:
-> Upload PDF.
-> For scanned PDFs, headers and footers are cropped using image processing tools.

Content Extraction:
-> OCR is applied to images for text recognition.
-> Direct text extraction for digital PDFs.

Translation:
Text is translated using Google Translate API with Unicode support for Indic languages.

Output Generation:
Translated text is reassembled into a clean PDF using FPDF.

# Results

-> Efficient text extraction and translation for both scanned and digital PDFs.
-> Retention of formatting, including headers and footers as per user selection.
-> Accurate translations, especially for Indic languages.

# Future Scope
-> Adding support for more languages.
-> Enhancing OCR accuracy for complex scripts.
-> Incorporating user feedback for iterative improvements.

# Contributing
We welcome contributions! Please fork this repository, create a branch, and submit a pull request.
