# Meter_Reading_OCR_Project

## 📌 Overview

This project automates the extraction of meter readings and relevant data from scanned utility bill images using Optical Character Recognition (OCR). It significantly reduces manual entry workload and improves data accuracy for billing workflows.

⚙️ Features

🔡 OCR Extraction: Detects and extracts text from scanned meter images using Tesseract and EasyOCR

📄 Data Parsing: Identifies key fields like meter readings and IDs

📦 Structured Output: Converts raw OCR output into clean, usable format (to be implemented)

📈 Performance Optimized: Achieved 40% reduction in manual effort and boost in data accuracy

🧠 Tech Stack
Language: Python

Libraries:

pytesseract – Tesseract OCR wrapper

EasyOCR – Lightweight, multilingual OCR

OpenCV, Pandas – For image pre-processing and output formatting

🖼️ Sample Workflow
1. Load utility bill image(s)
2. Preprocess image (grayscale, thresholding)
3. Run OCR engine (Tesseract + EasyOCR fallback)
4. Extract key information (meter number, units consumed, etc.)
5. Export results to CSV/JSON
