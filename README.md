# 8thSem_project
Document Intelligent Project
Document Intelligence System

An end-to-end web application that transforms unstructured documents into meaningful insights using OCR and NLP techniques.

Overview

With the increasing volume of unstructured data such as PDFs, images, DOCX, and TXT files, manual processing becomes inefficient. This project automates the complete pipeline—from text extraction to summarization and keyword generation—making document analysis faster and more accessible.

Features
Upload multiple file formats (PDF, DOCX, TXT, Images)
Extract text using Tesseract OCR
Clean and preprocess extracted text
Generate concise summaries using a BART-based model
Extract meaningful keywords using KeyBERT
Download structured report (Word/JSON)
Tech Stack
Backend: Flask (Python)
OCR: Tesseract OCR
NLP Models: BART (Transformers), KeyBERT
Libraries: PyMuPDF, python-docx, OpenCV, NLTK
Workflow
Upload document
Detect file type
Extract text (OCR if needed)
Clean and preprocess text
Generate summary
Extract keywords
Generate downloadable report
Supported Formats
PDF (scanned and text-based)
DOCX
TXT
JPG / PNG images


Open in browser:
http://127.0.0.1:5000



Future Improvements
Multi-language support
Advanced summarization techniques
Cloud deployment (AWS/GCP)
User authentication and dashboard
