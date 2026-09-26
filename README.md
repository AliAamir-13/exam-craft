# ExamCraft — Question Paper Generator

A Streamlit-based Python web app that generates question papers from PDFs.

## Problem
Creating question papers manually from source material (textbooks, question banks) is repetitive and time-consuming — especially when the source is a scanned document rather than clean text.

## What it does
- Extracts text from text-based PDFs using **pdfplumber**
- Supports scanned PDFs via **OCR**, so image-only documents can be processed too
- Copies and structures MCQs from the extracted content into a usable question paper format

## Tech Stack
- **Language:** Python
- **Interface:** Streamlit
- **PDF text extraction:** pdfplumber
- **Scanned PDF support:** OCR

## Status
Early stage — currently runs on localhost. Actively improving extraction accuracy, UI, and working toward a public deployment.

## What I learned
Hands-on experience with Streamlit app development, PDF text extraction with pdfplumber, OCR pipelines for scanned documents, and structuring automated PDF-to-content workflows.

## Roadmap
- [ ] Improve MCQ extraction/structuring accuracy
- [ ] Polish the UI
- [ ] Upload source code
- [ ] Deploy a live demo link
- [ ] (Stretch) Support additional question types (fill-in-the-blank, short answer)

---
*Code coming soon — this repo currently documents the project scope and design.*
