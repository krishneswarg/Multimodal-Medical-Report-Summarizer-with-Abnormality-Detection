# Medical Report Summarizer

A web app that accepts medical report PDFs/images, extracts key findings, flags abnormal values, and generates plain-language summaries with downloadable JSON and PDF output.

## Tech Stack
- Frontend: React + Vite
- Backend: FastAPI
- OCR/Text Extraction: PyMuPDF, Tesseract
- PDF Export: FPDF

## Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload